# Most — Clothing Store Website

A single-page showcase website for **Most**, a clothing store in Modasa, Gujarat, India.
Customers order by phone or WhatsApp — there is no online shop or cart.

- Phone / WhatsApp: **77777 77777**
- Address: Modasa, Gujarat 383315
- Sections: hero, collection cards (men's / women's / kids' wear), why-us, visit us

## Tech

- React 19 with TanStack Start (Vite 7 build)
- Tailwind CSS 4 (`src/styles.css` holds the colours and fonts)
- Photos live in `src/assets/`

## Run it on your computer

```bash
bun install     # or: npm install
bun run dev     # opens on http://localhost:8080
```

Build a production copy with `bun run build`.

## Put this on GitHub

1. Go to github.com and sign in (make a free account if you don't have one).
2. Click **+** (top right) → **New repository**.
3. Give it a name, for example `most-website`, keep it **Private**, then **Create repository**.
4. On the empty repository page choose **"uploading an existing file"**, drag the files in
   (or use the git commands below), then **Commit changes**.

```bash
git init
git add .
git commit -m "Most website"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/most-website.git
git push -u origin main
```

Replace `YOUR-USERNAME` with your GitHub username.

## Main files

| File | What it does |
| --- | --- |
| `src/routes/index.tsx` | The whole landing page: hero, collection cards, visit-us, WhatsApp buttons |
| `src/routes/__root.tsx` | Page head: browser-tab title, search description, Google Fonts |
| `src/styles.css` | Colours and fonts (the site's look) |
| `src/assets/` | The 4 shop photos |
| `src/components/ui/` | Ready-made UI pieces (buttons, cards, dialogs) |
| `package.json` | Package list and scripts |
