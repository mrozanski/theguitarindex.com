# Launch checklist.

Launching The Guitar Index with solid technical hygiene and AI-friendly signals is a good idea. Here’s a concise checklist you can follow.

## Access & governance files

- robots.txt  
  - Allow key crawlers: Googlebot, Bingbot, plus known AI bots like GPTBot, PerplexityBot, Claude bots, Google-Extended, etc.[1][2]
  - Disallow only truly private or irrelevant paths (admin, test, staging).  
  - Include sitemap location, for example:  
    - `Sitemap: https://theguitarindex.com/sitemap.xml`[3]

- sitemap.xml  
  - Generate an XML sitemap listing:  
    - Home (hub)  
    - Each claim/cluster page  
    - Each deep-dive article as you add them.[3][1]
  - Keep it auto-updated via your static site generator or CMS if possible.

- llms.txt  
  - Place at: `https://theguitarindex.com/llms.txt`.[4][5]
  - Use Markdown structure:  
    - H1 with site name.  
    - Short blockquote summarizing what the site is.  
    - A small set (10–20) of your highest-value URLs with 1–2 sentence descriptions.[6][7][8]
  - Focus on: hub page + core claim pages (provenance, auctions, etc.), not every post.  
  - Optionally note any paths you prefer LLMs not to use.

## Essential HTML meta & structure

On every important page (especially the hub and claim pages):

- `<title>`  
  - Descriptive, under ~60 characters, including your main concept.  
  - Example hub title: `The Guitar Index – Historic Guitars, Stories, and Provenance`.[9][1]

- `<meta name="description">`  
  - 1–2 sentence, human-readable summary mentioning audience and purpose.  
  - Example: `The Guitar Index is a high-signal guide to historic guitars, collections, and provenance for collectors, builders, and the guitar industry.`[1]

- Canonical tag  
  - `<link rel="canonical" href="https://theguitarindex.com/this-page-url/">` on each page, pointing to itself (or the canonical version if you ever cross-post).[3][1]

- Heading hierarchy  
  - One H1 per page; logical H2/H3 structure that mirrors topics and subtopics.[1]
  - Put concise answers / definitions right after important headings.

- Open Graph / Twitter meta (helps sharing + entities)  
  - `og:title`, `og:description`, `og:url`, `og:type`, and `og:image`.  
  - Similar `twitter:` tags if you care about social previews.

- Basic on-page signals  
  - Author identification (name and short bio) on key concept pages.[2]
  - “Last updated” date visible on claim pages and the hub.[10]
  - Internal links with descriptive anchor text (“guitar provenance”, “Jim Irsay collection auction”) rather than “click here”.

## Schema / structured data (nice-to-have, but strong)

- Organization / Website schema on the site  
  - Mark up The Guitar Index as an Organization or WebSite with name, URL, and (optionally) sameAs links to your other properties and profiles.[3][1]

- Person schema on your personal/author page  
  - Mark up yourself (on guitarhistorian.com or an “About Mariano” page) with Person schema, linking to The Guitar Index as a “knowsAbout” or related site.[2][1]

- Article schema on deep dives  
  - For long, single-topic claim pages: use Article (or BlogPosting) schema with headline, description, author, datePublished/dateModified, and mainEntityOfPage.[1][3]

## Indexing and analytics due diligence

- Search Console / indexing  
  - Add The Guitar Index to Google Search Console and Bing Webmaster Tools.[11][3]
  - Submit your sitemap.xml.  
  - After launch, manually “Inspect URL” on key pages to nudge indexing.

- Analytics  
  - Add a lightweight analytics solution (GA4, Plausible, Fathom, etc.).  
  - Track: page views on hub and claim pages, referrers from Substack, and time on page.

- AI visibility checks (ongoing)  
  - Periodically ask major assistants/engines questions like “What is The Guitar Index?” or “Where can I learn about guitar provenance?” and see if/when you start appearing.[10][9]
  - Adjust llms.txt and hub links over time to spotlight your best-performing pages.

If you’d like, next step can be a small llms.txt draft for theguitarindex.com listing the hub plus your first 3–5 claim pages with one-line descriptions.

[1](https://www.m8l.com/blog/llm-search-optimization-how-to-make-your-website-visible-to-ai)
[2](https://www.aleydasolis.com/en/ai-search/ai-search-optimization-checklist/)
[3](https://www.perfectsearchmedia.com/blog/ultimate-technical-seo-checklist)
[4](https://www.bluehost.com/blog/what-is-llms-txt/)
[5](https://www.semrush.com/blog/llms-txt/)
[6](https://www.level.agency/ai-seo-glossary/llms-txt-file/)
[7](https://www.rankability.com/guides/llms-txt-best-practices/)
[8](https://writesonic.com/blog/llm-txt-guide)
[9](https://backlinko.com/ai-optimization)
[10](https://www.averi.ai/learn/practical-roadmap-checklist-implement-llm-optimized-content)
[11](https://www.plerdy.com/seo-checklist/)
[12](file:///Users/marianorozanski/guitar-stack/Claim%20pages/html/landing.html)
[13](https://www.gitbook.com/blog/what-is-llms-txt)
[14](https://wolfpackadvising.com/blog/boost-ai-seo-2025-with-llms-txt-file/)
[15](https://www.firebrand.marketing/?p=46437)
[16](https://higoodie.com/blog/llms-txt-robots-txt-ai-optimization)
[17](https://totheweb.com/blog/beyond-seo-your-geo-checklist-mastering-content-creation-for-ai-search-engines/)
[18](https://www.youtube.com/watch?v=WMYP1Jhekcs)
[19](https://gitbook.com/docs/guides/seo-and-llm-optimization/geo-guide-how-to-optimize-your-docs-for-ai-search-and-llm-ingestion)
[20](https://www.mintlify.com/blog/the-value-of-llms-txt-hype-or-real)
[21](https://www.searchenginejournal.com/partner-resources/visibility-over-rankings-your-strategic-guide-checklist-for-llm-aio-optimization/)
[22](https://peec.ai/blog/llms-txt-md-files-important-ai-visibility-helper-or-hoax)