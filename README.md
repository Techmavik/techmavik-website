# Techmavik website

A responsive static website for Techmavik, with The Trending Fever presented as its creative digital growth service.

## Preview locally

Open `index.html` in a modern browser. For a local server, run:

```bash
python -m http.server 8000
```

Then visit http://localhost:8000.

## Deploy free with Vercel

1. Create a GitHub account (if needed) and a new repository named `techmavik-website`.
2. Upload `index.html`, `styles.css`, and `script.js` (README optional) to the repository root.
3. Sign in to Vercel with GitHub and choose **Add New → Project**.
4. Import `techmavik-website`. It is a static site: leave the framework preset as **Other**, leave build command and output directory empty, and deploy.
5. In Vercel project **Settings → Domains**, add your purchased domain and follow the exact DNS records Vercel displays at your domain registrar.
6. Wait for DNS verification and HTTPS activation, then test on mobile and desktop.

## Before public launch

- Confirm the correct domain and business email. The current email `hello@techmavik.com` is a suggested placeholder; replace it if your real domain/email differs.
- Replace or confirm the service descriptions and add real portfolio projects, testimonials and business contact details.
- The contact form currently opens the visitor's email application using `mailto:`. Connect a form backend (for example Formspree, Web3Forms or a custom API) before relying on it for lead capture.
- Add privacy policy, terms, analytics and any required consent notices.
