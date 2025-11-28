# Contributing

Thanks for contributing! This file explains how to propose, edit, and approve documentation changes.

Rules of the road
- Prefer small, focused PRs that update a single page or related set of pages.
- Use clear titles and descriptions in PRs. Link to related issues or RFCs.
- When adding new pages, add them to mkdocs.yml navigation.

How to submit
1. Create a topic branch from main.
2. Add or update documentation under docs/.
3. Run local link checks if possible (mkdocs serve / build).
4. Open a PR and add the relevant reviewers.

Review process
- One technical reviewer + one doc reviewer for major changes.
- Minor edits (typos, formatting) may be merged by maintainers.

Style
- Use plain language, short sections, and examples.
- Use decision logs for architecture decisions (docs/templates/decision_log.md).
- Keep runbooks concise and action-focused.

Document retirement
- Mark outdated pages with a deprecation note and archive into docs/archived/.
