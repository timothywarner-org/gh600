# Changelog

All notable changes to this course companion repository are tracked here. This project follows [Keep a Changelog](https://keepachangelog.com/en/1.1.0/) and uses [Semantic Versioning](https://semver.org/) loosely, scoped to course content rather than software.

## [Unreleased]

### Added (2026-11-14, scaffold)
- README with the course outline, exam facts, skills measured, setup, and study approach.
- `lessons/`: one folder per lesson. Each README carries the lesson title and learning objectives word for word from the course outline, the study guide skills each objective serves, setup notes, and GitHub Docs links. Each `demos/` page is ready for that lesson's lab files.
- `docs/exam-objectives.md`: every skill in the Exam GH-600 study guide (last updated 2026-05-13) mapped to the lessons that teach it, with a self-rating column.
- `docs/resources.md`: GitHub Docs and Microsoft Learn links by exam domain, checked November 14, 2026.
- `docs/study-plan-template.md`: 30-, 60-, and 90-day schedules.
- `lab/README.md`: what the lab will hold, plus the accounts and tools you can set up now.
- `demos/README.md`: the home for demo material that spans more than one lesson.
- CONTRIBUTING.md, NOTICE.md, and issue and pull request templates.

### Changed (2026-11-14)
- `.gitignore` keeps its Python rules and adds secrets, IDE and OS noise, Node, and a local-only folder for instructor files.

### Notes
- Lab files land lesson by lesson, as each lesson publishes.
