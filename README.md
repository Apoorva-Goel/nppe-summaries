# NPPE Visual Study Summaries — Website

One-page visual summaries (mindmaps, flowcharts, infographics) for the three core textbooks behind Canada's **National Professional Practice Examination (NPPE / PPE)**. Built as a plain static website so you can open it on your **phone, tablet, or any browser**.

```
nppe-summaries/
├── index.html        ← landing page (links to the 3 books)
├── .nojekyll         ← tells GitHub Pages to serve files as-is
├── README.md         ← this file
├── book1/            ← 18 chapters + index.html + summary.css
├── book2/            ← 35 chapters + index.html + summary.css
└── book3/            ← 27 chapters + index.html + summary.css
```

---

## 🚀 Publish to GitHub Pages (about 5 minutes, one time)

Once live, you get a permanent URL you can open or bookmark on any device.

### Step 1 — Create a GitHub repository
1. Sign in (or sign up) at <https://github.com>.
2. Click the **+** (top-right) → **New repository**.
3. Name it, e.g. `nppe-summaries` (becomes part of your URL).
4. Set it **Public** (required for free Pages).
5. Leave "Add a README" **unchecked** (you already have one).
6. Click **Create repository**.

### Step 2 — Upload the files
1. On the empty repo page, click **uploading an existing file**.
2. Open this `nppe-summaries` folder on your computer and drag **everything inside it** into the upload box: `index.html`, `README.md`, `.nojekyll`, and the `book1/`, `book2/`, `book3/` folders.
3. Wait for all files to finish uploading (80+ files — give it a minute).
4. Type a commit message like *"Initial upload"* → **Commit changes**.

> Tip: if drag-and-drop is flaky with the folders, you can drag each `bookN` folder in as a separate commit.

### Step 3 — Turn on Pages
1. In the repo: **Settings** → **Pages** (left sidebar).
2. **Build and deployment → Source**: choose **Deploy from a branch**.
3. **Branch**: select **main** and **/ (root)** → **Save**.
4. Wait ~1 minute, refresh. You'll see:
   > ✅ Your site is live at `https://yourusername.github.io/nppe-summaries/`

### Step 4 — Use it on your phone/tablet
Open that URL on any device. To make it feel like an app:
- **iPhone/iPad (Safari):** Share → **Add to Home Screen**.
- **Android (Chrome):** ⋮ menu → **Add to Home screen**.

---

## ⚡ Even faster: Netlify Drop (no account, no git)
If you'd rather skip GitHub: go to <https://app.netlify.com/drop> and drag this whole `nppe-summaries` folder onto the page. You get an instant public URL. (Make a free account to keep the URL permanent.)

---

## ✅ Status of the chapters

| Book | Chapters live | Notes |
| --- | --- | --- |
| Book 1 | **18 / 18** | Complete |
| Book 2 | **1 / 35** | Chapter 1 + the index are in. The other 34 chapter files were *online-only* in cloud storage and couldn't be copied automatically — see below. |
| Book 3 | **27 / 27** | Complete |

### Finishing Book 2 (one-time, ~30 seconds)
The Book 2 chapter files live in your cloud-synced folder but weren't downloaded to this PC, so they couldn't be copied. To fix:

1. In **File Explorer**, go to
   `Desktop\credential and license\BOOK2 - Law for Professional Engineers...\Visual Summaries-Book 2`.
2. **Right-click** the folder → **"Always keep on this device"** (OneDrive) — the files download in a few seconds (icons change from a cloud ☁️ to a green check ✔️).
3. Copy **all** the `Chapter NN - ....html` files into this site's `book2/` folder (next to the `Chapter 01` and `summary.css` already there). Don't copy that folder's own `index.html` — this `book2/index.html` already links every chapter.

That's it — the Book 2 page already lists all 35 chapters; the links light up as soon as the files are present.

> Or just re-open this task and ask me to finish Book 2 once the files are downloaded — I'll copy them in.

---

## 🎨 Customize
- **Landing page** text/links: edit `index.html`.
- **A book's chapter list**: edit that book's `index.html`.
- **Look of the summaries**: edit `bookN/summary.css`.

---

## 📜 Disclaimer
Study material derived from the listed textbooks for **personal exam preparation only**. All textbook content remains the intellectual property of the original authors and publishers. Verify against current PEO standards.

Good luck on the NPPE! 🍀
