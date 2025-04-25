# koka-textmate-grammar
This repository contains copies of the following files from the original [koka repository](https://github.com/koka-lang/koka):
- The VS Code extension's textmate grammar file
- The `LICENSE` file

These files are kept up-to-date, via a GitHub Action, which runs once a week. This GitHub action inspects the "source" files for changes; if changes are found, then commit the latest changes to this repo.

## Use-Case
The primary use-case of this repository is to provide syntax highlighting within GitHub (via [linguist](https://github.com/github-linguist/linguist)). For more info, please see the [discussion](https://github.com/koka-lang/koka/issues/686).
