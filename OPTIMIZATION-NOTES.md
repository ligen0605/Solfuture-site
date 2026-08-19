# Solfuture Energy website optimisation

## What changed

- Rebuilt the page around a clearer conversion path and stronger visual hierarchy.
- Fixed horizontal overflow and added a proper mobile navigation menu.
- Added responsive layouts for services, packages, projects, brands and the quote form.
- Improved accessibility with landmarks, labels, keyboard focus styles, a skip link and reduced-motion support.
- Improved SEO with canonical, Open Graph, Twitter Card and EnergyBusiness structured data.
- Improved loading behaviour with a responsive hero image, explicit image dimensions and lazy-loaded brand images.
- Added honest package pricing qualifications and clearer enquiry copy.
- Added package-to-form prefill interaction and current-year footer logic.
- Split packages into Residential and Commercial categories with an accessible navigation dropdown.
- Added 50kW, 100kW and 150kW DC commercial packages with enquiry-form prefill.
- Marked the 50kW and 150kW commercial options as Popular and added the commercial pricing note: prices exclude GST and remain subject to applicable STC/VEEC incentive policies.
- Exported the supplied Adobe Illustrator logo to a transparent, web-optimised PNG and integrated it into the header and footer.
- Updated the partner brand wall with official Sigenergy and Hanersun logos and removed DMEGC.
- Replaced the temporary Vercel canonical and social URL with the official `https://www.solfuture.com.au/` address.
- Added `robots.txt` and `sitemap.xml` for search-engine discovery.
- Added the public phone number and email as clickable contact details and included them in structured data.

## Before publishing

The quote form now uses FormSubmit and sends enquiries to `sales@solfuture.com.au`. No API key, serverless function or Vercel environment variables are required.

1. Publish the site and submit the form once.
2. Open the activation email sent by FormSubmit to `sales@solfuture.com.au`.
3. Click **Confirm**. Enquiries will only be delivered after this confirmation.

The form uses FormSubmit's table email template, customer email as Reply-To and a hidden honeypot field. CAPTCHA is disabled to keep the AJAX form experience on the current page. FormSubmit is a third-party processor and says submissions are retained for 30 days.

Also add service locations, a privacy policy and any further verified credentials when available.

## Deploy

Replace the repository contents with this version, including `index.html` and `assets`. Commit and push to `main`; GitHub Pages or the existing Vercel project can host it as a static site.
