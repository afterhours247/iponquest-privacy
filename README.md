# IponQuest Legal

Public legal, privacy, support, and data-deletion information for IponQuest.

- **Developer:** Afterhours
- **Contact:** iponquest@gmail.com
- **Effective date:** September 30, 2026
- **Repository visibility:** Public

## Public pages

After GitHub Pages is enabled from `main` and the repository root:

- Home: `https://afterhours247.github.io/iponquest-privacy/`
- Privacy Policy: `https://afterhours247.github.io/iponquest-privacy/privacy.html`
- Terms of Use: `https://afterhours247.github.io/iponquest-privacy/terms.html`
- Data Deletion: `https://afterhours247.github.io/iponquest-privacy/data-deletion.html`
- Support: `https://afterhours247.github.io/iponquest-privacy/support.html`

## Current policy scope

The September 30, 2026 revision is aligned to the current IponQuest first-public-release candidate source and covers:

- local-first budgeting with optional Google sign-in through Supabase Auth
- explicit Personal Cloud dataset linking and background synchronization
- Household membership, invitations, shared budgets, and shared goals
- on-device ML Kit receipt OCR with online authorization, quota, and security metadata
- Google Play Plus purchase verification and Play Integrity security checks
- user-controlled CSV/PDF/ZIP exports and Backup V3 JSON
- separate local-data, online-account/cloud, Household, subscription, and exported-file deletion responsibilities
- local App Lock/security state and recurring-bill notification privacy

Optional online features depend on the enabled app build and service configuration. The legal pages avoid claiming that a source-complete feature is deployed or available when it is not enabled.

## Deployment

This is a static, script-free site. Publish it through GitHub Pages using:

- Source: **Deploy from a branch**
- Branch: **main**
- Folder: **/(root)**

The `.nojekyll` file disables Jekyll processing.

## Maintenance

Update the public documents before releasing an IponQuest version that changes data handling, permissions, storage, exports, notifications, accounts, cloud services, Household behavior, receipt processing, advertising, analytics, billing, security/attestation, or backend behavior.

This repository contains public-facing information only. Do not add app source code, credentials, signing material, private Play Console information, tokens, private infrastructure identifiers, raw receipts, or real user financial data.
