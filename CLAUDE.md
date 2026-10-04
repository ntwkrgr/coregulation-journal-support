# CLAUDE.md

Public support repo for the Coregulation Journal iOS app. Docs only — no code, build, or tests.

## Files
- `README.md`: public app overview, features, requirements, support instructions. Prose follows Chas's voice.
- `PRIVACY.md`: privacy policy linked from the App Store listing.

## Source of truth
- App code lives in `ntwkrgr/coregulation-journal-app`. Derive README features/version from that repo's `README.md`, `TODO.md`, and `MARKETING_VERSION` in `CoregulationJournal.xcodeproj/project.pbxproj` (app target).
- `PRIVACY.md` mirrors the app repo's `PRIVACY.md`. When the policy content changes, copy it over and bump the effective date here to the release date.

## Conventions
- Bump "Current version" in `README.md` with each App Store release.
- Issues are public: keep the README warning against posting journal data or child info.
