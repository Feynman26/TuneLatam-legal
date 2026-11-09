# TuneLatam — Legal website

Public, static legal website for the TuneLatam Android application.

This repository contains no application source code, user data, analytics, backend credentials, or secrets.

## Public pages

- Terms: https://feynman26.github.io/TuneLatam-legal/terms/
- Privacy: https://feynman26.github.io/TuneLatam-legal/privacy/
- Ratings-account deletion: https://feynman26.github.io/TuneLatam-legal/account-deletion/

Each page also includes Spanish (es) and Portuguese (pt) versions.

## Deployment

GitHub Pages: Settings → Pages → Deploy from a branch → main → /(root) → Save.

## Release-owner checklist

Before final Play submission:
- Verify Pages is enabled and all links return HTTPS 200 without authentication.
- Published public support email: `tunelatam.support@gmail.com`. Verify a real inbound email/reply from an independent sender and monitor the inbox regularly; publishing a mailto link does not itself prove deliverability. Align Google Play's public contact with this address.
- Test the public account-deletion email request from a browser without the app, verify account ownership securely, record request processing, and validate the actual Supabase ratings-account deletion flow before production release.
- Review the terms, privacy and Data Safety against the final configured Android AAB and the applicable law.
- Keep all translated pages consistent when app behavior changes.

The privacy policy and terms are aligned with the planned freemium launch contract: the Tuner remains free; an eligible 7-day (7 × 24-hour) in-app Preview starts on first Premium capability use and does not require payment or auto-convert; subscriptions (monthly, quarterly, annual) are purchased separately through Google Play. These public pages describe planned commercial behavior, not evidence that production billing is already active. Verify final SDK/data flows, owner support contact, public deletion request channel, and legal/Data Safety review before commercial release.
