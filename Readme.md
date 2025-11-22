# Compile math note 
This repository hosts my LaTeX notes. 
## Features
On every push, it automatically:
- Compiles the .tex files into PDFs
- Saves the generated PDFs as artifacts  
- Performs spell checking 
## LaTeX Compilation 

This repository uses [xu-cheng/latex-action](https://github.com/xu-cheng/latex-action) to automatically compile LaTeX documents on every push.

### Usage
- Push your LaTeX source files to the repository
- The workflow will automatically compile your documents
- Download the generated PDFs on the Actions page

### Local Development
```bash
# Install latexmk (usually included with LaTeX distributions)
latexmk -pdf main.tex
```

## Spell-Checking
This repository uses [check-spelling/check-spelling](https://github.com/marketplace/actions/check-spelling) to automatically perform spell checking every time you push.

## Usage
- See @check-spelling-bot's report on the Actions page
- Add expect words in `expect.txt`