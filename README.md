# ✉️ Animated Email Signature — copy mine, or make your own

A clean, professional email signature that sits at the bottom of every email you send: your photo, name, title, a verified check, and Website · LinkedIn · GitHub icons — with a smooth intro animation and a subtle idle shine.

> **No coding needed.** Everything below is done in your web browser and in Gmail's settings.

---

## 🅰️ Just want it in your Gmail? (2 minutes)

1. **Open the ready-made signature here:**
   👉 https://htmlpreview.github.io/?https://raw.githubusercontent.com/DanielIbraev/email-signature/main/signature.html
   *(This shows the signature card by itself in your browser.)*
2. Click on the card, press **Select All** (`Cmd`+`A` on Mac / `Ctrl`+`A` on Windows), then **Copy** (`Cmd`/`Ctrl`+`C`).
3. In Gmail, click the **⚙️ gear** (top-right) → **See all settings**.
4. On the **General** tab, scroll to **Signature** → click **＋ Create new**, give it any name.
5. Click inside the big box and **Paste** (`Cmd`/`Ctrl`+`V`).
6. Just below, under **Signature defaults**, choose your signature for **“For new emails”** and **“On reply/forward.”**
7. Scroll to the very bottom → **Save changes.** ✅

Now it appears automatically at the bottom of every email.

---

## ❓ Fixing the two most common Gmail questions

**“There’s a `--` line above my signature. How do I remove it?”**
That’s Gmail adding it, not the signature. To remove it:
Gmail **⚙️ → See all settings → General → Signature**, and **check the box** that says
**“Insert signature before quoted text in replies and remove the ‘--’ line that precedes it.”** → **Save changes.**
The `--` disappears.

**“My photo / icons don’t show up.”**
Gmail is hiding external images. Turn them on:
Gmail **⚙️ → See all settings → General → Images** → select **“Always display external images”** → **Save changes.**

---

## 🅱️ Want your OWN version? (fork it — still no coding)

Everything here is done on the GitHub website.

### Step 1 — Make your own copy
Click **Fork** (top-right of the repo page). You now have your own copy at `github.com/YOUR-USERNAME/email-signature`.

### Step 2 — Add your photo
1. In **your** copy, click the **`assets`** folder → then click **`profile.png`**.
2. Click the **trash icon** to delete it → **Commit changes**.
3. Go back to the **`assets`** folder → **Add file ▾ → Upload files** → drag in your own photo.
4. **Important:** it must be named exactly **`profile.png`** (rename your file to that first). → **Commit changes.**
   *(A square-ish photo looks best.)*

### Step 3 — Edit your details
1. Open **`signature.html`** → click the **pencil ✏️ (Edit)** button.
2. Change only these (use your browser’s Find, `Cmd`/`Ctrl`+`F`):

   | Find this | Replace with |
   |-----------|--------------|
   | `Daniel Ibraev` | your name |
   | `Founder & CEO of Connex` | your title |
   | `danielnibraev@gmail.com` | your email *(appears twice — change both)* |
   | `danielibraev.com` | your website |
   | `linkedin.com/in/daniel-ibraev` | your LinkedIn |
   | `DanielIbraev` (on the line marked `<<< CHANGE USERNAME`) | **your** GitHub username |

3. Click **Commit changes.** Leave everything else as-is.

*(Don’t have a website or LinkedIn? You can leave those links — or ask and it’s easy to remove an icon.)*

### Step 4 — Copy yours into Gmail
Open your version in the browser:
`https://htmlpreview.github.io/?https://raw.githubusercontent.com/YOUR-USERNAME/email-signature/main/signature.html`
Then follow **Section 🅰️** from step 2 onward.

---

## 🎬 A note on the animation
The intro + subtle shine play in **Apple Mail**, **Outlook for Mac**, and any web browser. **Gmail shows the same card without motion** — every email signature is static in Gmail; that’s Gmail’s rule, not this file. Your photo, badge, icons, and links all look right either way.

## License
[MIT](LICENSE) — free to use and share.
