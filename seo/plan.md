# Chloe's weekly SEO plan

Goal: Ohio homeowners searching about mortgage protection, living benefits and final expense coverage find Matt's articles, then request a call on `ohio.html`.

Approved by Matt 2026-10-23. One article per weekly run. Quality over volume.

## Rules every article follows

- Answers one real question a homeowner would type into Google. Put the plain answer in the "Short answer" box at the top.
- 700–1,200 words, written by Matt in first person, 8th-grade reading level, sentence case headings.
- Accurate and general. If unsure of a fact, leave it out. No invented statistics, quotes, testimonials or case stories.
- No prices, rates, earnings or guarantees. No "best", "cheapest" or "#1" claims. Never say coverage is guaranteed or that no exam is guaranteed.
- Always note that coverage, riders, prices and eligibility vary by carrier, product, age, health and state.
- Not legal or tax advice; say so on topics that touch estates, probate or taxes.
- No doorway pages: never publish near-copies that only swap a city name. A local article must contain content that is actually specific to that place.
- Ohio focus. Never mention other states as service areas.
- Every article: same layout as `learn/mortgage-protection-vs-pmi.html` (shared `learn.css`), canonical URL, Open Graph tags, Article + FAQPage structured data (2–4 questions answered in the article), a call-to-action to `../ohio.html`, and links to 2–3 related articles.

## Each run

1. Take the first topic below marked `[ ]`. If it would duplicate an existing article, skip it and note why.
2. Write `learn/<slug>.html`.
3. Add it to: `learn/index.html` (ARTICLE-LIST), `ohio.html` (OHIO-LEARN-LINKS, newest 5 only), `sitemap.xml`, and the MORE-ARTICLES block of 2–3 related existing articles.
4. Validate: structured data is valid JSON, sitemap is valid XML, every internal link resolves to a file.
5. Mark the topic `[x]` with the date and file name, and add a line to the log.
6. Open a pull request titled `SEO: <article title>`. Matt merges it.

## Topic queue

- [x] Mortgage protection insurance vs. PMI (2026-10-23, learn/mortgage-protection-vs-pmi.html)
- [x] What are living benefits on life insurance? Critical, chronic and terminal illness explained (2026-10-27, learn/living-benefits-life-insurance.html)
- [ ] How much life insurance do I need to cover my mortgage?
- [ ] Do I need a medical exam to get life insurance?
- [ ] Term life vs. mortgage protection: is there a difference?
- [ ] Is the mortgage life insurance my lender offers worth it?
- [ ] What happens to my mortgage if I die? (Ohio homeowners, general info)
- [ ] Final expense insurance in Ohio: what it covers and who it's for
- [ ] Return of premium term life insurance, explained
- [ ] Life insurance for Ohio homeowners with high blood pressure or diabetes
- [ ] Life insurance for self-employed homeowners
- [ ] Does life insurance through work cover my mortgage?
- [ ] Mortgage protection for Medina County homeowners (must include genuinely local content)
- [ ] How to compare life insurance quotes without getting flooded with calls

When fewer than 4 topics remain, add new ones based on the questions homeowners ask most, and note them in the log.

## Log

- 2026-10-23: Foundation added (canonical, Open Graph, InsuranceAgency data, sitemap, article section). First article published.
- 2026-10-27: Published learn/living-benefits-life-insurance.html. Cross-linked with the PMI article; added to learn index, ohio.html and sitemap.
