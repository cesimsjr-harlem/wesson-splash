Wesson Property Partners — Prelaunch Splash Page

Files
- index.html: main page with logo, tagline, launch text, and email form
- styles.css: brand-aligned styles using Montserrat and palette
- assets/logo.png: provided final logo
- assets/favicon.svg: basic favicon
- privacy.html: placeholder privacy policy
- .well-known/security.txt: security contact

Deploy on Cloudflare Pages
1) Create a new GitHub repo and add these files at the root.
2) In Cloudflare Pages, create a project and connect the repo.
3) Build command: leave empty. Output directory: / (root).
4) Deploy, then add your custom domain in Pages and enable SSL.

Form
- Replace the action attribute in the form with your Formspree endpoint.
- Optionally add Cloudflare Turnstile for spam protection.

Brand
- Colors in CSS come from your guide: #1C2C44, #2E6F78, #44644A, #4B6638, #F2F5E2.
- Edit tagline and launch date inside index.html.

