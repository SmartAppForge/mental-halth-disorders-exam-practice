# Mental Health Disorders Exam Practice — v1.0

A standalone, responsive HTML/CSS/JavaScript practice app for nursing students.

## Files
- `index.html` — app interface
- `styles.css` — responsive layout and results-page offer banner
- `config.js` — app settings, 70% Level 2 threshold, and four supplied Gumroad URLs
- `questions.js` — the original 40 questions and answer keys from the supplied project
- `app.js` — navigation, scoring, answer review, sharing, offers, and level unlocking
- `TEST-CHECKLIST.md` — manual validation checklist
- `TEST-RESULTS.md` — automated checks and tests still outstanding

## Run locally
Open `index.html` in a modern browser, or serve this folder using a local static HTTP server.

## Publish on GitHub Pages
1. Create a new repository named `mental-halth-disorders-exam-practice`.
2. Upload all eight files to the repository root (not a nested project folder).
3. Commit the changes.
4. In **Settings → Pages**, select the deployment source/branch and root folder as appropriate.
5. Wait for deployment and test the published URL.

## Level 2 behavior
Level 2 is available after a Level 1 score at or above the configured `minimumPercent` (70% by default). Below the threshold, the results-page action becomes **Retry Level 1**. The threshold is configured in `config.js`. Any local-storage based progress is device/browser-specific and is not server-verified.

## Offers
The four supplied URLs are preserved in `config.js`. The colored offer banner is displayed on the results screen, not during Home or Quiz.

No repository was created, modified, or published as part of generating this archive.
