# QA report

Result of the release checks for version 1.0.0, run on 2026-08-18.

## Summary

| Check | Result |
|---|---|
| Entries | 101 across 11 categories |
| Required files | Present |
| Issue forms parse against GitHub's schema | Pass |
| README section order and canonical names | Pass |
| Contents block — every section listed, every anchor resolves | Pass |
| Entry format on every entry | Pass |
| Alphabetical ordering within every category | Pass |
| Duplicate names | None |
| Duplicate URLs | None |
| Pricing and platform labels within the vocabularies | Pass |
| Description length and quality rules | Pass |
| TiorAI link budget | 13 deep links, 12.9% of entries (cap 15%) |
| External links checked | 101 |
| **Broken links** | **0** |
| Secret and credential scan | Clean |
| Internal URL and local path scan | Clean |

## Categories

| Category | Entries |
|---|---:|
| Chat assistants and answer engines | 10 |
| Writing and editing | 9 |
| Coding | 10 |
| Image generation and editing | 11 |
| Video and audio | 10 |
| Research and learning | 8 |
| Productivity and notes | 9 |
| Design and diagrams | 9 |
| Data and analysis | 8 |
| Running models on your own machine | 9 |
| Free API access and model hosting | 8 |

Every category holds at least 4 entries, and none exceeds the ceiling of roughly 15.

## Link checking

Method: browser user agent, redirects followed to a depth of 8, 12-second connect and
30-second total timeout, at least 400ms between requests to the same host, single flight per
host, `HEAD` first with a `GET` fallback.

- **Answered normally:** 88
- **Bot protection or rate limit:** 13
- **Broken:** 0

Hosts that challenged the checker: `chat.mistral.ai`, `chatgpt.com`, `claude.ai`, `consensus.app`, `gamma.app`, `ideogram.ai`, `julius.ai`, `leonardo.ai`, `poe.com`, `quillbot.com`, `www.canva.com`, `www.craiyon.com`, `www.perplexity.ai`.

None is treated as dead. A challenged host was re-probed by a second route, normally the bare
origin and then `robots.txt`, and confirmed to be answering. A challenge response says the
host declines automated requests; it says nothing about whether the site works.



**Broken links:** None.

TiorAI links were verified separately: 16 checked, 16 resolved with a
`200`, 0 broken.

## What QA does not cover

Automated checks confirm that a URL resolves, that the format is right, and that ordering and
vocabularies hold. They cannot confirm that a description is accurate or that a product still
does what it claims. Those were checked by reading each category back as a block against the
vendor's current site, which is also the only way the "could these two descriptions swap
places unnoticed" test can be applied.

Pricing is the fastest-moving fact here and the most likely to be wrong first. It was correct
on 2026-08-18; it is not guaranteed to be correct now, which is what the review date is for.
