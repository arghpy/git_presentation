# git_presentation

[![Super-Linter](https://github.com/arghpy/git_presentation/actions/workflows/manage_pull_requests.yaml/badge.svg)](https://github.com/marketplace/actions/super-linter)

For starters, install **texlive** using your distro's package manager.

After that, compile the '.tex' file **twice** using the command:

```bash
pdflatex presentation.tex
```

You need to compile it twice in order for the ToC (Table of Contents)
to be displayed in the generated pdf file.
