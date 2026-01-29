# Repository Guidelines

## Project Structure & Module Organization
- `AICLE.context.md`: Top-level draft context for the AICLE methodology.
- `methodology/`: Core whitepaper content.
  - `methodology/AICLE.md`: Primary normative methodology document.

This repository is documentation-focused; there is no application source tree or test suite at this time.

## Build, Test, and Development Commands
- No build or test scripts are currently defined.
- Work is done directly in Markdown files. Use your editor’s preview to validate formatting.

Example workflow:
- Edit: `methodology/AICLE.md`
- Validate locally: open the Markdown preview in your editor.

## Coding Style & Naming Conventions
- Markdown-first repository. Keep headings hierarchical (`#`, `##`, `###`) and consistent.
- Prefer short paragraphs and bullet lists for scanability.
- Use explicit, normative language for requirements (e.g., MUST/SHOULD/MAY) when defining rules.
- File naming: descriptive, TitleCase or uppercase for key docs (e.g., `AICLE.md`, `AICLE.context.md`).

## Testing Guidelines
- No automated tests or coverage targets are defined.
- Validate changes by checking for:
  - consistent heading levels
  - clear section flow
  - no duplicated content across `AICLE.context.md` and `methodology/AICLE.md` unless intentional

## Commit & Pull Request Guidelines
- No Git history is available in this folder, so no established commit message convention is documented.
- Suggested commit format (if you initialize Git): `docs: <short summary>`
- PRs should include:
  - a concise description of the change
  - the sections/files modified (e.g., `methodology/AICLE.md`)
  - rationale for changes to core principles or constraints

## Version Control Setup (if Git is not initialized)
- Initialize: `git init`
- First commit flow:
  - `git add AICLE.context.md methodology/AICLE.md AGENTS.md`
  - `git commit -m "docs: initialize methodology"`

## Agent-Specific Instructions
- Treat the repository as a normative methodology spec, not a product implementation.
- Preserve the meaning of requirements language when editing (MUST/SHOULD/MAY).
- Keep additions consistent with the AICLE design goals and principles.
