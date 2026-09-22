# tanishchachra.com

Personal portfolio site for Tanish Chachra — Content Strategist & Editorial
Lead. Plain HTML/CSS, no build step, no dependencies.

## Editing

- `index.html` — all page content (sections: Home, Experience, Video, About,
  Contact).
- `styles.css` — all styling.
- `assets/` — logos, video thumbnails, and article screenshots.

Open `index.html` directly in a browser to preview, or serve the folder
locally with any static server, e.g. `npx serve .`.

## Deploying

1. Import this repo into [Vercel](https://vercel.com/new) or
   [Netlify](https://app.netlify.com/start) — no build command or output
   directory needed (it's a static site).
2. Once deployed, go to the project's Domains settings and add
   `tanishchachra.com`.
3. At your domain registrar, point the domain at the host:
   - **Vercel**: add the A/CNAME records Vercel shows you on the Domains
     page (usually an `A` record to `76.76.21.21` for the root domain, and
     a `CNAME` to `cname.vercel-dns.com` for `www`).
   - **Netlify**: similarly, either change nameservers to Netlify DNS or
     add the A/CNAME records Netlify provides.
4. DNS changes can take a few minutes up to 48 hours to propagate.
