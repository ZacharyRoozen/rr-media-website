R&R Media — delta export, 2026-09-08
Unzip over site/ at repo root. Overwrites 4 files:

  index.html        contact form -> Web3Forms (access_key, subject, from_name,
                    botcheck honeypot, required fields, #ct-status region)
  index2.html       same changes
  css/home.css      #ct-status styling + disabled-button state
  js/app.js         AJAX submit handler (no redirect off-site);
                    fallback address info@rrmediamarketing.com

Web3Forms notes
  - access_key 8e66ccb9-dcfa-4c1c-9318-4800d2a3a6a7 is public by design.
  - All fields POST through automatically, incl. company, interest and the six
    lead_* hidden fields. No custom-field setup needed in the dashboard.
  - "botcheck" is the honeypot; leave it hidden.

Debug gridline code is stripped from these HTML files.

Unchanged since 2026-09-02 export: services.html, css/styles.css,
css/home2.css, css/services.css
