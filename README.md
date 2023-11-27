# asdf-trufflehog

![CI](https://github.com/fartbagxp/asdf-trufflehog/workflows/CI/badge.svg)
![Lint](https://github.com/fartbagxp/asdf-trufflehog/workflows/Lint/badge.svg)
[![License](https://img.shields.io/badge/license-MIT-blue)](https://choosealicense.com/licenses/mit/)
[![Doc](https://img.shields.io/badge/Doc-asdf-blue)](https://asdf-vm.com/)

This is a [trufflehog](https://github.com/trufflesecurity/trufflehog) plugin for the [asdf version manager](https://asdf-vm.com/).

## Contents

- [Plugin Dependencies](#plugin-dependencies)
- [Install](#install)
- [License](#license)

## Plugin Dependencies

- `curl` - for trufflehog downloads from upstream releases

## Install

Plugin:

```bash
asdf plugin-add trufflehog https://github.com/fartbagxp/asdf-trufflehog
```

trufflehog:

```bash
# Show all installable versions
asdf list-all trufflehog

# Install specific version
asdf install trufflehog latest

# Set a version globally (in your ~/.tool-versions file)
asdf global trufflehog latest

# Run trufflehog
trufflehog --version
> trufflehog 3.63.1
[...]
```

## Uninstall

```bash
asdf plugin remove trufflehog
```

## License

See [LICENSE](LICENSE).
