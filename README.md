<div align="center">

# asdf-detekt [![Build](https://github.com/mattrussell-sonocent/asdf-detekt/actions/workflows/build.yml/badge.svg)](https://github.com/mattrussell-sonocent/asdf-detekt/actions/workflows/build.yml) [![Lint](https://github.com/mattrussell-sonocent/asdf-detekt/actions/workflows/lint.yml/badge.svg)](https://github.com/mattrussell-sonocent/asdf-detekt/actions/workflows/lint.yml)

[detekt](https://github.com/glean-notes/asdf-detekt) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

**TODO: adapt this section**

- `bash`, `curl`, `tar`: generic POSIX utilities.
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

# Install

Plugin:

```shell
asdf plugin add detekt
# or
asdf plugin add detekt https://github.com/mattrussell-sonocent/asdf-detekt.git
```

detekt:

```shell
# Show all installable versions
asdf list-all detekt

# Install specific version
asdf install detekt latest

# Set a version globally (on your ~/.tool-versions file)
asdf global detekt latest

# Now detekt commands are available
detekt --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/mattrussell-sonocent/asdf-detekt/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Matt Russell](https://github.com/mattrussell-sonocent/)
