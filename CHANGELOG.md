# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [0.1.2] - 2025-06-07

### Added

- Support [Nerd Fonts](https://www.nerdfonts.com/) to display file-specific icons via a new `--icons` argument.
- Directory names are now displayed in bold for better visibility.

## [0.1.1] - 2025-06-06

### Added
- Initial release of `lstr`.
- Core recursive directory tree walking and printing functionality.
- Colorized output for directories, configurable with the `--color` flag (`always`, `auto`, `never`).
- Control over recursion depth via the `-L` flag.
- Option to display directories only via the `-d` flag.
- Option to show hidden files and directories via the `-a` flag.
- Ability to respect `.gitignore` and other standard ignore files via the `-g` flag.

## [0.1.0] - 2025-06-06

- Initial release.
