# Upgrade notes

New files: upgrades.css, script.js (was empty), favicon.svg, 404.html, sitemap.xml
Changed: every .html page gets additions only (head tags, skip link, `id="main-content"`, footer on posts).
style.css and all page content are untouched.

Rollback: delete the "UPGRADE" block in <head> of a page, or restore from git history.

Still needs you:
1. howrah-forgings.html links to 5 PDFs that are not in the repo (404 today):
   product-report.pdf, cost-analysis.pdf, calcutta-steel-letter.pdf,
   howrah-forgings-letter.pdf, howrah-forgings-certificate.pdf
2. contact.html email is agarwalvivaan09@email.com - confirm the domain is right.
3. research.html links "Household_Financial_Resiliance_Index_Vivaan_Agarwal (1).pdf"
   (typo "Resiliance", and spaces/"(1)" in the name). Rename file + link together.
4. `images`, `icons`, `fonts` in the repo root are empty 0-byte files, not folders. Safe to delete.
5. Submit sitemap.xml in Google Search Console.
