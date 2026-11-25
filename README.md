# Heavenly Haven website

Static site (single `index.html`) for Heavenly Haven — owner Hope Andai Maina.

## Host on GitHub Pages
1. Create a new repo on GitHub (e.g. `heavenly-haven`).
2. Upload `index.html` and `README.md` to the repo root (Hope's photo is built into `index.html`).
3. Go to **Settings → Pages**, set **Source** to `Deploy from a branch`, pick `main` and `/ (root)`, then Save.
4. After a minute the site is live at `https://<your-username>.github.io/heavenly-haven/`.

## Things you can edit (top of the `<script>` in index.html)
- `PRODUCTS` — each product has a list of sizes `v:[{s:"500ml",p:500}]` (`s` = size label, `p` = price in KES). Change a price or add a size by editing that list.
- `PHONE_INTL` / `PAY_NUMBER` — the WhatsApp and payment number.
