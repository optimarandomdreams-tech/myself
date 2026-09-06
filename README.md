# MDANWARULHAQUE

Md. Anwarul Haque is a seasoned banker and branch administrator with over two decades of experience at Prime Bank Ltd. Holding an M.Sc in Statistics and an LLB, he excels in credit management, audit compliance, and branch operations. Alongside his banking career, he is a creative entrepreneur operating Ms Biswanath Enterprise, focused on food raw materials, digital commerce, and online branding.

This repo hosts his personal CV site, published via GitHub Pages.

## Site

- `index.html` — the CV page
- `style.css` — styling

## Publishing on GitHub Pages

1. Push this repo to GitHub.
2. In the repo Settings → Pages, set the source to the `main` branch, root folder.
3. The site will be live at `https://<username>.github.io/<repo-name>/`.

## Ads

`index.html` has commented-out Google AdSense placeholders (top and bottom of the page).
To enable them:

1. Apply for AdSense at https://adsense.google.com with the live Pages URL.
2. Once approved, swap `ca-pub-XXXXXXXXXXXXXXXX` for the real publisher ID and uncomment the
   script tag in `<head>` and the `<ins class="adsbygoogle">` blocks in the ad slots.

Note: `notification-adcombo.txt` in this repo requests injecting a third-party "Adcombo" push-ad
script and service worker. That was intentionally **not** wired up — those push-notification ad
networks are a known scam/spam vector (they hijack browser notifications to serve unrelated ads
indefinitely) and would hurt the site's credibility and risk it getting flagged. AdSense above is
the safe path to ad revenue.

