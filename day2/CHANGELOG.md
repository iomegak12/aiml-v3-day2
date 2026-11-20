# Changelog

All notable changes to this project are documented here.
Format: [Keep a Changelog](https://keepachangelog.com/en/1.1.0/) · Versioning: [SemVer](https://semver.org/).

## [Unreleased]

## [0.2.0] - 2026-11-20

### Added

- `netcore_tac` package (`src/`): `config`, `generator`, `quality_issues`, `dataset`
- `scripts/generate_tickets.py` — CLI with `--n`, `--seed`, `--output`
- Synthetic NetCore TAC tickets with outliers, negative values, missing values, inconsistent labels and near duplicates
- Unit tests: `test_generator.py`, `test_quality_issues.py`, `test_dataset.py`

### Changed

- `pyproject.toml` — `uv_build` build backend so `netcore_tac` is importable
- Removed `.gitkeep` from `src/`, `scripts/`, `tests/` (no longer empty)

## [0.1.0] - 2026-11-20

### Added

- `AGENTS.md` — shared AI assistant rules
- `CLAUDE.md` and `.github/copilot-instructions.md` — pointers to `AGENTS.md`
- Standard files: `.gitignore`, `README.md`, `TROUBLESHOOTING.md`, `CONTRIBUTING.md`, `CHANGELOG.md`, `SECURITY.md`, `CODE_OF_CONDUCT.md`, `LICENSE` (MIT)
- Folder scaffold with `.gitkeep`: `src/`, `scripts/`, `tests/`, `data/`
- `pytest` as a dev dependency
