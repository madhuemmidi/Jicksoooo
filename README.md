# jicksoooo — Personal Site

Open `index.html` in a browser (or run a static server) — that's it.

## Run locally in VS Code
1. Install the **Live Server** extension.
2. Right-click `index.html` → **Open with Live Server**.

## Files
- `index.html` — everything (HTML + CSS + JS in one file)
- `firebase-config.js` — paste your Firebase Web config here to enable saving contact-form submissions to Firestore
- `jicksoooo.jpg` — profile photo
- Site credit: **madhu emmidi**

## Publish on GitHub Pages
1. Create a new GitHub repo and push these files.
2. Repo → **Settings** → **Pages** → Source: `main` / `(root)` → Save.
3. Your site goes live at `https://<your-username>.github.io/<repo>/`.

## Enable the contact form (Firebase Firestore)
1. Create a Firebase project, enable **Firestore Database**.
2. Add a Web app, copy its config into `firebase-config.js`.
3. In Firestore Rules, allow client writes to a `contacts` collection (read restricted to you).
4. Submissions land in the **`contacts`** collection.

## Languages
Header has an **EN / తె** toggle. Preference is remembered.
