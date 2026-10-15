# tesserea-legal

Tesserea's one public page: support questions, the privacy policy and the terms of use, in a
single self-contained `index.html` (English only, like the app). Kept outside the app repository on
purpose.

## Publishing

Public repository `scott3450/tesserea-legal` (only this page, never app code — owner's rule,
1 Oct 2026). GitHub ▸ Settings ▸ Pages ▸ Deploy from a branch ▸ `main`, `/ (root)`.
Edit here, commit, `git push`; Pages redeploys on its own.

| Where | URL |
|---|---|
| App Store Connect ▸ Support URL | `https://scott3450.github.io/tesserea-legal/` |
| App Store Connect ▸ Privacy Policy URL | `https://scott3450.github.io/tesserea-legal/#privacy` |
| Description ▸ Terms of Use line, subscription screen | `https://scott3450.github.io/tesserea-legal/#terms` |

The app links the same addresses (`Links` in `Sectile/app/Tesserea/SettingsView.swift`).

## Rules

- No outbound links except Apple's standard EULA (the Terms of Use rest on it); no
  `FUNDING.yml`, no Sponsor button (guidelines 2.3.10, 3.1.1).
- Keep the URLs stable after submission.
- The text must agree with the App Privacy label: "Data Not Collected". Subscriptions handled
  by Apple do not change that answer.
- When the subscription's scope or periods change, update the support answer, Terms ▸
  Subscription and both dates.
