# Changelog

## [0.1.1] - 2026-11-04

### Added

- Explicit WHY lifecycle rules and an append-only recorder for user-stated or adopted
  reasons.
- A Sample test that simulates user input and verifies the Sample WHY file is updated
  without changing its template content. Simulated input covers multiline reasons and
  missing, empty, or whitespace-only WHY files; updater tests cover delivery to existing
  Base projects.

## [0.1.0] - 2026-11-02

### Added

- Initial HADA Base operating contract and repository boundaries.
- Canonical Base version and file-ownership manifest.
- Repository contract validator and version consistency checks.
- Offline three-tree update planner with safe apply, conflict preservation, and evidence reports.
- Optional, disabled-by-default local conversation export importer with hash deduplication.
