# Starting Toolkit - Commercial Website

Multilingual static sales website for Cloudflare Pages.

- `/pt/`: Portuguese offer for Brazil, R$ 87.
- `/en/`: English international offer, US$ 19.
- `/es/`: Spanish international offer, US$ 19.
- `/blog/`: initial editorial pages in three languages.
- `/config/site-config.js`: replace the two Hotmart checkout placeholders before accepting purchases.

## Deploy
Static site. No build command. Output directory: `/`. Deploy this repository as a separate Cloudflare Pages project and attach `startingtoolkit.com`. Keep the existing app project and `app.startingtoolkit.com` unchanged.

## Before launch
1. Replace `COLE_AQUI_LINK_HOTMART_R$87` with the Brazilian Hotmart checkout URL.
2. Replace `COLE_AQUI_LINK_HOTMART_US$19` with the international Hotmart checkout URL.
3. Review and complete the privacy and terms pages with the business operator details and applicable legal information.
4. Verify checkout, mobile layout, and language switching.

The page currently uses a CSS-built product preview, not a screenshot of the live application.


## Blog editorial files

- Blog index: `/blog/`
- Portuguese listing: `/blog/pt.html`
- English listing: `/blog/en.html`
- Spanish listing: `/blog/es.html`
- Article pages: `/pt/`, `/en/`, and `/es/` with localized slugs.
- SEO: `sitemap.xml`, `robots.txt`, canonical URLs, hreflang, Open Graph, and BlogPosting structured data are included.

The three initial articles are published as nine localized pages. Review the copy and replace the publication date if you schedule them for a later date. The calls to action link to the corresponding language landing page.
