# Repository Guidelines

## Project Structure & Module Organization
This repository is documentation-only. Key locations:
- `readme.md`: primary event page with schedules, rules, and registration/submission tables.
- `README_AgentHack_V2.md`: template version with placeholder tokens (e.g., `[REGISTRATION_START_DATE]`) for reuse.
- `.github/ISSUE_TEMPLATE/`: issue templates for registration flows (`register.md`, `registration.md`).

## Build, Test, and Development Commands
No build system or runtime code is present in this checkout (no `package.json`, `Makefile`, or test runner). Work is done by editing Markdown and previewing it locally in your editor. Keep Markdown tables aligned when updating rows.

## Coding Style & Naming Conventions
- Markdown headings should use `#`/`##` with short, direct paragraphs.
- Preserve existing HTML blocks in `readme.md` (tables, images) unless you are intentionally restructuring them.
- Placeholder tokens in `README_AgentHack_V2.md` use `[ALL_CAPS]` patterns; keep names consistent across the file.
- File names are already established; add new docs only if needed and prefer clear, descriptive names.

## Testing Guidelines
There are no automated tests. Validate by:
- Rendering Markdown to ensure tables line up and images/links resolve.
- Checking for broken anchors or malformed HTML tags.

## Commit & Pull Request Guidelines
This workspace does not include Git history, so no commit convention can be inferred. If contributing upstream, use descriptive commits such as `docs: update schedule table` and describe intent in the PR. PRs should:
- List the files changed and the reason.
- Call out any new or updated links.
- Include a screenshot for major layout or table changes.

## Content Update Tips
The registration and submission sections are large, structured tables. Append new entries rather than rewriting existing rows, and avoid editing other participants' information unless explicitly required.
