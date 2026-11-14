---
name: geo-seo-toolkit
description: >-
  Technical SEO and AI-search diagnosis for a real site: indexing, crawling,
  canonicals, redirects, sitemaps, rendering, structured data, programmatic
  pages, migrations, crawler and WAF controls, and Search Console diagnosis.
  Not for keyword choice, titles and headings, content strategy, backlinks,
  directories or marketing copy.
---

# Technical SEO and AI search

Search visibility is a chain. Find the first layer that breaks it, fix that
layer, and prove the result where users and crawlers see it.

`URL owner → generated output → deployed code and data → CDN/WAF/cache → crawler → engine record → measured outcome`

- Reproduce the symptom with the real host, path, method and user agent. Edge
  rules and platform normalisation can act before application code.
- Keep URL identity consistent across redirects, canonicals, internal links,
  sitemaps and structured data. Redirect only to a relevant, indexable
  equivalent.
- Useful public HTML and crawlable links come first. Schema, bot routes and
  crawler-only files can't substitute for page content. Never invent entity
  facts to fill schema.
- Eligibility, indexing, ranking, citation and traffic are separate outcomes;
  a traffic change alone doesn't prove cause. No composite SEO or GEO scores.
- Recheck the exact production URL without cache-busting, with GET (and HEAD
  for redirects or caching). A build, preview or accepted submission proves
  only that state.
- Indexability, consolidation, retirement and crawler policy are product
  decisions. Keyword, title and copy choices belong to the project's own
  briefs.

Read only the reference the task needs, and check current first-party docs
when platform behaviour decides the outcome:

- [Public delivery](references/public-delivery.md): hosts, redirects,
  canonicals, robots, rendering, encoding, sitemaps, migrations, caches.
- [Dynamic pages](references/dynamic-pages.md): programmatic routes, jobs,
  inventories, pagination, lifecycle, coverage.
- [Platform controls](references/platform-controls.md): AI-search crawlers,
  permissions, WAF, IndexNow, `llms.txt`.
- [Content and entities](references/content-and-entities.md): schema, local
  business and entity facts.
- [Measurement](references/measurement-and-proof.md): Search Console and
  analytics diagnosis.
