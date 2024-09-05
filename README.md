# Sample project

This repository serves as a template for any kind of project. It includes
pre-configured settings for [EditorConfig][editorconfig],
[`commitlint`][commitlint] and [`markdownlint`][markdownlint]. The latter
ensures that the [README.md](/README.md) file adheres to linting standards.
There is also a [Lefthook][lefthook] configuration file that enables the
installation of [Git hooks][git-hooks] that automatically run the checks
performed by these tools during each commit.

It also features continuous integration (CI) configurations for
[GitHub Actions][github-actions], which automatically execute these checks,
along with others, on every push or pull request.

## Usage

To use this repository as a template, it is recommended to follow its
[setup wizard][setup-wizard] to automatically apply all necessary configurations
to the new repository.

## Unlicense

This source code is free and available under [no license][unlicense]. Please
read the full [unlicensing statement](/UNLICENSE.txt) for more information.

<!-- Links -->

[commitlint]: https://commitlint.js.org
[editorconfig]: https://editorconfig.org
[git-hooks]: https://git-scm.com/book/en/v2/Customizing-Git-Git-Hooks
[github-actions]: https://github.com/features/actions
[lefthook]: https://github.com/evilmartians/lefthook
[markdownlint]: https://www.npmjs.com/package/markdownlint
[setup-wizard]: https://gist.github.com/marlondecol/1b8b3980d2b0dd7612ed3a73c3eb6083
[unlicense]: https://unlicense.org
