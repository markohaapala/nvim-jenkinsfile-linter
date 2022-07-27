# nvim-jenkinsfile-linter

**NOTE:** Forked from ckipp01/nvim-jenkinsfile-linter to remove the requirement for
`JENKINS_USER` and `JENKINS_PASSWORD` or `JENKINS_TOKEN` to allow development of
Jenkinsfiles on a local Jenkins installation having no credentials.

A small plugin for Neovim that utilizes the [Jenkins pipeline
linter](https://www.jenkins.io/doc/book/pipeline/development/) to ensure your
Jenkinsfiles are valid before using them.

https://user-images.githubusercontent.com/13974112/147474213-b4a0cfdb-e7c5-420d-89b2-293deb312a27.mov

## Prerequisites

- Neovim >= 0.6
- curl available
- [Plenary.nvim](https://github.com/nvim-lua/plenary.nvim) installed
- Ensure you have `JENKINS_URL` set.

## Installation

```lua
use({'markohaapala/nvim-jenkinsfile-linter', requires = { "nvim-lua/plenary.nvim" } })
```

## Docs

[`:h nvim-jenkinsfile-linter`](https://github.com/markohaapala/nvim-jenkinsfile-linter/blob/main/doc/jenkinsfile-linter.txt)
