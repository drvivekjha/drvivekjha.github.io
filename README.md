# drvivekjha.github.io

Personal website of Dr. Vivek Jha, MD DM — Endocrinologist, PGIMER Chandigarh.

## Deploy (5 minutes)

1. Create a GitHub account for Vivek (or use his existing one). The username **must be `drvivekjha`** for the site to live at `https://drvivekjha.github.io`.
2. Create a new **public** repository named exactly `drvivekjha.github.io`.
3. Upload these files to the repository root: `index.html`, `robots.txt`, `sitemap.xml`, and the `assets/` folder.
4. In the repo: **Settings → Pages → Source: Deploy from a branch → main / (root)**. The site goes live at `https://drvivekjha.github.io` within a couple of minutes.

## Add his photo

Save his profile photo as **`assets/profile.jpg`** (portrait orientation, at least 640×800 px). His ResearchGate photo works as a starting point — download it from his RG profile and commit it. If the file is missing, the site shows a "VJ" monogram instead, so nothing breaks.

## Make him rank (SEO checklist)

The page already includes: Physician + Person JSON-LD schema, meta description/keywords, Open Graph tags, canonical URL, sitemap, and robots.txt. To get indexed and climb rankings:

1. **Google Search Console** — add `drvivekjha.github.io` as a URL-prefix property, verify via the HTML-tag method (paste the meta tag into `<head>` of index.html), then **submit the sitemap** (`sitemap.xml`) and request indexing of the homepage. Same flow you used for Pixel Intelligence Lab.
2. **Bing Webmaster Tools** — import the site from Search Console with one click.
3. **Backlinks matter most for a personal site.** Add the website URL to: his ResearchGate profile (website field), ORCID (create one if he doesn't have it — it also helps publication indexing), Google Scholar profile (create one — this alone usually becomes the #2 result for his name), LinkedIn, and any PGIMER/departmental page that lists residents.
4. **Google Scholar profile** is the highest-leverage single step for "appearing at the top of his field" — it aggregates his 42 publications with citation counts and ranks extremely well for name searches.
5. For patient discovery, consider a free **Google Business Profile** once he has a fixed practice location — that's what surfaces doctors in Maps/local results for "endocrinologist near me".
6. Keep the publications section updated — fresh content and accumulating backlinks are what move rankings over months.

## Updating publications

Publications are grouped by year in `index.html` under `<!-- PUBLICATIONS -->`. Each entry is a `<li class="pub">` — copy an existing one, swap the title, ResearchGate link, and journal name.
