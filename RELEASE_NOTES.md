# LumiNote v2.0 — Release Notes

**Release type:** Unpacked extension (manual install)
**Manifest:** V3
**Compatible browsers:** Microsoft Edge, Google Chrome, and other Chromium-based browsers

> Prefer a one-click install? LumiNote is also on the
> [Microsoft Edge Add-ons store](https://microsoftedge.microsoft.com/addons/detail/luminote/icfniiligafjcfkomejlehlkdhbihbcg).
> This release is for people who want to run the **unpacked** version directly.

---

## ✨ What's included

LumiNote turns any webpage into an interactive research canvas:

- 🖍️ **Multi-color highlighting** — five preset colors plus a custom color picker (your last custom color is remembered).
- 📝 **Notes on highlights** — attach a written note to any highlight and read it back on hover.
- ✏️ **Drawing & handwriting** — sketch on a multi-page canvas with pen, eraser, and stroke eraser; strokes are saved as editable vector data.
- 💾 **Persistent highlights** — highlights re-anchor to the page via DOM paths and reappear on your next visit.
- 📚 **The LumiNote Library** — a dashboard of every highlight grouped by website, with live search and filters by domain and color.
- 📄 **Export to Word & PDF** — export a page's highlights (with notes and drawings) to a `.doc` file or a print-ready PDF.
- 🧹 **Easy cleanup** — clear the current page, delete a single highlight, or reset everything.

Everything is stored **locally** in your browser — no accounts, no servers, no tracking.

---

## 📦 Package contents

The release archive (`luminote-v2.0.zip`) contains **only** the files required to run the extension:

```
luminote-v2.0/
├── manifest.json
├── content.js
├── styles.css
├── popup.html
├── popup.js
├── highlights.html
├── highlights.js
└── icons/
    ├── icon16.png
    ├── icon32.png
    ├── icon48.png
    └── icon128.png
```

Source-only assets (promo art, screenshots, PSDs, videos, READMEs) are **not** part of the runtime package.

---

## 🚀 Install (Load unpacked)

1. **Download** `luminote-v2.0.zip` from this release and **extract** it to a folder you'll keep (the browser reads the files from this location on every launch — don't delete it after installing).
2. Open your browser's extensions page:
   - Edge: `edge://extensions`
   - Chrome: `chrome://extensions`
3. Turn on **Developer mode** (top-right toggle).
4. Click **Load unpacked** and select the extracted `luminote-v2.0` folder (the one containing `manifest.json`).
5. LumiNote appears in your toolbar — pin it for quick access. ✅

### Updating from a previous unpacked copy
Replace the old folder with the new one (or overwrite the files), then click the **Reload** ↻ icon on the LumiNote card in the extensions page. Your saved highlights are kept — they live in browser storage, not in the extension folder.

---

## 🔒 Permissions

- **`storage`** — save your highlights, notes, and drawings locally.
- **`activeTab`** — apply and clear highlights on the page you're viewing.

No data leaves your device.

---

## ⚠️ Known notes

- **Developer-mode banner:** Chromium browsers may show a "remove developer-mode extensions" prompt on startup. This is expected for any unpacked extension — click *Keep* / dismiss it.
- **Word export** produces an MHTML-based `.doc`; open it in Microsoft Word for best fidelity.
- **PDF export** uses the browser's print dialog — choose *Save as PDF* as the destination.
- Keep the extracted folder in place; deleting or moving it will disable the extension until you re-point the browser to it.

---

_Made with 💛 — Quick Notes, Illuminated Insights._
