# Pharmanic website

Plain static site (HTML + CSS + JS) — upload the whole folder to any host (Netlify, Vercel, GitHub Pages, cPanel, etc.). Open `index.html` to preview locally.

## Fill in your details
Edit **js/config.js**: phone, email, WhatsApp, address, working hours, map address, social links, form endpoint.
Anything left empty shows a marked placeholder and the matching button appears disabled.

## Contact form
Needs a backend to deliver messages. Either paste a form-service URL (e.g. Formspree) into `formEndpoint`,
or set `email` and the form will open the visitor's email app with the message pre-filled.

## Images
Product images were cropped from the posters you supplied (low resolution). Replacing the files in `img/`
with original high-resolution photos (same file names) will make the site sharper.

## Fonts
Cormorant Garamond, Manrope and Noto Sans Georgian load from Google Fonts (needs internet).
