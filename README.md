# Make-Up Clone testing

Manual testing documentation for Make-Up Clone, an online cosmetics store I built with React and TypeScript.

- Site: https://make-up-clone.vercel.app
- App code: https://github.com/ShVira/MakeUpClone

## Files

- `MakeUp_Checklist.xlsx`: 85 checks grouped by area: home page, catalog, product page, search, cart, checkout, account, footer, mobile, browsers, network and security.
- `MakeUp_Test_Cases.xlsx`: 20 test cases for the main flows: cart, delivery price, checkout, search, sign up, log in and mobile menu. Each case has type, test design technique, priority, precondition, steps, test data and expected result.

## What I used

- Test design: equivalence partitioning, boundary values, state transition, error guessing
- Chrome DevTools: device mode (375x812 and 768x1024), network throttling (Slow 3G), Local Storage
- Browsers: Chrome, Safari

## How to use the checklist

Open the file in Google Sheets or Excel. Pick a status for each check (PASSED, FAILED, BLOCKED, ND) and add a note or a bug link in "Links / Notes". The summary at the top counts the statuses automatically. Progress bars in section rows work only in Google Sheets.

## Author

Vira Shkurenko, Junior QA Engineer. [LinkedIn](https://linkedin.com/in/vira-shkurenko)
