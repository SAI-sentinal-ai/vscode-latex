# vscode-latex

Harry's quiet, minimal VS Code setup for writing LaTeX (LaTeX Workshop, monochrome theme, Adobe Caslon or Cormorant Garamond), plus a sample article to try it on. Public repo, for his own writing and anyone who wants the same.
Business: personal. Background: the general-context skill; no systems notes in the hub (it is listed in GENERAL/sources.md as a personal repo).

Start by reading STATUS.md (where things stand) and DECISIONS.md (why things are the way they are).

## Stack
- VS Code settings in `.vscode/` (`settings.json`, plus ltex dictionaries and disabled-rule lists, UK/Oxford spelling).
- LaTeX sample: `article.tex`, `bibliography.bib`, `naturetex.sty`; compiled by the LaTeX Workshop extension.

## Run it
- Nothing to install or build. Open the folder in VS Code with the LaTeX Workshop extension; build the PDF from the extension.
- To reuse the settings, copy `.vscode/` into the folder that holds your `.tex` file.

## Deploy
Nowhere. Pushing only updates GitHub.

## Secrets and config
None. The repo is public: never commit anything private.

## Layout
- `.vscode/`: the settings (the point of the repo).
- `article.tex`, `bibliography.bib`, `naturetex.sty`, `images/`: the sample document. `article.pdf` is committed output.
- `README.md`: install steps for the extension, theme and fonts.
- `.claude/settings.json`: turns off claude.ai connectors for sessions in this repo.
- `.gitignore` excludes LaTeX build files (aux, log, fls, synctex).

## Watch out for
- Settings are deliberately plain (hidden gutters, error colours turned off); do not "fix" them.
- If `.vscode/settings.json` changes, update the README steps in the same commit.

## Related
- Harry's other LaTeX work (the OCIA booklet) lives elsewhere. TODO(Harry): where, so it can be linked here.
