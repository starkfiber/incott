# Incott

Legacy news application source in the [Stark Fiber Enterprise](https://starkfiber.my) portfolio.

## Repository layout

- `news_app/` — Flutter client. Its manifest declares Dart >=2.12 and <3.0, Firebase integrations, localisation, image/media libraries and advertising integrations.
- `news_admin/` — companion administration directory; its setup has not yet been qualified in this review.

## Maintenance status

The existing dependency constraints belong to an older Flutter/Dart generation. A modern toolchain upgrade needs a baseline and migration work; it is not safe to imply that changing version constraints alone makes the application current.

## Upgrade priorities

1. Identify the original runtime, lockfiles and required service configuration. Document placeholders, not real credentials.
2. Confirm source/template and bundled-asset licences before redistribution or commercial relaunch.
3. Reproduce news reading, authentication, localisation and media playback in a development environment with synthetic content.
4. Migrate Flutter/Dart and Firebase dependencies in stages; retest login, offline/error states and notification consent.
5. Review administrator authorisation, backend rules, analytics and advertising consent before public deployment.

No live Firebase configuration, customer content or mobile release was changed during this repository review.
