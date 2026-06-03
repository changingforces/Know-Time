Know Time Wave Clock — deployable mobile website

This is not an Android/iPhone store app. It is a static website package.

Files:
- index.html: the app
- manifest.json: lets mobile browsers offer "Add to Home Screen" after hosting
- sw.js: offline cache after hosting over HTTPS

To make it work on iPhone and Android reliably:
1. Upload this folder to any static web host, such as GitHub Pages, Netlify, Cloudflare Pages, or a basic web server.
2. Open the hosted HTTPS URL in Safari/Chrome.
3. Use Share -> Add to Home Screen.

Opening from a ChatGPT sandbox link, file preview, or zip preview may fail on phones even when the app code is valid.
