

```markdown
# SEO Audit Tool

Explore comprehensive SEO insights with our SEO Audit Tool. This tool crawls your website, identifying SEO issues and opportunities to enhance your site's performance.

## Table of Contents

- [Features](#features)
- [Input](#input)
- [Results](#results)
- [Example Result](#example-result)
- [Connect With Us](#connect-with-us)
- [Support](#support)

## Features

Our SEO Audit Tool performs a detailed crawl of your website, checking for a range of SEO factors that influence your site’s visibility and performance.

## Input

**Web URL**: The starting point for the crawl. Set this to the homepage or a specific page URL you want to analyze.

## Results

Results are stored in Apify datasets with attributes such as page URL, title, load status, presence of SEO tags, and much more, providing a comprehensive view of your SEO health.

### Attributes Include:

- **url**: Page URL
- **title**: Page title
- **isLoaded**: Page load status
- **SEO Tags**: Checks for Google Analytics, meta tags, and character encodings
- **Content Checks**: Evaluates the presence and adequacy of titles, descriptions, H1 tags, and overall content length
- **Link Analysis**: Counts internal and external links, checks for no-follow attributes
- **Media Analysis**: Lists unoptimized images and counts broken image links
- **Advanced Checks**: Assesses viewport settings, AMP compatibility, and the absence of iframes
- **Error Tracking**: Lists and counts broken links
- **Structured Data**: Checks for JSON-LD and Microdata

## Example Result

```json
{
  "url": "https://www.example.com/",
  "title": "Your Online Store - Home",
  "isLoaded": true,
  "isGoogleAnalyticsObject": true,
  "metaDescription": "Discover our range of products.",
  "isMetaDescriptionEnoughLong": true,
  "isTitleEnoughLong": true,
  "h1": "Welcome to Your Online Store",
  "isH1OnlyOne": true,
  "linksCount": 87,
  "internalNoFollowLinksCount": 0,
  "notOptimizedImagesCount": 3,
  "wordsCount": 1152,
  "isContentEnoughLong": true,
  "isViewport": true,
  "brokenLinksCount": 0,
  "brokenImagesCount": 2,
  "jsonLd": {
    "isJsonLd": true
  },
  "microdata": {
    "isMicrodata": true
  }
}
```

## Connect With Us

- **YouTube**: [Visit our channel](https://www.youtube.com/@CodeMaster-421)
- **Instagram**: [Follow us on Instagram](https://www.instagram.com/quicklifesolutionsofficial/)
- **AI Newsletter**: [Subscribe to our newsletter](https://sendfox.com/quicklifesolutions)
- **Free Consultation**: [Book a free consultation call](https://tidycal.com/quicklifesolutions/free-consultation)
- **More Tools**: [Explore our Apify actors](https://apify.com/dainty_screw)

### Support

- **Discord**: [Raise a Support ticket here](https://discord.gg/2WGj2PDmHb)
- **Email**: [Contact us](mailto:codemasterdevops@gmail.com)
```
