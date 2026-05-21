================================================================
  LEARN2THRIVE  -  EMAIL SIGNATURE KIT
================================================================

WHAT'S IN THIS FOLDER
---------------------
  L2T-signature.html   The signature itself. Open in a browser to install.
  preview.html         Shows the signature in light + dark mode (reference).
  images/              The 4 logo files that must be hosted online.
  README.txt           This file.


----------------------------------------------------------------
STEP 1 - HOST THE 4 IMAGES  (do this once for the whole team)
----------------------------------------------------------------
Email images cannot be local files - they must live at a public web
address. Everyone's signature will point at the SAME hosted images.

Upload the 4 files in the /images folder to your website, e.g. into a
folder called /email-assets/. Good options:
  - Your website host (ask whoever manages www.L2T.org)
  - A CDN or file host that gives permanent public links

After uploading you should have 4 working URLs, for example:
  https://www.L2T.org/email-assets/l2t-logo-light-mode.png
  https://www.L2T.org/email-assets/l2t-logo-dark-mode.png
  https://www.L2T.org/email-assets/thrivist-podcast-light-mode.png
  https://www.L2T.org/email-assets/thrivist-podcast-dark-mode.png

Test each URL by pasting it into a browser - the logo should appear.
Do NOT rename the files after uploading.


----------------------------------------------------------------
STEP 2 - PUT YOUR URLS INTO THE SIGNATURE
----------------------------------------------------------------
Open L2T-signature.html in a plain text editor (Notepad, TextEdit,
VS Code). Find the four placeholder URLs that start with:

  https://www.L2T.org/email-assets/

Replace each with your real hosted URL from Step 1. Save the file.
(If you hosted at exactly www.L2T.org/email-assets/ with the same
file names, no changes are needed.)


----------------------------------------------------------------
STEP 3A - INSTALL IN GMAIL
----------------------------------------------------------------
  1. Double-click L2T-signature.html so it opens in a browser.
  2. Click just before the logo, then drag to select the ENTIRE
     signature (logo through podcast image).
  3. Copy it  (Ctrl+C  /  Cmd+C).
  4. In Gmail: Settings (gear) > See all settings > General tab.
  5. Scroll to "Signature" > Create new (or edit existing).
  6. Click in the signature box and paste  (Ctrl+V / Cmd+V).
  7. Scroll down and click "Save Changes".


----------------------------------------------------------------
STEP 3B - INSTALL IN OUTLOOK
----------------------------------------------------------------
NEW OUTLOOK (Windows) or OUTLOOK ON THE WEB:
  1. Open L2T-signature.html in a browser, select the whole
     signature, and copy it (as in Step 3A).
  2. Settings (gear) > Mail > Compose and reply (or "Signatures").
  3. Create a signature, paste into the box, Save.

CLASSIC OUTLOOK (Windows) - most reliable method:
  1. Outlook > File > Options > Mail > Signatures.
  2. Click "New", name it (e.g. L2T), click OK, then Save and close.
  3. On your PC open this folder (paste into the address bar):
        %APPDATA%\Microsoft\Signatures
  4. You'll see L2T.htm . Open it in Notepad.
  5. Delete everything in it, then paste in the full contents of
     L2T-signature.html . Save.
  6. Restart Outlook. The signature is ready under File > Options >
     Mail > Signatures (assign it to new mail / replies).

OUTLOOK FOR MAC:
  Outlook > Settings > Signatures > "+", paste the copied signature.


----------------------------------------------------------------
STEP 4 - TEST IT (both directions)
----------------------------------------------------------------
GMAIL -> OUTLOOK
  - Install the signature in Gmail (Step 3A).
  - Compose a new email in Gmail, send it to your Outlook address.
  - Open it in Outlook. Check: logos load, layout is intact, the
    L2T.org and podcast links work.

OUTLOOK -> GMAIL
  - Install the signature in Outlook (Step 3B).
  - Compose a new email in Outlook, send it to your Gmail address.
  - Open it in Gmail and check the same things.

ALSO CHECK ON A PHONE
  - View both test emails in the Gmail app and the Outlook app.
  - Side-by-side layout stays side-by-side and scales down; it does
    not stack. That is expected and normal for signatures.

If a logo shows as a broken-image icon, the image URL is wrong or
the file is not public yet - recheck Step 1 and Step 2.


----------------------------------------------------------------
ABOUT DARK MODE - WHAT TO EXPECT
----------------------------------------------------------------
The signature is built to adapt to dark mode: it swaps to the
light-background l2t circle and the white-text podcast logo, and
recolors text to #FCFAF3.

This full behavior is honored by Apple Mail (Mac and iPhone), and by
the Classic Outlook ".htm file" install above.

Gmail and most other clients do NOT support conditional dark-mode
styling in a signature. In those clients you get the light-mode
logos, and the client applies its OWN automatic dark-mode
adjustment to the text. It stays readable, but it will not be the
exact #FCFAF3 - that level of control is not possible in a pasted
signature. This is a known email limitation, not a bug in the file.


----------------------------------------------------------------
ROLLING IT OUT TO THE TEAM
----------------------------------------------------------------
1. One person completes Step 1 (host the images) and Step 2 (put the
   URLs in the file). Share that finished L2T-signature.html file.
2. Each teammate edits ONLY their personal details in the file:
   name, credentials, the title line, address (if different),
   and phone number. Leave all the HTML tags and colors alone.
3. Each teammate installs using Step 3A (Gmail) or 3B (Outlook).
4. Everyone points at the SAME hosted images - teammates do not need
   to host their own copies.

Tip: keep one master copy of L2T-signature.html somewhere shared so
future hires can grab it.
================================================================
