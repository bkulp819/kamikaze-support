# Kamikaze’s Workout Timer — support site

Public support and privacy pages for Kamikaze’s Workout Timer. This repository contains only the website, not the iOS app source.

- Support: https://bkulp819.github.io/kamikaze-support/
- Privacy: https://bkulp819.github.io/kamikaze-support/privacy/
- Contact: kamikazetimer@gmail.com

## Publish

GitHub Pages publishes the `/docs` folder on `main`. Edit the HTML or CSS, commit, and push. There are no dependencies, build steps, analytics scripts, external fonts, or contact forms.

## Privacy policy maintenance

The policy describes local workout storage, user-initiated file sharing, support email, Apple-provided reports, GitHub Pages hosting, and the app’s anonymous TelemetryDeck analytics. The analytics section lists the events and parameters the app sends; the source of truth is `Sources/WorkoutCore/AnalyticsEvent.swift` in the app repository, plus the default parameters of the TelemetryDeck Swift SDK. Update this policy and the App Store privacy disclosures whenever those events, the SDK, or the provider’s retention practices change.

The app links to the public support and privacy URLs from its Settings screen; keep those URLs stable. Recheck this policy whenever app behavior, hosting, or support practices change.

## Preview

Run `python3 -m http.server 8765 --directory docs` and visit http://localhost:8765/.
