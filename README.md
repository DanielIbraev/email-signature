# ✉️ Animated Email Signature

A clean, modern **email signature card** that sits at the bottom of every email — circular photo with a rotating gradient ring, shimmering name, and floating **Website · LinkedIn · GitHub** icons.

<img src="assets/profile.png" width="110" align="right">

**What's in here**

| File | Purpose |
|------|---------|
| `signature.html` | The signature. Open it, copy the card, paste into your mail client. |
| `assets/profile.png` | The photo (hosted here so email clients can load it). |

---

## 📧 Put it at the bottom of every email (automatic)

### Gmail (web)
1. Open `signature.html` in a browser → select the whole card → **Copy** (⌘/Ctrl-C).
2. Gmail → **⚙️ → See all settings → General → Signature → Create new**.
3. Paste it in, then under **Signature defaults** set it for **"For new emails"** and **"On reply/forward"**.
4. **Save changes** at the bottom. Done — it's on every email. ✅

### Apple Mail (macOS)
1. **Mail → Settings → Signatures →** pick your account → **＋**.
2. **Uncheck** "Always match my default message font".
3. Open `signature.html` in Safari, copy the card, paste into the signature box.
4. Set **"Choose Signature"** at the bottom to this one. Hover + looped animations work here. ✅

### Outlook (web)
**Settings → Mail → Compose and reply → Email signature** → paste → toggle on for new messages & replies → **Save**.

---

## 🎬 About the animations
The looped animations (rotating ring, shimmering name, floating icons, light-sweep) play in **Apple Mail**, **Outlook for Mac**, and any browser. **Gmail strips CSS animations** from signatures, so there it shows the same card, clean and static — that's a limit of Gmail, not the file.

---

## 🍴 Want your own?
Fork this repo, replace `assets/profile.png` with your photo, and edit the name / email / links inside `signature.html`. ~2 minutes.

## License
[MIT](LICENSE)
