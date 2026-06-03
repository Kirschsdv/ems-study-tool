# Graad 9 EBS/EMS Studietoetsel · Grade 9 EMS Study Tool

A free, bilingual (Afrikaans/English) CAPS-aligned study tool for Grade 9 Economics and Management Sciences (EBS/EMS) in South Africa.

**Live app:** [https://YOUR-USERNAME.github.io/YOUR-REPO-NAME](https://github.com)

---

## What's in this repo

This is a **pre-built static site** — no build step required. Upload the files, enable GitHub Pages, done.

```
index.html              ← entry point
404.html                ← SPA routing fallback for GitHub Pages
static/
  js/
    main.[hash].js      ← compiled React app (everything in one file)
    main.[hash].js.LICENSE.txt
```

## Features

- 📖 **6 CAPS topics** — Economic Systems, Circular Flow, Price Theory, Sectors, Credit Transactions, Financial Literacy
- 🀄 **36 flashcards** with topic filter
- 🧠 **47 exam-difficulty MCQ** with explain panels and scenario-based distractors
- 📓 **Journal practice** — 4 past-paper CRJ/CPJ/DJ sets (Dahl 2024, Red Hot Dealz 2023, Die Borrelwinkel 2022, Sandy Juweliers 2019)
- 📒 **General Ledger tool** — T-accounts, Trial Balance, Error Identification (4 datasets)
- 📈 **Price Graph tool** — 5 real demand schedules with live SVG graphs
- 🔄 **Circular Flow diagram** — interactive tappable participants
- 📄 **Business Plan builder** — step-through entrepreneurship tool
- ⚖️ **Accounting Equation builder** — 12 scenarios + mark-up calculator
- 📜 **9 source question sets** — past-paper format (1+2+2+8 mark structure)
- 🌐 **Full bilingual toggle** — Afrikaans and English throughout
- 📄 **Past papers links** — verified free resources (testpapers.co.za, sapapers.co.za, and more)

## Deploy to GitHub Pages (manual upload)

1. Create a new GitHub repository (public)
2. Upload all files **preserving the folder structure**:
   - `index.html` → root
   - `404.html` → root
   - `static/js/main.[hash].js` → inside `static/js/` folder
   - `static/js/main.[hash].js.LICENSE.txt` → inside `static/js/` folder
3. Go to **Settings → Pages**
4. Under **Source**, select **Deploy from a branch**
5. Choose **main** branch, **/ (root)** folder
6. Click **Save**
7. Wait ~60 seconds, then visit `https://YOUR-USERNAME.github.io/YOUR-REPO-NAME`

> **Important:** Keep the `static/js/` folder structure exactly as-is. The `index.html` references `./static/js/main.[hash].js` with a relative path, so the folder hierarchy must be maintained.

## Source

Built with React 18. All content, components, data, and styles live in a single `App.jsx` file (~6700 lines). No backend, no database, no external API calls. Works fully offline once loaded.

CAPS curriculum aligned to the 2023/24 Annual Teaching Plan for Grade 9 EMS (Gauteng).

## License

Educational use. Past paper content is the property of the Gauteng Department of Education.
