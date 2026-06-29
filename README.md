# 🎮 Alpha Gaming: Your Ultimate Gaming Storefront

A fun, responsive **e-commerce frontend** for gamers. Browse games, consoles, and accessories, search instantly, add items to a cart, and check out — all in a clean, modern layout.

This is a **completely static, frontend-only** project: plain **HTML, CSS, and JavaScript**, with product data driven by a single `products.json` file. No build step, no framework, no backend required.

---

## ✨ Features

- **Massive Game Library** — games, consoles, and accessories in one catalog 🕹️
- **Shopping Cart** — add items, manage quantities, and proceed to checkout 🛒
- **Instant Search** — quickly filter products by name 🔍
- **Fully Responsive** — works great on mobile, tablet, and desktop 📱🖥️
- **Data-Driven Catalog** — products are loaded from `products.json`, so adding new games/consoles doesn't require touching HTML by hand 📦
- **Clean, Modern UI** — simple, friendly design with per-page styling ✨

---

## 💻 Tech Stack

| Layer | Tech |
|---|---|
| Structure | HTML5 |
| Styling | CSS3 (global + per-page stylesheets) |
| Behavior | Vanilla JavaScript |
| Data | JSON (`products.json`) |

> No npm, no React, no build tools — just open the HTML files in a browser.

---

## 🧩 Project Structure

```
Gaming-store/
├── .github/
│   └── copilot-instructions.md
├── html-child/              # individual pages: per-category & per-game
│   ├── games.html, consoles.html, accessories.html
│   ├── cart.html, checkout.html, contact.html
│   ├── Gamingnews.html, special.html
│   └── elden_ring.html, gta5.html, zelda.html, tekken8.html, ... (per-title pages)
├── script-child/
│   ├── consolesscript.js     # logic for the consoles page
│   └── gamesscript.js        # logic for the games page
├── styles-child/
│   └── *.css                 # one stylesheet per page (cart, checkout, each game, etc.)
├── images/                   # product photos & social icons
├── index.html                 # homepage
├── script.js                  # global / shared JavaScript
├── script1.js                  # additional global JavaScript
├── style.css                   # global stylesheet
├── styles.css                  # additional global stylesheet
├── products.json               # full product catalog (games, consoles, accessories)
├── PRODUCTS_JSON_README.md     # schema/docs for products.json
├── example-json-usage.html     # demo: how to read products.json on a page
├── LICENSE                     # MIT
└── README.md
```

---

## 🚀 Getting Started

No installation needed — this is a static site.

1. **Clone the repo:**
   ```bash
   git clone https://github.com/alphaxt/Gaming-store.git
   cd Gaming-store
   ```

2. **Open it in a browser:**
   - Easiest: double-click `index.html`, **or**
   - Recommended (avoids JSON/fetch issues with `file://` URLs): serve it locally:
     ```bash
     # Python 3
     python -m http.server 5500
     # then visit http://localhost:5500
     ```
     or use the **Live Server** extension in VS Code.

That's it — browse, search, add to cart, and check out.

---

## 📦 Product Data

All catalog data (games, consoles, accessories) lives in [`products.json`](./products.json). See [`PRODUCTS_JSON_README.md`](./PRODUCTS_JSON_README.md) for the full schema, and [`example-json-usage.html`](./example-json-usage.html) for a working example of reading it on a page.

---

## 📜 License

This project is licensed under the **MIT License** — see [LICENSE](./LICENSE) for details.

---

**Developed by Muhammad Danish**
