# Chapter 4 — Let the Crawler Finish the Job

The Thursday Packet site opened in a browser. It looked finished. The preview worked. The type was careful. A teammate sent the URL to their phone and nodded.

The crawler, when someone finally asked it to speak, received something else: a shell, a script tag, and a polite nothing where the explanation of name repair should have been. One staging header, copied forward in a hurry, still asked machines not to index the site. The sitemap existed, but it listed three old paths that now redirected twice and one path that returned a soft 200 with a “page not found” written in a stylish button. Robots.txt disallowed a folder that happened to contain the only guide worth retrieving.

The builder had already drafted twelve posts.

This is the cheapest tragedy in search, and it is almost always avoidable. **A URL you can open is not a URL a librarian can file.** People say “the site is live” when they mean “the browser I use, after the scripts I allowed, after the cookies I accepted, painted a picture.” A crawler may get one fetch, limited time, and a different idea of what counts as the document.

Chapter 2 asked you to name the stuck layer. This chapter is for the weeks when the stuck layer is crawl or index, and for the weeks when you thought it was rank and it was crawl all along.

---

## Seven Checks Before You Write the Next Twelve Posts

The handbook keeps a pre-launch list written for teams that ship with modern scaffolds — the kind where a platform URL works on the first try and search still cannot see a sentence. I am restating it as checks, not as a lucky number.

1. **Rendering.** Prefer HTML that already contains the text a stranger needs: server-rendered, pre-rendered, or a static output you can prove. If the product must be a client-rendered app, confirm — with a URL inspection or a fetch as the crawler — that the *received* document includes the headings and the explanation, not only a placeholder. A preview that appears after a second request is a product feature and an indexing risk.

2. **A sitemap that is actually reachable,** submitted to the webmaster tools you use. Submission is a hint, not a vow that every URL will be stored.

3. **robots.txt that does not block the documents you want retrieved.** Do not invent a clever Disallow and forget it. Do not confuse robots.txt with `noindex`. They are different instruments. One discourages fetching. The other, if seen, discourages storing.

4. **No leftover noindex on official pages.** Staging rules belong on staging. Management pages may stay out of the index on purpose. Your `/repair` page may not.

5. **Redirects and true not-found states.** Important moves should happen in one step when you can help it. A real missing page should be a real 404 or 410, not a cheerful 200 with a stylish empty state. Soft 404s waste crawl time and confuse everyone, including you.

6. **A unique title and a unique description for each URL that wants a job.** Duplicates are how a suitcase site mumbles.

7. **Canonicals, internal reachability, and honesty about parameters.** If `http` and `https`, trailing slashes, filter parameters, and campaign tags all show the same document, tell the system which URL is the document. Then make your redirects agree with that choice. A canonical that points at a different story than the user sees is not a technicality. It is a lie the librarian will eventually notice.

After the seven, do the adult thing: **inspect the fetched HTML** for the URLs that matter. Use the webmaster tool’s inspection, or a raw fetch, not only your laptop’s view-source after everything has run. If you have a second engine in the market, use its site scan as a complement, not as a new religion.

---

## What “Discovered, Not Indexed” Is Trying to Say

Coverage reports speak in statuses that change wording across years and vendors. I will not freeze a menu label. I will freeze the jobs underneath.

**We have not found this yet, or we found a hint and have not fetched it properly.** Sitemaps, internal links, and a handful of real mentions help discovery. Orphan URLs hope.

**We found it and have not stored it.** This can be a quality judgment, a duplication judgment, a crawl-budget judgment, or a wait. It can also be you: thin pages, doorway clusters, or a site that looks like an attic. Publishing more of the same rarely persuades a librarian who already declined the last twelve.

**We stored it and then unstuck it.** Something changed — a noindex, a canonical, a quality drop, a legal takedown, a moved URL. The report is a history. Read it as history.

The handbook’s structural case — an index rate in one telling moving from about seventeen percent toward nearly full coverage, with an organic-traffic shape people rounded to forty percent — is a lesson about attics and pathways, not a coupon. When a site stops hiding useful documents behind click trees, duplicate parameters, and rotting leaves, a system can afford to store more of what remains. If you quote those percentages as your forecast, go back to the front matter.

---

## Architecture Is a Table of Contents

Think of the site as a book, because the metaphor is almost too accurate.

A crawler is a hurried reader with a budget. If the useful chapter is four clicks from the spine, under an unlabeled section, it may never be read. If the book keeps adding appendixes that nobody opens, the reader starts to distrust the table of contents. If two chapters have the same title, the reader picks one and shrugs at the other.

**Hubs** exist to lower depth and to tell the truth about a cluster. A hub is a page that orients: here is the job, here are the specific documents, here is the product when the job is the product. It is not a keyword-stuffed portal you built because a slide mentioned “pillar content.”

**Internal links are votes you actually control.** They should be readable, varied in anchor language, and pointed at documents you want retrieved. “Click here” from a footer farm is a shrug. A sentence in a related guide that sends a person — and a crawler — to `/repair` is a vote.

**Metabolism matters.** Pages that have never earned a query, never earned a click, and never earned an update are candidates for merger, a truthful noindex, or removal. This is not cruelty. It is editing. A librarian should not have to keep every draft you were afraid to delete.

Thursday Packet did not need a “resources” attic with twenty outlines. It needed `/repair` reachable from the homepage, from the preview empty-state, and from the one guide that already told the truth about broken names. That is architecture. It can be done in an afternoon. It is less photogenic than a cluster diagram.

---

## Asking to Be Indexed, Without Superstition

When a new URL is real — content in the HTML, title honest, not blocked — request indexing in the tools you use. Do it for the pages that matter, especially new ones and translated ones if you have them. Do not make the request a superstition that replaces internal links and a sitemap.

Useful updates can invite a return visit. Fake updates, made to “refresh the date,” train you to lie and may not train the crawler to care. If you change a page, change a fact, a test, a limitation, or a screenshot. Then let the `dateModified` you show, if you show one, be a fact as well.

Submit where your market actually searches. For many overseas English products, Google Search Console and Bing Webmaster Tools are the first two desks. Other regional webmaster tools exist and should be added when the market is real, not when a checklist looks cosmopolitan. Some answer paths still borrow from an ordinary web index. IndexNow and its cousins are hints you can use; they are not a second Google. Recheck official docs, because this sentence will age.

---

## A Worked Technical Gate (Composite)

`packet.example.invalid`, invented, dated.

| Check | Result | Evidence | Action |
| --- | --- | --- | --- |
| Render of `/repair` | Fail | Inspection HTML missing the three-step explanation; it appears only after a client fetch | Pre-render the explanation; re-inspect |
| Sitemap | Conditional | File reachable; contains two retired URLs and misses `/repair` | Rebuild from the live map; resubmit |
| robots.txt | Fail | `Disallow: /guides/` leftover from a staging experiment | Remove; record the change |
| noindex | Pass | Official pages have none; `/admin` stays out | — |
| Redirects / 404 | Fail | `/blog/pdf` returns 200 with an empty-state button | True 404 or a one-step redirect to `/repair` if the job moved |
| Titles | Conditional | Three posts share “A better export” | Unique titles or merge |
| Canonical | Pass after fix | HTTPS, apex, no parameter duplicates on the product page | Keep a regression check |

Only after this table is boring should the builder return to the keyword card. The twelve drafted posts were not the stuck layer. The stuck layer was a librarian who never received the book.

---

## Where Technical Hygiene Falsifies Itself

**A site can be technically pretty and still have nothing worth storing.** Perfect scores on a performance report do not create increment. Do the gate, then go to Chapter 5. Do not hide in Lighthouse.

**Some apps cannot be fully pre-rendered**, and that is a product fact. Then your public explanation, pricing, and documentation must still be documents. Do not make the marketing site a clone of the empty shell.

**Aggressive blocking of training crawlers is a policy choice, not an automatic SEO win or loss.** Chapter 6 will separate training from answering. The hard fail is blocking the crawlers that exist to retrieve you for search and answers, by accident, because a copied robots.txt looked strict and serious.

**International and language versions have extra rules** — hreflang, consistency, and the humility to not auto-translate garbage. This book will not fake a full international manual. If that is your actual market, treat official documentation as the source and this chapter as the spirit: one document, one job, a crawler that can finish.

---


## FAQ (Technical, Without a Plugin Parade)

**Do I need a new SEO plugin?** Usually no. You need a truthful document, a sitemap, an honest robots file, and an inspection habit. A plugin that injects twelve schema types you do not display is a new way to lie.

**How often should I request indexing?** When a real document is new or materially changed. Daily requests on an unchanged shell train you to ignore the report.

**What about crawl budget?** On a small site, the attic is the budget problem. Delete or merge rotting URLs before you buy a story about “budget optimization.”

**Can I hide parameter URLs in robots.txt instead of canonicalizing them?** Sometimes, if they are truly useless and you understand the difference between “do not fetch” and “do not store.” If the useful document is only reachable with parameters, you have an architecture problem, not a robots problem.

**Is a perfect performance score required this fortnight?** No. A slow but complete document can be stored. An instant empty shell cannot. Fix the fetched text first; then, if the page is heavy, cut the weight.

---

## Takeaway

**Rule:** The document a crawler receives is the document that can be stored. Your browser is not a witness by itself.

**This week:** Run the technical gate on the one URL you chose in Chapter 3. Inspect the fetched HTML. Fix the first fail before you publish a new outline.
