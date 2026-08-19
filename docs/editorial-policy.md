# Editorial policy

The rules this repository is built and maintained by. The README's
"How tools are selected" section is the short version; this is the full one.

## Scope

AI tools that a person can use to finish real work without paying. Scope is decided by the pricing model, not by what the tool does, which is why the categories here span assistants, coding, images, and local inference rather than one domain.

This is the pricing-filtered list in the TiorAI portfolio. `awesome-ai-tools` covers the general landscape regardless of cost; this repository only lists what is usable free, and describes the free offering rather than the product as a whole.

## What qualifies

- There is a free tier you can actually finish a piece of work on, not a demo.
- Signing up does not require a credit card, and the free tier does not expire.
- The free offering is current, checked against the vendor's own pricing page.
- There is enough public information to describe it accurately.
- It covers something the entries already in that category do not.

## What does not

- Products whose only free offering is a time-limited or credit-limited trial.
- Products that require a credit card before you can use the free tier.
- Waiting lists, closed betas, and "request a demo" gates.
- Source-available products presented as open source.
- Broken, parked, or login-walled sites with no public information.
- Products that have shut down or been folded into something else.
- Affiliate landing pages, coupon sites, and lead-capture funnels.
- Near-identical clones with no meaningful difference from something already listed.
- Anything whose main activity is clearly illegal, and NSFW-focused products.
- Anything submitted purely as a promotional exercise.

## Descriptions

One sentence, 8 to 25 words, 35 at the absolute maximum, ending in a full stop. Written for
this repository rather than adapted from a vendor's homepage, and rewritten if a neighbouring
entry could swap places with it unnoticed.

Banned outright: superlatives (*best*, *leading*, *revolutionary*, *cutting-edge*,
*game-changing*, *world-class*, *ultimate*, *powerful*, *seamless*, *unleash*), `AI-powered`
as an opening, unverifiable claims about users, funding, or awards, and the em dash inside a
description, which is reserved as the entry separator so the format stays machine-parseable.

## Metadata vocabularies

Closed sets. A term outside them is a defect, not a judgement call.

**Pricing** — at least one, at most two, in this order:
`Free` · `Freemium` · `Paid` · `Open Source` · `Free Trial`

`Open Source` means an OSI-approved licence. Source-available products do not get the label;
the description says "source-available" instead. `Free Trial` never appears alone.

**Platform** — zero to six, in this order:
`Web` · `Windows` · `macOS` · `Linux` · `iOS` · `Android` · `API` · `CLI` ·
`Browser Extension` · `VS Code` · `JetBrains` · `Discord`

Applied only where verified. A wrong label is worse than a missing one.



## Ordering

Alphabetical within a category, ignoring punctuation and a leading "The". Position carries no
meaning and there is no paid placement.

Between categories, the order is editorial, by expected reader interest. That ranks topics,
never products.

## Categories

Minimum 4 entries, 8 is the working target, roughly 15 is the ceiling. A category that cannot
reach 8 strong entries is merged or dropped rather than padded. No subcategories.

The taxonomy is revisited when a category drops below 6 entries, passes 15, or starts
receiving the same submissions as its neighbour.

## Links

The primary link is the resource's own official site: canonical, HTTPS, no tracking
parameters, no affiliate parameters, no shortener, no directory listing, no review page.

TiorAI links are capped: at most 15% of entries carry one, all distinct, at most three per
category, maintainer-placed only. Contributors are asked not to add them.

## Removal

An entry is removed when the product shuts down, the domain is taken over or starts serving
something harmful, the listing turns out to be misleading, or the entry no longer meets the
scope above. Removals are recorded in [CHANGELOG.md](../CHANGELOG.md). An entry removed for
a safety reason goes through review again rather than being quietly restored.
