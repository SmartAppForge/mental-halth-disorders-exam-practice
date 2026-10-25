# Test checklist

## Automated checks
- [ ] JavaScript syntax check for `config.js`, `questions.js`, and `app.js`
- [ ] Exactly 40 unique questions, q1–q40
- [ ] 20 questions per level; four options and a valid answer key per question
- [ ] Four distinct HTTPS commercial URLs

## Browser checks after deployment
- [ ] Home screen loads and starts Level 1
- [ ] One answer per question is selected and saved
- [ ] Previous/Next navigation and progress indicator work
- [ ] Level 1 score is correct for known answer combinations
- [ ] Below 70%, results action says Retry Level 1 and restarts Level 1
- [ ] At or above 70%, results action starts Level 2
- [ ] Level 2 score and answer review work
- [ ] Sharing works or fallback is offered
- [ ] Commercial banner appears on Results only, not Home or Quiz
- [ ] Each offer button opens the matching supplied Gumroad page
- [ ] Layout is usable on desktop and mobile
