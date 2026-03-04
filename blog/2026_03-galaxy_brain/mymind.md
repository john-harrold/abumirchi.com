# mymind Auto-Generated Metadata

## 1. Content Type Classification
mymind categorizes every item into a type. The export shows 18 distinct types:
- **XPost** (489), **Article** (282), **WebPage** (207), **Post** (127), **Product** (89), **Image** (40), **Document** (18), **Embed** (13), **YouTubeVideo** (12), **Repository** (11), **RedditPost** (7), **BlueskyPost** (5), **Issue** (4), **WikipediaArticle** (2), **Note**, **Content**, **MusicRecording**, **TikTokPost** (1 each)

## 2. AI Visual Recognition Tags (computer vision)
For images and products, mymind runs **computer vision** to detect:
- **Objects**: `faucets`, `ring binder`, `bathtub`, `plant`, `drawer`
- **Colors**: `electric blue`, `magenta`, `violet`, `silver`, `monochrome`
- **Materials**: `metal`, `aluminium`, `titanium`, `brass`, `wood`
- **Design attributes**: `product design`, `graphic design`, `font`, `logo`, `brand`
- **Visual properties**: `flash photography`, `neon sign`, `atmospheric phenomenon`

These cards often have **10-46 tags** each. In the data, 286 cards have >10 tags (mostly auto-visual).

## 3. OCR (Optical Character Recognition)
mymind reads text within images — screenshots, memes, diagrams — and indexes that text so you can search for words appearing inside images.

## 4. Article Summaries
For web pages and articles, mymind generates a short paragraph summary of the content (this appears in the `content` field, though the export has very few populated).

## 5. Smart Card Extraction
For specific content types, it extracts structured metadata:
- **Books**: cover image, author, title
- **Products**: product image, brand, price info
- **Music**: artist, album info
- **Recipes**: specialized formatting

## 6. Color Search Index
Beyond tagging colors by name, mymind builds a **visual color index** so you can filter by hue (e.g., "show me all blue images").

## User Tags vs Auto Tags
In the data, the distinction is clear:
- **User tags** (<=5 per card, 672 cards): semantic/topical — `read later`, `Ukraine`, `rstats`, `cancel culture`, `new music`
- **Auto tags** (>10 per card, 286 cards): visual descriptors — `electric blue,technology,poster,magenta,art,font,display device,signage`

mymind shows these separately in its UI (labeled "auto-tags" vs user tags).

## What's in the Export
The CSV has 8 fields: `id, type, title, url, content, note, tags, created`. The auto-tags and user-tags are **mixed together** in the `tags` column with no way to distinguish them in the export. Only 13 cards have user notes, and only 2 have content populated.

### Field Population (1,310 cards)
| Field   | Populated |
|---------|-----------|
| Title   | 1,173     |
| URL     | 1,261     |
| Tags    | 1,135     |
| Note    | 13        |
| Content | 2         |

## Sources
- [How to use tagging in mymind](https://mymind.helpscoutdocs.com/article/51-how-to-use-tagging-in-mymind)
- [mymind - Comprehensive Guide (Skywork)](https://skywork.ai/skypage/en/mymind-Your-AI-Powered-Digital-Brain-%E2%80%93-A-Comprehensive-Guide-for-AI-Enthusiasts/1972840147367030784)
- [mymind - What is it?](https://mymind.com/what)
- [Building an extension of your mind with mymind (Ness Labs)](https://nesslabs.com/mymind-featured-tool)
