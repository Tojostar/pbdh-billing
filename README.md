# PBDH Billing Log

Offline web app for logging hospital consults (patient, In/Out, start/finish, level A–E, call-out band, life saving, comments).
Works on iPhone, iPad, Android and desktop. Data is stored on each device only.

## Put it online (pick one, both free)

**Netlify Drop (easiest, 2 minutes)**
1. On a computer, unzip this folder.
2. Go to https://app.netlify.com/drop and drag the `pbdh-billing` folder onto the page.
3. You get a link like `https://something.netlify.app`. Sign up (free) to keep it permanently and rename it.

**GitHub Pages**
1. Create a new repository and upload all files in this folder.
2. Settings → Pages → Source: "Deploy from a branch" → `main` / root → Save.
3. Your app is at `https://<username>.github.io/<repo>/`.

## Add the icon to your home screen
- **iPhone/iPad:** open the link in Safari → Share → Add to Home Screen.
- **Android:** open in Chrome → ⋮ → Add to Home screen (or "Install app").

It then opens full-screen with its own icon, and works without internet after the first load.

## Phone ↔ tablet
Each device keeps its own data. To move entries across: Summary → **Back up all data** on one device,
send the file to the other (AirDrop, email, Files), then Summary → **Restore / merge**. Restoring merges and never deletes.

## Privacy
Patient names stay on the device. Nothing is sent anywhere. Back up regularly: clearing Safari/Chrome website data,
or deleting the home-screen app on iPhone, erases the stored entries.
