# Thai Vara Ltd. website

Static responsive website for Cloudflare Pages.

## Files
- index.html — homepage and services
- styles.css — responsive luxury-minimal styling
- script.js — mobile navigation and current year
- privacy-policy.html — draft; review before publishing
- assets/favicon.svg — favicon

## Before launch
1. Create a Formspree form and replace REPLACE_WITH_YOUR_FORM_ID in index.html.
2. Replace the placeholder business email in the contact section.
3. Review the privacy policy, company contact details, lawful basis, retention period and Formspree data-processing details.
4. Confirm all claims, service details, qualifications, insurance and service coverage are accurate.
5. Test the form end-to-end.

## Cloudflare Pages
Connect this repository to Cloudflare Pages using Git integration. Framework preset: None. For a plain static site, leave the build command blank and use the repository root as the output directory (or the root option shown by the current Pages setup UI). Add thaivara.co.uk and www.thaivara.co.uk under Custom Domains after deployment.

This site has no database or custom backend. The contact form requires a configured third-party form endpoint. Verify the provider's current free-plan limits and commercial-use terms before relying on it for live business enquiries.