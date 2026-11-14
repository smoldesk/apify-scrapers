# Apify Scrapers by Smoldesk Studios

Scrapers for public data that needs no login, cookies or API key. Every one of them runs on the [Apify Store](https://apify.com/smoldesk). You pay per result with no monthly fee. Export to JSON, CSV or Excel, or call them from the Apify API, Make, Zapier, n8n or an AI agent over MCP.

This repo is the catalog. The scrapers run on Apify, so there's no code to install here.

| Scraper | What it gets | Price |
|---|---|---|
| [Weibo Scraper](#weibo-scraper) | Posts, comments, profiles, hot search | $8 / 1,000 posts |
| [Toutiao Scraper](#toutiao-scraper) | News and 微头条 post search, comments, hot board | $2 / 1,000 articles |
| [WeChat Articles Scraper](#wechat-articles-scraper) | Official Account articles, full text, images | $8 / 1,000 articles |
| [YouTube Scraper](#youtube-scraper) | Videos, Shorts, channels, comments | $1 / 1,000 videos |
| [YouTube Comments Scraper](#youtube-comments-scraper) | Comments and replies from videos, channels, searches | $1.20 / 1,000 comments |
| [YouTube Channel Scraper](#youtube-channel-scraper) | Channel profiles, social links, latest videos | $1 / 1,000 results |
| [Bilibili Scraper](#bilibili-scraper) | Videos, comments, danmaku, creators | $2.50 / 1,000 videos |
| [Telegram Channel Scraper](#telegram-channel-scraper) | Channel messages, views, reactions | $1 / 1,000 messages |
| [Substack Scraper](#substack-scraper) | Newsletters, subscriber counts, posts | $3 / 1,000 newsletters |
| [Google Trends Scraper](#google-trends-scraper) | Interest over time, regions, related queries | $1.50 / 1,000 results |
| [Google Ads Transparency Scraper](#google-ads-transparency-scraper) | Competitor ads, countries, reach | $1 / 1,000 ads |
| [Google Hotels Scraper](#google-hotels-scraper) | Hotel prices, ratings, booking sites | $2.50 / 1,000 hotels |
| [Google Hotels Price Calendar](#google-hotels-price-calendar) | Cheapest rate per check-in date, a year ahead | $1 / 1,000 dates |
| [Airbnb Scraper](#airbnb-scraper) | Listings, prices for your dates, reviews, availability calendar | $2 / 1,000 listings |
| [Shopify Store Analyzer](#shopify-store-analyzer) | Store apps, theme, contacts, products | $5 / 1,000 stores |
| [SEEK, JobStreet & JobsDB Scraper](#seek-jobstreet--jobsdb-scraper) | Jobs and salaries in APAC | $0.80 / 1,000 jobs |
| [Career Site & Remote Jobs Scraper](#career-site-jobs-scraper) | Jobs from Greenhouse, Lever, Workday and more, remote jobs by country | $2 / 1,000 jobs |
| [Tennis Scraper](#tennis-scraper) | Results, odds, H2H, ATP/WTA rankings | $2.50 / 1,000 matches |
| [Google Maps Scraper](#google-maps-scraper) | Places, phones, websites, emails, socials | $2 / 1,000 places |
| [Contact Details Scraper](#contact-details-scraper) | Emails, phones, socials, contact forms from websites | $3 / 1,000 websites with contacts |
| [Websiteless](#websiteless) | Google Maps businesses with no website, a Facebook-only page or a broken site, scored | $5 / 1,000 leads |

## Social media

### Weibo Scraper

Scrape Weibo (新浪微博) without logging in. Search any keyword or #hashtag within a date range, pull full post text, likes, comments and reposts, comment and reply threads, user profiles and the hot-search board (热搜) with heat values. Mix keywords, post links, profiles and trending in one run and duplicates are dropped. Goes past Weibo's 650-post search limit on its own, adds English region names, an ad flag and optional approximate sentiment. Built for brand monitoring, social listening and China market research: schedule it with **Only new posts** to get just the new mentions of your brand.

$8 per 1,000 posts or profiles, $1 per 1,000 comments or hot-search topics. Lower on paid Apify plans.

**[Open Weibo Scraper on Apify](https://apify.com/smoldesk/weibo-scraper)** · [GitHub](https://github.com/smoldesk/weibo-scraper)

### Toutiao Scraper

Scrape Toutiao (今日头条), China's biggest news app, without logging in. Search any keyword within a date range and get articles and videos with reads, plays, likes, comments and shares, 微头条 short posts with full text, images and hashtags, the comment and reply threads, and the hot board (热榜) with heat scores. Has a monitor mode that only returns new articles.

$2 per 1,000 articles or videos, $1 per 1,000 comments or hot-board topics. Lower on paid Apify plans.

**[Open Toutiao Scraper on Apify](https://apify.com/smoldesk/toutiao-scraper)** · [GitHub](https://github.com/smoldesk/toutiao-scraper)

### WeChat Articles Scraper

Scrape WeChat Official Account (微信公众号) articles without a WeChat account or login. Search any keyword through Sogou WeChat search and get each article's full text as Markdown and plain text, images, publish time, account name and ID, author, the original/repost flag and IP location. Paste article links to get their full text, or schedule it with **Only new articles** to monitor a brand.

$8 per 1,000 articles with full text, $2 per 1,000 search cards. Lower on paid Apify plans.

**[Open WeChat Articles Scraper on Apify](https://apify.com/smoldesk/wechat-articles-scraper)** · [GitHub](https://github.com/smoldesk/wechat-articles-scraper)

### YouTube Scraper

Scrape YouTube without an API key or quota. Search results, channel videos, Shorts, live streams, playlists and comments, with exact view and like counts, publish date, tags, chapters and subscriber counts. Output is flat, so it opens cleanly in a spreadsheet.

$1 per 1,000 videos or channels, $0.50 per 1,000 comments. Lower on paid Apify plans.

**[Open YouTube Scraper on Apify](https://apify.com/smoldesk/youtube-scraper)** · [GitHub](https://github.com/smoldesk/youtube-scraper)

### YouTube Comments Scraper

Comments and replies from YouTube video URLs, a channel's latest videos, playlists or the top videos for a keyword. Full text, author, likes, reply count, pinned and hearted flags, and the input each comment came from. You pay only for comments; opening the videos is free.

$1.20 per 1,000 comments on the Apify Free plan, down to $0.60 on Business.

**[Open YouTube Comments Scraper on Apify](https://apify.com/smoldesk/youtube-comments-scraper)** · [GitHub](https://github.com/smoldesk/youtube-comments-scraper)

### YouTube Channel Scraper

Channel profiles from URLs or `@handles`: subscribers, exact total views, video count, join date, country, description and social links, plus the latest videos, Shorts and live streams with exact views and likes. Leave the tabs empty for profiles only.

$1 per 1,000 profiles or videos on the Apify Free plan, down to $0.40 on Business.

**[Open YouTube Channel Scraper on Apify](https://apify.com/smoldesk/youtube-channel-scraper)** · [GitHub](https://github.com/smoldesk/youtube-channel-scraper)

### Bilibili Scraper

Scrape Bilibili (哔哩哔哩) without logging in: video search (English brand names also searched in Chinese), full video stats with engagement rate, comments and replies, danmaku (bullet comments) with a per-video danmaku profile, built-in Chinese sentiment, creator profiles and the trending charts. Has a monitor mode that only returns what is new since the last run, plus follow-up comments.

$2.50 per 1,000 videos, $2 per 1,000 creators, $0.50 per 1,000 comments, $0.10 per 1,000 danmaku. Lower on paid Apify plans.

**[Open Bilibili Scraper on Apify](https://apify.com/smoldesk/bilibili-scraper)** · [GitHub](https://github.com/smoldesk/bilibili-scraper)

### Telegram Channel Scraper

Scrape public Telegram channels without a login or Telegram API keys. Messages with views, reactions, media, links and forwards, public comments, emails and @mentions, plus channel info and subscriber counts. Filter by keyword, date, message type and views, and get only new messages on each scheduled run.

$1 per 1,000 messages, $2 per 1,000 channels, $0.50 per 1,000 comments. Lower on paid Apify plans.

**[Open Telegram Channel Scraper on Apify](https://apify.com/smoldesk/telegram-channel-scraper)** · [GitHub](https://github.com/smoldesk/telegram-channel-scraper)

### Substack Scraper

Scrape Substack newsletters: subscriber counts and growth, paid tiers and prices, author socials and contact emails, posts with likes and full text, comment threads, Notes and keyword search across Substack. Find newsletters by category or keyword.

$3 per 1,000 newsletters, $1 per 1,000 posts, $0.50 per 1,000 comments from 26 Nov 2026 (free until then). Lower on paid Apify plans.

**[Open Substack Scraper on Apify](https://apify.com/smoldesk/substack-scraper)** · [GitHub](https://github.com/smoldesk/substack-scraper)

## Marketing and SEO

### Google Trends Scraper

Google Trends data over plain HTTP, no browser. Interest over time, interest by region and city, related and rising queries, side-by-side comparison of up to 5 terms, and Trending now with search volume and news links.

$1.50 per 1,000 results, $0.50 per 1,000 trending searches. Lower on paid Apify plans.

**[Open Google Trends Scraper on Apify](https://apify.com/smoldesk/google-trends-scraper)** · [GitHub](https://github.com/smoldesk/google-trends-scraper)

### Google Ads Transparency Scraper

See every ad a competitor runs on Google Search, YouTube, Shopping, Maps and Play, from the Google Ads Transparency Center. Ad image, video, text and landing page when Google shows them, the countries each ad runs in, EU impressions, audience targeting and political ad spend. Can alert you to new ads.

$1 per 1,000 ads, plus $2 per 1,000 for full ad details. Lower on paid Apify plans.

**[Open Google Ads Transparency Scraper on Apify](https://apify.com/smoldesk/google-ads-transparency-scraper)** · [GitHub](https://github.com/smoldesk/google-ads-transparency-scraper)

### Shopify Store Analyzer

Look inside any Shopify store: installed apps, theme, contact emails and phones, social links, location, product count and price range. Can also export every product with images, descriptions and variants, plus a CSV you can import straight into another Shopify store.

$5 per 1,000 stores, $0.50 per 1,000 products. Lower on paid Apify plans.

**[Open Shopify Store Analyzer on Apify](https://apify.com/smoldesk/shopify-store-analyzer)** · [GitHub](https://github.com/smoldesk/shopify-store-analyzer)

## Travel

### Google Hotels Scraper

Hotel prices from Google Hotels for any city: nightly and total prices for your dates in any currency, taxes, star class, ratings with review breakdowns, GPS, photos, and the prices Google lists for each booking site (Expedia, Booking.com, Hotels.com and others).

$2.50 per 1,000 hotels, plus $2 per 1,000 for booking-site prices. Lower on paid Apify plans.

**[Open Google Hotels Scraper on Apify](https://apify.com/smoldesk/google-hotels-scraper)** · [GitHub](https://github.com/smoldesk/google-hotels-scraper)

### Google Hotels Price Calendar

The cheapest nightly rate for every check-in date, up to a year ahead, for any hotel on Google Hotels. One row per date with price per night, stay total, taxes and fees, weekday and a cheapest-date flag. Choose stay length (1 to 28 nights), guests and currency, and optionally add the prices each booking site lists for every date.

$1 per 1,000 dates, plus $1.50 per 1,000 for booking-site prices. A full year for one hotel costs about $0.37. Lower on paid Apify plans.

**[Open Google Hotels Price Calendar on Apify](https://apify.com/smoldesk/google-hotel-price-calendar)** · [GitHub](https://github.com/smoldesk/google-hotel-price-calendar)

### Airbnb Scraper

Airbnb listings for any city (whole cities, split across the map past Airbnb's ~270 limit), neighborhood, list of listing URLs or host profile (all their listings): the price for your dates (total, per night, discounts and fees), rating, coordinates and photos, plus full details (amenities, house rules, host profile, six category ratings, sleeping arrangements). Optional guest reviews with translations and the 12-month availability calendar with booked share.

$2 per 1,000 listings, plus $2 per 1,000 for full details, $2 per 1,000 reviews and $4 per 1,000 calendars. Lower on paid Apify plans.

**[Open Airbnb Scraper on Apify](https://apify.com/smoldesk/airbnb-scraper)** · [GitHub](https://github.com/smoldesk/airbnb-scraper)

## Jobs

### SEEK, JobStreet & JobsDB Scraper

One scraper for SEEK (Australia, New Zealand), JobStreet (Malaysia, Singapore, Philippines, Indonesia) and JobsDB (Hong Kong, Thailand). Salaries are normalised to min, max and period. Includes full job descriptions, a remote filter and a mode that returns only jobs posted since the last run.

$0.80 per 1,000 jobs, plus $0.40 per 1,000 for full descriptions.

**[Open SEEK, JobStreet & JobsDB Scraper on Apify](https://apify.com/smoldesk/seek-jobs-scraper)** · [GitHub](https://github.com/smoldesk/seek-jobs-scraper)

### Career Site Jobs Scraper

Search live jobs from more than 12,000 company career sites on Greenhouse, Lever, Ashby and Workday by title, location, remote and seniority. Or point it at any company on 8 applicant tracking systems. Salary ranges, descriptions in Markdown, and a new-jobs mode that also tells you which jobs closed. Remote jobs can be filtered by the country you work from, with visa sponsorship and salary in USD.

$2 per 1,000 jobs.

**[Open Career Site Jobs Scraper on Apify](https://apify.com/smoldesk/career-site-jobs-scraper)** · [GitHub](https://github.com/smoldesk/career-site-jobs-scraper)

## Sports

### Tennis Scraper

Tennis results, fixtures and betting odds from TennisExplorer. Set scores, opening and closing odds from 15 bookmakers, head-to-head records, player stats and ATP/WTA rankings. Covers ATP, WTA, Challenger and ITF.

$2.50 per 1,000 matches (plus $3.50 per 1,000 for odds and H2H), $3.50 per 1,000 players, $0.60 per 1,000 ranking rows on the Free plan; lower on paid Apify plans (down to $1.40 per 1,000 matches).

**[Open Tennis Scraper on Apify](https://apify.com/smoldesk/tennis-scraper)** · [GitHub](https://github.com/smoldesk/tennis-scraper)

## Lead generation

### Google Maps Scraper

Google Maps places for any search and location: name, categories, address, phone, website, rating, review count, opening hours and coordinates. Optionally visits each business website for emails and social profiles (charged only when found). Lead filters for rating, reviews, phone and businesses without a website, a grid split to go past Google's ~120 places per search, and an only-new-places mode for monitoring.

$2 per 1,000 places, plus $2 per 1,000 for contact details when an email or social profile is found. Lower on paid Apify plans.

**[Open Google Maps Scraper on Apify](https://apify.com/smoldesk/google-maps-scraper)** · [GitHub](https://github.com/smoldesk/google-maps-scraper)

### Contact Details Scraper

Emails, phone numbers, social profiles (Facebook, Instagram, LinkedIn, X, TikTok, YouTube, WhatsApp) and contact forms from any list of websites, or from the websites in another dataset such as a Google Maps Scraper run. Reads the homepage plus contact, about, team and legal pages, checks each email's domain for a mail server and drops junk emails and website-builder social accounts.

$3 per 1,000 websites with contacts found; websites with nothing found are free. Lower on paid Apify plans.

**[Open Contact Details Scraper on Apify](https://apify.com/smoldesk/contact-details-scraper)** · [GitHub](https://github.com/smoldesk/contact-details-scraper)

### Websiteless

Google Maps leads for web designers and agencies: local businesses with no website, only a Facebook or Instagram page, only a directory or booking listing, or (if you choose) a dead, parked or outdated site. Each lead has a 0 to 100 lead score, plain-English reasons to pitch, phone, rating, reviews and Google profile gaps. Chains, duplicates and businesses with a working website are skipped for free.

$5 per 1,000 leads, plus $2 per 1,000 for contact details when an email or social profile is found. Lower on paid Apify plans.

**[Open Websiteless on Apify](https://apify.com/smoldesk/websiteless-leads)** · [GitHub](https://github.com/smoldesk/websiteless-leads)

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

## Use all of them in your AI agent

The Apify MCP server can expose every scraper here as a tool. Add this URL to Claude Desktop, Claude Code, Cursor or VS Code (you sign in to Apify in the browser on first use, or send your API token as an `Authorization: Bearer <APIFY_TOKEN>` header):

```json
{
  "mcpServers": {
    "smoldesk": {
      "url": "https://mcp.apify.com?tools=smoldesk/airbnb-scraper,smoldesk/career-site-jobs-scraper,smoldesk/bilibili-scraper,smoldesk/contact-details-scraper,smoldesk/google-ads-transparency-scraper,smoldesk/google-hotel-price-calendar,smoldesk/google-hotels-scraper,smoldesk/google-maps-scraper,smoldesk/google-trends-scraper,smoldesk/seek-jobs-scraper,smoldesk/shopify-store-analyzer,smoldesk/substack-scraper,smoldesk/telegram-channel-scraper,smoldesk/tennis-scraper,smoldesk/toutiao-scraper,smoldesk/wechat-articles-scraper,smoldesk/weibo-scraper,smoldesk/youtube-channel-scraper,smoldesk/youtube-comments-scraper,smoldesk/youtube-scraper"
    }
  }
}
```

Or let the Apify CLI write the config: `apify mcp install cursor --tools smoldesk/airbnb-scraper,smoldesk/career-site-jobs-scraper,smoldesk/bilibili-scraper,smoldesk/contact-details-scraper,smoldesk/google-ads-transparency-scraper,smoldesk/google-hotel-price-calendar,smoldesk/google-hotels-scraper,smoldesk/google-maps-scraper,smoldesk/google-trends-scraper,smoldesk/seek-jobs-scraper,smoldesk/shopify-store-analyzer,smoldesk/substack-scraper,smoldesk/telegram-channel-scraper,smoldesk/tennis-scraper,smoldesk/toutiao-scraper,smoldesk/wechat-articles-scraper,smoldesk/weibo-scraper,smoldesk/youtube-channel-scraper,smoldesk/youtube-comments-scraper,smoldesk/youtube-scraper` (also `claude-code`, `vscode`, `codex`). Each run is billed per result, same as on the Store.

## Bugs and requests

Open an issue on the scraper's Issues tab on Apify. That's where fixes are tracked.
