# GHA Templates

[![GitHub Super-Linter](https://github.com/Spechal/gha-templates/actions/workflows/linting.yml/badge.svg)](https://github.com/marketplace/actions/super-linter)

* build.yml - [reusable workflow](https://docs.github.com/en/actions/learn-github-actions/reusing-workflows) using workflow_call
* build-dynamic.yml - Uses [build.yml@main] to verify the associated reusable workflow
* hello.yml - [reusable workflow](https://docs.github.com/en/actions/learn-github-actions/reusing-workflows) using workflow_call
* hello-dynamic.yml - Uses [hello.yml@main] to verify the associated reusable workflow
* linting.yml - [super-linter](https://github.com/github/super-linter) for linting various languages.
