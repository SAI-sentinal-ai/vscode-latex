# Decisions

## 2026-10-31 Turn off claude.ai connectors here
Decision: `.claude/settings.json` sets `disableClaudeAiConnectors`.
Why: Not recorded (commit 07f0cf8). Inferred: nothing in this repo needs them, and they cost tokens at session start.

## 2022-08-04 Settings travel with the document folder
Decision: the settings live in a `.vscode/` folder that is copied next to the `.tex` file, not in VS Code's user settings.
Why: so the writing setup applies only to LaTeX folders and leaves ordinary coding alone (inferred from the README steps).

## 2022-08-04 Hide the editor's clutter
Decision: no line numbers, folding, breadcrumbs, activity bar, status bar, line highlight, indent guides or git gutter marks. Error and warning squiggles are made transparent. Comments and punctuation are pale grey on a monochrome theme.
Why: a quiet, writing-first editor with the usual VS Code clutter removed and softer syntax colours (README).

## 2022-08-04 Write in a book face
Decision: the editor uses Adobe Caslon Pro at size 20, wrapped at 90 columns, with Cormorant Garamond as the free alternative. The sample document uses IM Fell English.
Why: Not recorded beyond the README (inferred: it should read like the printed page).

## 2022-08-04 British spelling checks
Decision: ltex word lists and disabled rules are kept for en-GB in `.vscode/`.
Why: Harry writes in British English (inferred).
