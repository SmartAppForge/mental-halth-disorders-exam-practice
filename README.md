# Mental Health DisordersExam Practice — v1.0

A standalone, responsive HTML/CSS/JavaScript educational practice app for GitHub Pages. It uses the 40 questions supplied in the project prompt, preserving their order, wording, answer options, and supplied answer keys. This is independent practice material, not an official examination or endorsement.

## Project identity

- App ID / recommended repository: `mental-halth-disorders-exam-practice` (spelling preserved exactly as supplied)
- Domain: NCLEX and Nursing Exam Practice
- Audience: Mental Health Disorders and Nursing Student
- Interface language: English

## Files

- `index.html` — application structure
- `styles.css` — responsive styling
- `config.js` — app identity, Level 2 unlock threshold, and four commercial links
- `questions.js` — complete 40-question bank
- `app.js` — navigation, answer state, scoring, review, sharing, and unlock logic
- `TEST-CHECKLIST.md` — validation checklist
- `TEST-RESULTS.md` — checks performed and outstanding manual tests

## Run locally

Open `index.html` in a modern browser. For the most representative test of sharing and browser storage, use a local static server or GitHub Pages (native share and clipboard support vary by browser and security context). No build step or package installation is required.

## Level 2 unlock rule

By default, Level 2 unlocks when the user scores at least 70% on Level 1. Change `minimumPercent` in `config.js` to adjust the threshold. The result is stored in browser local storage for this device/browser; this is not server-side verification and can be cleared or changed by the user.

## Commercial links

The four supplied links are configured in `config.js` exactly as provided in the prompt. The app does not independently verify Gumroad product availability or product contents.

## Publish to GitHub Pages

1. Sign in to GitHub and create a **new, separate** repository named `mental-halth-disorders-exam-practice`. Do not reuse or modify another application's repository.
2. Upload all eight project files to the repository root. Confirm `index.html` is at the root, not inside a nested project folder.
3. Open the repository's **Settings → Pages**.
4. Under the build/deployment source, select **Deploy from a branch**, choose the default branch (usually `main`) and the `/ (root)` folder, then save.
5. Wait for GitHub Pages to finish deployment. Open the Pages URL shown in Settings → Pages.
6. Test the published URL on desktop and mobile, including answer selection, scoring, Level 2 unlock, and share fallback.

No repository is created or modified by generating these files.
