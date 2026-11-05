# Apify Scrapers by Smoldesk Studios

Scrapers for public data that needs no login, cookies or API key. Every one of them runs on the [Apify Store](https://apify.com/smoldesk). You pay per result with no monthly fee. Export to JSON, CSV or Excel, or call them from the Apify API, Make, Zapier, n8n or an AI agent over MCP.

This repo is the catalog. The scrapers run on Apify, so there's no code to install here.

| Scraper | What it gets | Price |
|---|---|---|
| [Weibo Scraper](#weibo-scraper) | Posts, comments, profiles, hot search | $8 / 1,000 posts |
| [Toutiao Scraper](#toutiao-scraper) | News search, comments, hot board | $2 / 1,000 articles |
| [WeChat Articles Scraper](#wechat-articles-scraper) | Official Account articles, full text, images | $8 / 1,000 articles |
| [YouTube Scraper](#youtube-scraper) | Videos, Shorts, channels, comments | $1 / 1,000 videos |
| [Bilibili Scraper](#bilibili-scraper) | Videos, comments, danmaku, creators | $2.50 / 1,000 videos |
| [Telegram Channel Scraper](#telegram-channel-scraper) | Channel messages, views, reactions | $1 / 1,000 messages |
| [Substack Scraper](#substack-scraper) | Newsletters, subscriber counts, posts | $3 / 1,000 newsletters |
| [Google Trends Scraper](#google-trends-scraper) | Interest over time, regions, related queries | $1.50 / 1,000 results |
| [Google Ads Transparency Scraper](#google-ads-transparency-scraper) | Competitor ads, countries, reach | $1 / 1,000 ads |
| [Google Hotels Scraper](#google-hotels-scraper) | Hotel prices, ratings, booking sites | $2.50 / 1,000 hotels |
| [Google Hotels Price Calendar](#google-hotels-price-calendar) | Cheapest rate per check-in date, a year ahead | $1 / 1,000 dates |
| [Shopify Store Analyzer](#shopify-store-analyzer) | Store apps, theme, contacts, products | $5 / 1,000 stores |
| [SEEK, JobStreet & JobsDB Scraper](#seek-jobstreet--jobsdb-scraper) | Jobs and salaries in APAC | $0.80 / 1,000 jobs |
| [Career Site Jobs Scraper](#career-site-jobs-scraper) | Jobs from Greenhouse, Lever, Workday and more | $2 / 1,000 jobs |
| [Tennis Scraper](#tennis-scraper) | Results, odds, H2H, ATP/WTA rankings | $2 / 1,000 matches |

## Social media

### Weibo Scraper

Scrape Weibo (新浪微博) without logging in. Search any keyword or #hashtag within a date range, pull full post text, likes, comments and reposts, comment and reply threads, user profiles and the hot-search board (热搜) with heat values. Mix keywords, post links, profiles and trending in one run and duplicates are dropped. Built for brand monitoring, social listening and China market research: schedule it with **Only new posts** to get just the new mentions of your brand.

$8 per 1,000 posts or profiles, $1 per 1,000 comments or hot-search topics.

**[Open Weibo Scraper on Apify](https://apify.com/smoldesk/weibo-scraper)** · [GitHub](https://github.com/smoldesk/weibo-scraper)

### Toutiao Scraper

Scrape Toutiao (今日头条), China's biggest news app, without logging in. Search any keyword within a date range and get articles and videos with reads, plays, likes, comments and shares, the comment and reply threads, and the hot board (热榜) with heat scores. Has a monitor mode that only returns new articles.

$2 per 1,000 articles or videos, $1 per 1,000 comments or hot-board topics.

**[Open Toutiao Scraper on Apify](https://apify.com/smoldesk/toutiao-scraper)** · [GitHub](https://github.com/smoldesk/toutiao-scraper)

### WeChat Articles Scraper

Scrape WeChat Official Account (微信公众号) articles without a WeChat account or login. Search any keyword through Sogou WeChat search and get each article's full text as Markdown and plain text, images, publish time, account name and ID, author, the original/repost flag and IP location. Paste article links to get their full text, or schedule it with **Only new articles** to monitor a brand.

$8 per 1,000 articles with full text, $2 per 1,000 search cards.

**[Open WeChat Articles Scraper on Apify](https://apify.com/smoldesk/wechat-articles-scraper)** · [GitHub](https://github.com/smoldesk/wechat-articles-scraper)

### YouTube Scraper

Scrape YouTube without an API key or quota. Search results, channel videos, Shorts, live streams, playlists and comments, with exact view and like counts, publish date, tags, chapters and subscriber counts. Output is flat, so it opens cleanly in a spreadsheet.

$1 per 1,000 videos or channels, $0.50 per 1,000 comments.

**[Open YouTube Scraper on Apify](https://apify.com/smoldesk/youtube-scraper)** · [GitHub](https://github.com/smoldesk/youtube-scraper)

### Bilibili Scraper

Scrape Bilibili (哔哩哔哩) without logging in: video search, full video stats, comments and replies, danmaku (bullet comments), creator profiles and the trending charts. Has a monitor mode that only returns what is new since the last run.

$2.50 per 1,000 videos, $2 per 1,000 creators, $0.50 per 1,000 comments, $0.10 per 1,000 danmaku.

**[Open Bilibili Scraper on Apify](https://apify.com/smoldesk/bilibili-scraper)** · [GitHub](https://github.com/smoldesk/bilibili-scraper)

### Telegram Channel Scraper

Scrape public Telegram channels without a login or Telegram API keys. Messages with views, reactions, media, links and forwards, plus channel info and subscriber counts. Filter by keyword and date.

$1 per 1,000 messages, $2 per 1,000 channels.

**[Open Telegram Channel Scraper on Apify](https://apify.com/smoldesk/telegram-channel-scraper)** · [GitHub](https://github.com/smoldesk/telegram-channel-scraper)

### Substack Scraper

Scrape Substack newsletters: subscriber counts, paid tiers and prices, author socials, and posts with likes, comments and full text. Find newsletters by category.

$3 per 1,000 newsletters, $1 per 1,000 posts.

**[Open Substack Scraper on Apify](https://apify.com/smoldesk/substack-scraper)** · [GitHub](https://github.com/smoldesk/substack-scraper)

## Marketing and SEO

### Google Trends Scraper

Google Trends data over plain HTTP, no browser. Interest over time, interest by region and city, related and rising queries, side-by-side comparison of up to 5 terms, and Trending now with search volume and news links.

$1.50 per 1,000 results, $0.50 per 1,000 trending searches.

**[Open Google Trends Scraper on Apify](https://apify.com/smoldesk/google-trends-scraper)** · [GitHub](https://github.com/smoldesk/google-trends-scraper)

### Google Ads Transparency Scraper

See every ad a competitor runs on Google Search, YouTube, Shopping, Maps and Play, from the Google Ads Transparency Center. Ad image, video, text and landing page when Google shows them, the countries each ad runs in, EU impressions, audience targeting and political ad spend. Can alert you to new ads.

$1 per 1,000 ads, plus $2 per 1,000 for full ad details.

**[Open Google Ads Transparency Scraper on Apify](https://apify.com/smoldesk/google-ads-transparency-scraper)** · [GitHub](https://github.com/smoldesk/google-ads-transparency-scraper)

### Shopify Store Analyzer

Look inside any Shopify store: installed apps, theme, contact emails and phones, social links, location, product count and price range. Can also export every product with images, descriptions and variants, plus a CSV you can import straight into another Shopify store.

$5 per 1,000 stores, $0.50 per 1,000 products.

**[Open Shopify Store Analyzer on Apify](https://apify.com/smoldesk/shopify-store-analyzer)** · [GitHub](https://github.com/smoldesk/shopify-store-analyzer)

## Travel

### Google Hotels Scraper

Hotel prices from Google Hotels for any city: nightly and total prices for your dates in any currency, taxes, star class, ratings with review breakdowns, GPS, photos, and the prices Google lists for each booking site (Expedia, Booking.com, Hotels.com and others).

$2.50 per 1,000 hotels, plus $2 per 1,000 for booking-site prices.

**[Open Google Hotels Scraper on Apify](https://apify.com/smoldesk/google-hotels-scraper)** · [GitHub](https://github.com/smoldesk/google-hotels-scraper)

### Google Hotels Price Calendar

The cheapest nightly rate for every check-in date, up to a year ahead, for any hotel on Google Hotels. One row per date with price per night, stay total, taxes and fees, weekday and a cheapest-date flag. Choose stay length (1 to 28 nights), guests and currency, and optionally add the prices each booking site lists for every date.

$1 per 1,000 dates, plus $1.50 per 1,000 for booking-site prices. A full year for one hotel costs about $0.37.

**[Open Google Hotels Price Calendar on Apify](https://apify.com/smoldesk/google-hotel-price-calendar)** · [GitHub](https://github.com/smoldesk/google-hotel-price-calendar)

## Jobs

### SEEK, JobStreet & JobsDB Scraper

One scraper for SEEK (Australia, New Zealand), JobStreet (Malaysia, Singapore, Philippines, Indonesia) and JobsDB (Hong Kong, Thailand). Salaries are normalised to min, max and period. Includes full job descriptions, a remote filter and a mode that returns only jobs posted since the last run.

$0.80 per 1,000 jobs, plus $0.40 per 1,000 for full descriptions.

**[Open SEEK, JobStreet & JobsDB Scraper on Apify](https://apify.com/smoldesk/seek-jobs-scraper)** · [GitHub](https://github.com/smoldesk/seek-jobs-scraper)

### Career Site Jobs Scraper

Search live jobs from more than 12,000 company career sites on Greenhouse, Lever, Ashby and Workday by title, location, remote and seniority. Or point it at any company on 8 applicant tracking systems. Salary ranges, descriptions in Markdown, and a new-jobs mode that also tells you which jobs closed.

$2 per 1,000 jobs.

**[Open Career Site Jobs Scraper on Apify](https://apify.com/smoldesk/career-site-jobs-scraper)** · [GitHub](https://github.com/smoldesk/career-site-jobs-scraper)

## Sports

### Tennis Scraper

Tennis results, fixtures and betting odds from TennisExplorer. Set scores, opening and closing odds from 15 bookmakers, head-to-head records, player stats and ATP/WTA rankings. Covers ATP, WTA, Challenger and ITF.

$2 per 1,000 matches (plus $3 per 1,000 for odds and H2H), $3 per 1,000 players, $0.50 per 1,000 ranking rows.

**[Open Tennis Scraper on Apify](https://apify.com/smoldesk/tennis-scraper)** · [GitHub](https://github.com/smoldesk/tennis-scraper)

## Running a scraper from code

Each scraper can be called through the Apify API. Get a token from [Apify Console](https://console.apify.com/settings/integrations) and run, for example:

```bash
curl -X POST "https://api.apify.com/v2/acts/smoldesk~weibo-scraper/run-sync-get-dataset-items?token=YOUR_TOKEN" \
  -H "Content-Type: application/json" \
  -d '{"searchQueries": ["iPhone 17"], "maxPostsPerSearch": 50}'
```

Or in Python with `pip install apify-client`:

```python
from apify_client import ApifyClient

client = ApifyClient("YOUR_TOKEN")
run = client.actor("smoldesk/youtube-scraper").call(run_input={"searchQueries": ["lofi beats"], "maxResults": 50})
for item in client.dataset(run["defaultDatasetId"]).iterate_items():
    print(item)
```

The input fields for each scraper are listed on its Input tab on Apify.

## Bugs and requests

Open an issue on the scraper's Issues tab on Apify. That's where fixes are tracked.
