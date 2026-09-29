# Changelog

All notable changes to this project are documented here. The project follows [Semantic Versioning](https://semver.org).

## 0.1.1

- Data script rejects placeholder years where January 1 is not a holiday (isdayoff.ru returns such data for unpublished years)
- Official 2026 norms added to tests; all years 2013–2026 checked against the source statistics
- README describes the yearly update as it works: a weekly check opens a pull request, the release follows a manual check

## 0.1.0

- Russian production calendar for 2013–2026: workdays, public holidays, transferred days off, shortened pre-holiday days and paid non-working days by presidential decree
- `isWorkday`, `dayKind`, `addWorkdays`, `workdaysBetween`, `nextWorkday`, `previousWorkday`, `days`, `stats` with working-hour norms
