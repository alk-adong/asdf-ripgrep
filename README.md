<div align="center">

# asdf-ripgrep [![Build](https://github.com/alk-adong/asdf-ripgrep/actions/workflows/build.yml/badge.svg)](https://github.com/alk-adong/asdf-ripgrep/actions/workflows/build.yml) [![Lint](https://github.com/alk-adong/asdf-ripgrep/actions/workflows/lint.yml/badge.svg)](https://github.com/alk-adong/asdf-ripgrep/actions/workflows/lint.yml)

[ripgrep](https://github.com/BurntSushi/ripgrep) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add ripgrep
# or
asdf plugin add ripgrep https://github.com/alk-adong/asdf-ripgrep.git
```

ripgrep:

```shell
# Show all installable versions
asdf list-all ripgrep

# Install specific version
asdf install ripgrep latest

# Set a version globally (on your ~/.tool-versions file)
asdf global ripgrep latest

# Now ripgrep commands are available
rg --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/alk-adong/asdf-ripgrep/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Anthony Dong](https://github.com/alk-adong/)
