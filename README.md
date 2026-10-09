# equire.ae

Marketing website for **equire**, the verified marketplace for UAE business sales and investment.

A single static page (`index.html`) with no build step. Fonts load from Google Fonts; everything else is inline.

## App preview

`app/` holds the equire mobile app prototype, live at `equire.ae/app`. It is an installable web app (PWA): open it on a phone and use **Add to Home Screen** to get a full-screen app icon. Everything runs in the browser with example data; nothing is sent anywhere.

## Run locally

Open `index.html` in a browser, or serve the folder:

```sh
python3 -m http.server 8000
```

## Deploy

Any static host works (GitHub Pages, Netlify, Vercel, Cloudflare Pages). Point the `equire.ae` domain at the host once DNS is set up.

## Notes

- Listings and the broker dashboard on the page are illustrative examples.
- The pilot sign-up form prepares an email to `contact.us@equire.ae`; connect it to a form backend or CRM before launch.
