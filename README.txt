DEBT MONITOR V2 — ANDROID PWA
Included: index.html, manifest.json, sw.js.

INSTALL ON ANDROID
1. Extract this ZIP.
2. Host these files at an HTTPS address (or use localhost for testing).
3. Open the HTTPS address in Chrome on Android.
4. Chrome menu ⋮ → Install app / Add to Home screen.
5. Open Debt Monitor from the home screen.

FEATURES
- Loan and credit card records, editable and prefilled for verification
- EMI/card due-date calendar for the next due occurrence
- Best-effort browser notification request (not guaranteed background alarms)
- Approximate loan interest/payoff calculator
- Snowball vs avalanche debt payoff planner
- Monthly budget and cash-left estimate
- Separate billed, unbilled and minimum due card amounts
- PIN gate, local JSON backup/restore, payment CSV export
- Offline-first caching after first successful HTTPS load

DATA / SAFETY NOTES
Starter figures are historical user-shared values and may be outdated. Confirm against current statements. The IndusInd loan is prefilled with the previously recorded ₹45,041 outstanding, ₹4,828 EMI, and 11 instalments left. Card billed/unbilled split is only a starting estimate and must be verified.
The app stores data in browser localStorage. The PIN is a SHA-256 hash but the underlying records are not encrypted; this PIN is a basic access barrier, not strong security. Anyone with browser storage access may read records. Do not enter card number, CVV, bank PIN, OTP, or passwords.
The app does not connect to banks, calculate official lender amortization, or run a guaranteed background alarm. Use the phone's native Clock/Calendar for reliable reminders.

INSTALL FIX: Upload/replace index.html, manifest.json, and sw.js at repository root, and upload icon-192.png and icon-512.png at the same root level.
