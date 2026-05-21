# Learn2Thrive — Email Signature

This repo hosts the Learn2Thrive email signature and its logo images.
The images are already hosted here, so there is **nothing to set up** —
just install the signature.

## Files

| File | Purpose |
|------|---------|
| `L2T-signature.html` | The signature. Open in a browser to install it. |
| `preview.html` | Shows the signature in light + dark mode (reference only). |
| `l2t-logo-light-mode.png` / `l2t-logo-dark-mode.png` | l2t circle logo. |
| `thrivist-podcast-light-mode.png` / `thrivist-podcast-dark-mode.png` | Podcast logo. |

The four logos are served from these public URLs (already wired into the signature):

```
https://raw.githubusercontent.com/brendanlymurphy/learn2thrive-email-assets/main/l2t-logo-light-mode.png
https://raw.githubusercontent.com/brendanlymurphy/learn2thrive-email-assets/main/l2t-logo-dark-mode.png
https://raw.githubusercontent.com/brendanlymurphy/learn2thrive-email-assets/main/thrivist-podcast-light-mode.png
https://raw.githubusercontent.com/brendanlymurphy/learn2thrive-email-assets/main/thrivist-podcast-dark-mode.png
```

Do not rename or move these files — the signature points at these exact paths.

## Install in Gmail

1. Open `L2T-signature.html` in a web browser (download it, then double-click).
2. Click just before the logo and drag to select the **entire** signature,
   down through the podcast logo.
3. Copy it (`Ctrl+C` / `Cmd+C`).
4. Gmail → Settings (gear) → **See all settings** → **General**.
5. Scroll to **Signature** → **Create new** (or edit an existing one).
6. Click in the box, paste (`Ctrl+V` / `Cmd+V`), then **Save Changes**.

## Install in Outlook

**New Outlook / Outlook on the web:** copy the signature from the browser
(steps 1–3 above), then go to Settings → Mail → **Compose and reply** /
**Signatures**, paste, and save.

**Classic Outlook (Windows) — most reliable:**
1. Outlook → File → Options → Mail → **Signatures** → **New**, name it
   (e.g. `L2T`), click OK, then Save and close.
2. In File Explorer, open: `%APPDATA%\Microsoft\Signatures`
3. Open `L2T.htm` in Notepad, delete its contents, and paste in the full
   contents of `L2T-signature.html`. Save.
4. Restart Outlook and assign the signature under File → Options → Mail.

**Outlook for Mac:** Outlook → Settings → Signatures → **+**, paste.

## Test it

- **Gmail → Outlook:** install in Gmail, send yourself a message, open it
  in Outlook. Check logos load, layout holds, and links work.
- **Outlook → Gmail:** install in Outlook, send to Gmail, check the same.
- View both on the Gmail and Outlook **phone apps** too. The side-by-side
  layout scales down rather than stacking — that is expected.

## Dark mode

The signature adapts to dark mode (swaps to the light-background l2t circle
and white-text podcast logo, recolors text to `#FCFAF3`). This is fully
honored by **Apple Mail** and by the Classic Outlook `.htm` install above.
Gmail and most other clients do not support conditional dark-mode styling
in signatures — there you get the light-mode logos and the client's own
automatic dark adjustment. Still readable, just not pixel-exact. This is a
known email limitation.

## Rolling out to the team

Everyone uses the same `L2T-signature.html` and the same hosted images.
Each teammate edits **only** their personal details in the file — name,
credentials, title line, address, phone — and leaves all HTML tags and
colors alone. Then they install with the Gmail or Outlook steps above.
