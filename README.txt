CREATIVE DRAWING — CURRENT PRODUCTION BASE

Files:
- index.html  (single bilingual EN/ES source of truth; EN default)
- assets/ramiro-clemente.jpg
- assets/instagram.jpg
- assets/facebook.png

Production links configured:
- Workshop checkout: https://buy.stripe.com/14kbLO7gC0bl4vu7sE
- Mentorship: https://ramiroclemente-mentorship.subscribepage.io/
- Instagram: https://www.instagram.com/ramiroclemente/
- Facebook: https://www.facebook.com/ramiroclementeart
- 2026 workshop preview: public embedded player used by Brave Art Academy's 2026 class page.

Lead form:
- AJAX notifications go to ramiroclemente2000@gmail.com through FormSubmit.
- IMPORTANT: FormSubmit requires the recipient to activate the form the first time it is used from the deployed site. Check that inbox and click the activation email.
- The form records newsletter consent and source information.
- Duplicate handling uses a SHA-256 hash of the normalized email in localStorage; the raw email is not stored in the browser.
- Future linked landing pages on the SAME origin/browser should use the same keys:
  RC_LEAD_KEY = ramiro_clemente_leads_v1
  RC_KNOWN_KEY = ramiro_clemente_known_lead_v1
- True cross-domain/cross-device deduplication requires a shared newsletter/CRM backend that performs an email UPSERT. A static GitHub Pages site cannot guarantee that by itself.

Deployment:
Upload the entire folder contents to the GitHub Pages repository root (or keep the assets folder path unchanged).


2026-09-05 update: evergreen landing refined; hero profile image removed; preview gate simplified; mentorship links point to https://ramiroclemente.github.io/mentorship/ and open in a new tab; social icons standardized; typography restricted to Futura PT Book/Medium/Demi with minimum 12px (9pt).
