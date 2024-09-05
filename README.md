# Project Template
Note: (Ctrl+K V) opens a markdown preview side-by-side with the editor in VS Code.

## File Structure
Credit for the general structure of this project goes to Brendan M. Price (https://www.brendanmichaelprice.com/workflow/).

### Code
- `code/build` (data preparation)
- `code/check` (data validation)
- `code/learn` (exploratory analysis)
- `code/libraries` (external libraries used in code)
- `code/share` (public-facing analysis)

### Data
Included in .gitignore. Raw data is stored on the cloud elsewhere (ex: Dropbox, Onedrive) and copied into local directories as needed due to GitHub's file size restrictions. Derived data can be produced using the included code files.
- `data/raw` (data as it was acquired)
- `data/derived` (anything created in the project)

### Output
- `output/learn` (outputs of exploratory analysis)
- `output/share` (outputs of public-facing analysis)

### Paper
LaTeX files and pdfs.

## Setting Up VS Code for R
- https://code.visualstudio.com/docs/languages/r
- https://github.com/REditorSupport/vscode-R
- See Also: Daniel Lüdecke (https://gist.github.com/strengejacke/82e8d7b869bd9f961d12b4091c145b88)

