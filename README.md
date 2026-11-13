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

Site comercial Starting Toolkit
