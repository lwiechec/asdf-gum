<div align="center">

# asdf-gum [![Build](https://github.com/lwiechec/asdf-gum/actions/workflows/build.yml/badge.svg)](https://github.com/lwiechec/asdf-gum/actions/workflows/build.yml) [![Lint](https://github.com/lwiechec/asdf-gum/actions/workflows/lint.yml/badge.svg)](https://github.com/lwiechec/asdf-gum/actions/workflows/lint.yml)

[gum](https://github.com/charmbracelet/gum) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`: generic POSIX utilities.

# Install

Plugin:

```shell
asdf plugin add gum https://github.com/lwiechec/asdf-gum.git
```

gum:

```shell
# Show all installable versions
asdf list all gum

# Install specific version
asdf install gum latest

# Set a version globally (on your ~/.tool-versions file)
asdf set -u gum latest

# Now gum commands are available
gum --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/lwiechec/asdf-gum/graphs/contributors)!

# Thanks

This repository is adapted from [adsf-babashka](https://github.com/fredZen/asdf-babashka) by
[Frederic Merizen](https://github.com/fredZen).

# License

Distributed under the [Eclipse Public License](LICENSE), the same as `asdf-babashka`.
© [Frederic Merizen](https://github.com/fredZen/)
