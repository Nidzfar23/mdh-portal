MDH EMPLOYEE PORTAL - SETUP GUIDE
=================================

FILES
  index.html      the portal (edit your cards here)
  manifest.json   makes it installable as a phone app
  sw.js           lets it open fast and work offline
  icons/          app icons made from the MDH logo

PUBLISH ON GITHUB PAGES (free)
  1. Sign in at github.com and click New repository. Name it (e.g. mdh-portal), set it to Public, create it.
  2. Click "uploading an existing file" and upload EVERYTHING in this folder
     (index.html, manifest.json, sw.js and the icons folder). Click Commit.
  3. Go to Settings > Pages. Under Branch choose "main" and "/ (root)", then Save.
  4. Wait 1-2 minutes. Your link will be:
       https://YOUR-USERNAME.github.io/mdh-portal/
  5. Open that link on a phone and test it.

INSTALL ON A PHONE
  Android (Chrome): tap the Install button in the portal, or menu > Install app.
  iPhone (Safari):  Share button > Add to Home Screen.

CHANGING THE CARDS
  Option A: open index.html, edit the FORMS list, re-upload it to GitHub.
  Option B: use a Google Sheet (see the comment above SHEET_CSV_URL in index.html).
            After setup, adding a row adds a card. No re-upload needed.

IF USERS SEE AN OLD VERSION AFTER YOU UPDATE
  Open sw.js and change  mdh-portal-v1  to  mdh-portal-v2  (then v3, etc.), and re-upload.
