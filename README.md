<div align="center">

# asdf-bitrise [![Build](https://github.com/gaborszakacs/asdf-bitrise/actions/workflows/build.yml/badge.svg)](https://github.com/gaborszakacs/asdf-bitrise/actions/workflows/build.yml) [![Lint](https://github.com/gaborszakacs/asdf-bitrise/actions/workflows/lint.yml/badge.svg)](https://github.com/gaborszakacs/asdf-bitrise/actions/workflows/lint.yml)


[bitrise](https://github.com/gaborszakacs/bitrise) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Why?](#why)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`: generic POSIX utilities.
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

# Install

Plugin:

```shell
asdf plugin add bitrise
# or
asdf plugin add bitrise https://github.com/gaborszakacs/asdf-bitrise.git
```

bitrise:

```shell
# Show all installable versions
asdf list-all bitrise

# Install specific version
asdf install bitrise latest

# Set a version globally (on your ~/.tool-versions file)
asdf global bitrise latest

# Now bitrise commands are available
bitrise version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/gaborszakacs/asdf-bitrise/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Gabor Szakacs](https://github.com/gaborszakacs/)
