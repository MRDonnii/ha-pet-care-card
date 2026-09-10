# Changelog

## [0.2.0] - 2026-09-10

### Added

- Each meal can expose a daily `skip` helper with a confirmed **Spring over**
  action and a **Fortryd** action.
- Skipped meals are marked separately and excluded from today's completion
  count and next-meal calculation.

### Changed

- The live Fie setup removes skipped meals from the Aqara feeder schedule and
  restores the normal recurring schedule automatically after midnight.
