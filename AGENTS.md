# Repository Guidelines

## Project Structure & Module Organization
- `char_gave_murder_mystery/` contains the current game canon, organized by numbered modules (world building, murder structure, investigation flow, interviews, appendix). Use the numeric prefixes to preserve reading order.
- `prompts/` contains reusable prompt templates for content generation (evidence, characters, timeline, etc.).
- `old/` stores legacy drafts and PDFs; treat as archival unless a change is explicitly requested.

## Build, Test, and Development Commands
- No build or runtime commands are defined; this repository is documentation and content only.
- Helpful navigation and search commands:
  - `ls char_gave_murder_mystery`
  - `rg "keyword"`

## Coding Style & Naming Conventions
- Write in Markdown with clear headings, short paragraphs, and consistent tables/lists.
- Preserve bilingual content (English/Marathi) and existing formatting choices.
- Filenames use numeric prefixes and snake_case (e.g., `05_INTERVIEWS/PHASE_1/01_constable_patil_report_t3.md`). Keep numbering stable when adding files.

## Testing Guidelines
- No automated tests or linting are configured.
- Manually verify continuity (names, timeline references, phase numbering) and check any paths you reference.

## Commit & Pull Request Guidelines
- Commit messages use short, sentence‑style summaries (e.g., “Finalize game materials…”, “Add PDF versions…”).
- PRs should describe the narrative change, affected phases, and any canon‑impacting details. Include screenshots if you change PDFs or add images.

## Content Safety & Consistency
- Treat `char_gave_murder_mystery/00_MASTER_DOCUMENT.md` as the source of truth for canon; update it when changes affect core facts.
- Avoid retroactive edits in `old/` unless the goal is historical correction or archiving.
