# Next Steps — Prioritized

Written 2026-08-08 after the site reached a solid baseline: 8 articles, all monetized, real product
photography, custom logo, luxury homepage redesign. This is what actually moves the needle from
here, roughly in priority order.

## 1. Get found — Google Search Console (do this first, costs nothing)

Right now the site has a sitemap.xml but nothing is telling Google to actually crawl it promptly.
Go to [search.google.com/search-console](https://search.google.com/search-console), add
`futuretechsweden.com` as a property (verify via the DNS TXT record method, same DNS panel in
Strato you've been using all night), then submit `https://futuretechsweden.com/sitemap.xml`.
Without this, Google finds new sites slowly — with it, indexing can happen in days instead of
weeks. This is the single highest-leverage 10-minute task available.

## 2. Post the TikTok videos that already exist

Four scripts are sitting unused in `marketing/`: two for article 1 & 2, one for wearables, one for
the buying guide. Scripts are the hard creative part — turning them into video is mechanical
(CapCut, ~20-30 min each per the walkthrough earlier). Traffic from social happens on a completely
different timescale than search (immediate vs. months), so this is the fastest way to get real
visitors before SEO kicks in.

## 3. Add privacy-friendly analytics

There's currently no way to know which articles get traffic, which affiliate links get clicked, or
whether anyone's finding the site at all. Recommend a lightweight, privacy-respecting option (no
cookie banner needed) like **Plausible** or **Simple Analytics** over Google Analytics — a few
dollars a month, one script tag, and it tells you what's actually working so future content
decisions aren't guesses.

## 4. Keep the content cadence going

The original 8-article queue is done. Next real ideas once ready for another content push:
- A seasonal/gift-guide angle when relevant (holidays, back-to-school)
- Deeper single-product "hands-on" review once you've actually ordered and tested something
  yourself — real hands-on content converts far better than research-only roundups, and now you
  have real Amazon/AliExpress accounts to actually buy through
- Revisit the still-thin Eilik affiliate coverage periodically — AliExpress seller enrollment
  changes over time

## 5. Professionalize a couple of loose ends when there's time

- Article 3 and 7 have a couple of items where the on-page brand name (RingConn, Kbao originally)
  doesn't exactly match the linked product due to affiliate enrollment gaps — noted in
  `product-links-to-monetize.md`, worth a look if you ever get time to hunt down exact-match
  alternatives.
- Amazon Associates account needs at least one qualifying sale within 180 days of signup
  (2026-08-07) or the application gets withdrawn — worth actively promoting the site well before
  early February 2027.
- Confirmed `og:image`/social share previews are working automatically (jekyll-seo-tag picks up
  the `image:` front matter on each post) — but the images are `.webp`, which has slightly patchy
  support on some link-preview crawlers (LinkedIn especially, historically). Low priority since
  major platforms (Facebook, X, Discord, Slack, iMessage) handle webp fine now — only worth
  converting to JPG if you ever notice a broken share preview somewhere specific.

## Not urgent, skip for now

- More technical/design polish — the site is in good shape; further gains here are marginal
  compared to traffic and content
- Trademark registration — only worth it once the brand has real traction (see earlier
  conversation about copyright vs. trademark)
