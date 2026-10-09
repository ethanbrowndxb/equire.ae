# equire.ae

Marketing website for **equire**, the verified marketplace for UAE business sales and investment.

A single static page (`index.html`) with no build step. Fonts load from Google Fonts; everything else is inline.

## Run locally

Open `index.html` in a browser, or serve the folder:

```sh
python3 -m http.server 8000
```

## Deploy

Any static host works (GitHub Pages, Netlify, Vercel, Cloudflare Pages). Point the `equire.ae` domain at the host once DNS is set up.

## Notes

- Listings and the broker dashboard on the page are illustrative examples.
- The pilot sign-up form prepares an email to `hello@equire.ae`; connect it to a form backend or CRM before launch.
