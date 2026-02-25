# dp-next-theme: Quarto extension for DP-Next


[![GitHub
License](https://img.shields.io/github/license/dp-next/dp-next-theme)](https://github.com/dp-next/dp-next-theme/blob/main/LICENSE.md)
[![GitHub
Release](https://img.shields.io/github/v/release/dp-next/dp-next-theme)](https://github.com/dp-next/dp-next-theme/releases/latest)
[![pre-commit.ci
status](https://results.pre-commit.ci/badge/github/dp-next/dp-next-theme/main.svg)](https://results.pre-commit.ci/latest/github/dp-next/dp-next-theme/main)
[![lifecycle](https://lifecycle.r-lib.org/articles/figures/lifecycle-experimental.svg)](https://lifecycle.r-lib.org/articles/stages.html#experimental)
[![Project Status: Active – The project has reached a stable, usable
state and is being actively
developed.](https://www.repostatus.org/badges/latest/active.svg)](https://www.repostatus.org/#active)

This repository contains Quarto shortcodes, embedded extensions, and
style theming that is used by all DP-Next Quarto-based repositories.

## Installing

To install the extension, use:

``` bash
quarto add dp-next/dp-next-theme
```

This will install the extension under the `_extensions` subdirectory.

To update the `dp-next-theme`, run:

``` bash
quarto update dp-next/dp-next-theme
```

## Using

This extension installs a
[brand.yml](https://posit-dev.github.io/brand-yml/) configuration for
DP-Next.

After installing the extension, add the below yaml key-value pair to the
`_quarto.yml` file:

``` yaml
format: dp-next-theme-html
```

Or for project-level configurations:

``` yaml
project:
  type: dp-next-theme
```

## Example

Here is the source code for a minimal example:
[example.qmd](example.qmd).

See this repository’s
[`_quarto.yml`](https://github.com/dp-next/dp-next-theme/blob/main/_quarto.yml)
files for examples of how you would use this extension.

## Contributing

Check out our [contributing document](CONTRIBUTING.md) for information
on how to contribute to the project, including how to set up your
development environment.

Please note that this project is released with a [Contributor Code of
Conduct](https://github.com/dp-next/.github/blob/main/CODE_OF_CONDUCT.md).
By participating in this project you agree to abide by its terms.

## Licensing

This project is licensed under the [MIT
License](https://github.com/dp-next/dp-next-theme/blob/main/LICENSE.md).

## Changelog

For a list of changes, see our [changelog](CHANGELOG.md) page.
