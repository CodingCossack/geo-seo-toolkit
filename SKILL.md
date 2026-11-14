---
name: geo-seo-toolkit
description: >-
  Diagnose, improve and verify SEO and AI-search visibility for real sites.
  Use for indexing, crawling, canonicals, redirects, sitemaps, rendering,
  structured data, programmatic pages, site migrations, crawler controls
  and search-performance diagnosis. Excludes generic marketing copy and outreach.
---

# SEO and AI search

## Scope and diagnosis

Establish the target host, URL class, intended behaviour and authorised outcome.
Confirm that the repository or connected property owns the target. When using
local code to explain public behaviour, identify its relationship to the deployed
revision and data.

Reproduce the symptom with the relevant host, path, protocol, method, user agent
or account property. For a previously fixed symptom, inspect the prior fix and
its closing evidence before repeating it.

Trace only the relevant layers:

`source or URL owner → generated output → commit → deployment and data → CDN/WAF/cache → crawler → engine record → measured outcome`

Locate the first divergence and the layer producing it. Edge rules and platform
normalisation may run before application code. Fix the existing owner and check
affected consumers; stop expanding the investigation once the mechanism explains
the symptom. Report conflicting states and anything still unexplained.

## Decision rules

- Keep URL identity consistent across redirects, canonicals, internal links,
  sitemaps, structured data and notifications where their contracts require it.
  Host, slash and encoding policies are project-specific.
- Base permanent aliases on semantic identity, not temporary content or
  result-set equality. Redirect only to a relevant, indexable equivalent.
- Preserve unknowns and source evidence. Never invent entity facts to fill
  visible content or schema. Keep historical attribution intact.
- Prioritise useful public HTML and crawlable links. Schema, bot routes and
  crawler-only files cannot substitute for page content.
- Do not assign composite SEO or GEO scores without a user-supplied calibrated
  model. Prioritise demonstrated blockage, breadth and user impact.
- Technical eligibility, submission, indexing, ranking, citation and conversion
  are separate outcomes. Traffic changes alone do not establish causality.

## Verification and completion

Use evidence that would fail if the cause remained; repeating a generated literal
or fixture is not independent verification.

For public changes, recheck the original failing request and the exact production
canonical URL without cache-busting parameters. Use GET, plus HEAD when redirects
or caching are involved. Identify the deployed revision and data generation when
available. A preview, build, commit, cache bypass, saved rule or accepted submission
proves only that state, not the public result.

Report the cause, owning layer, changes, evidence and material gaps. Claim a fix
only at the observed plane; if public or external verification is unavailable,
state that limit. Stop when the authorised outcome is proved or further progress
requires access, authority, a product decision or later engine evidence.

## References

Read only those needed by the task:

- [Public delivery](references/public-delivery.md): hosts, redirects, canonicals,
  robots, rendering, encoding, sitemaps, migrations and caches.
- [Content and entities](references/content-and-entities.md): page usefulness,
  factual authority, schema, local business, portfolios, images and backlinks.
- [Dynamic pages](references/dynamic-pages.md): programmatic routes, jobs,
  inventories, pagination, lifecycle and coverage.
- [Platform controls](references/platform-controls.md): AI-search consumers,
  crawler permissions, WAF controls, IndexNow and `llms.txt`.
- [Measurement and proof](references/measurement-and-proof.md): Search Console,
  analytics, outcome diagnosis and evidence selection.

Verify current first-party documentation when platform behaviour affects a decision.

## Authority

Diagnosis does not authorise edits, deployment, submissions, provider changes or
outreach. Implement only the authorised outcome and preserve unrelated state.
Indexability, consolidation, retirement and crawler policy are product decisions;
ask when a missing decision materially changes the result. Report incidental
findings without expanding the task.
