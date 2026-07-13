# ✉️ Animated Email Signature

A clean, modern, **animated** email signature — circular photo, website / LinkedIn / GitHub icons, and a one-click contact. Attaches to **every email automatically**.

**Live preview:** open `index.html` in a browser, or once deployed: `https://your-username.github.io/email-signature/`

![signature preview](assets/preview.png)

---

## 📦 What's in here

| File | Purpose |
|------|---------|
| `signature.html` | The copy-paste signature for your mail client (Gmail / Apple Mail / Outlook). |
| `index.html` | Animated showcase / GitHub Pages landing page. |
| `assets/profile.jpg` | Your photo (**you add this**). |

---

## 🚀 Quick start (make it yours)

1. **Add your photo** → save it as `assets/profile.jpg` (square works best, e.g. 400×400).
2. **Edit your links** → in `signature.html` **and** `index.html`, replace:
   - `WEBSITE_URL` → your website
   - `LINKEDIN_URL` → e.g. `https://www.linkedin.com/in/your-handle`
   - `GITHUB_URL` → e.g. `https://github.com/your-username`
   - `YOUR_TITLE` → your role (e.g. `Full-Stack Developer`)
   - the name / email if you're reusing this as a template.
3. **Host your photo** (needed for Gmail/Outlook — see below), then set `PROFILE_IMAGE_URL` in `signature.html` to that public URL.

---

## 🖼️ Hosting your photo (required for real emails)

Mail clients need a **public https URL** for the photo — they won't ship a local file. The easiest option, since this is already on GitHub:

- Enable **GitHub Pages** (Settings → Pages → Deploy from `main` / root).
- Your photo URL becomes: `https://your-username.github.io/email-signature/assets/profile.jpg`
- Put that URL in `signature.html` where it says `PROFILE_IMAGE_URL`.

---

## 📧 Attach it to every email automatically

### Gmail (web)
1. Open `signature.html` in a browser → select the whole card → **Copy** (⌘/Ctrl-C).
2. Gmail → **⚙️ Settings → See all settings → General → Signature → Create new**.
3. Paste into the box, name it, and set **"For new emails use"** and **"On reply/forward use"** to this signature.
4. **Save changes** at the bottom. It now appears on every email. ✅

> Note: Gmail strips CSS animations and `<style>`, so in Gmail you get the clean static design. The hover animations show in Apple Mail, Outlook (Mac), and the web preview. The animated version lives in `index.html`.

### Apple Mail (macOS)
1. **Mail → Settings → Signatures →** pick your account → **＋**.
2. Temporarily **uncheck** "Always match my default message font".
3. Open `signature.html` in Safari, copy the card, paste into the signature box.
4. Set **"Choose Signature"** at the bottom to this one so it's used automatically. Hover animations work here. ✅

### Outlook (web)
**Settings → Mail → Compose and reply → Email signature** → paste → toggle it on for new messages & replies → **Save**.

### Outlook (desktop, Windows)
**File → Options → Mail → Signatures → New** → paste → set it as default for New messages and Replies/forwards.

---

## 🌐 Deploy the animated page (GitHub Pages)

```bash
# after pushing this repo to GitHub:
# GitHub → repo → Settings → Pages → Source: Deploy from a branch → main / (root) → Save
```

Your animated signature will be live at `https://your-username.github.io/email-signature/`.

---

## 🍴 For everyone else

1. Click **Fork** (top-right).
2. Follow **Quick start** above with your own photo and links.
3. Done — your own animated signature in ~2 minutes.

---

## License

[MIT](LICENSE) — free to use, fork, and modify.
