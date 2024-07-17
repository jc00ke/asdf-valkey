<div align="center">

# asdf-valkey [![Build](https://github.com/jc00ke/asdf-valkey/actions/workflows/build.yml/badge.svg)](https://github.com/jc00ke/asdf-valkey/actions/workflows/build.yml) [![Lint](https://github.com/jc00ke/asdf-valkey/actions/workflows/lint.yml/badge.svg)](https://github.com/jc00ke/asdf-valkey/actions/workflows/lint.yml)

[valkey](https://github.com/jc00ke/asdf-valkey) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`, and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).
- MacOS: `gcc`
- Debian/Ubuntu: `linux-headers-$(uname -r) build-essential`

# Install

Plugin:

```shell
asdf plugin add valkey
# or
asdf plugin add valkey https://github.com/jc00ke/asdf-valkey.git
```

valkey:

```shell
# Show all installable versions
asdf list-all valkey

# Install specific version
asdf install valkey latest

# Set a version globally (on your ~/.tool-versions file)
asdf global valkey latest

# Now valkey commands are available
valkey-server --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/jc00ke/asdf-valkey/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Jesse Cooke](https://github.com/jc00ke/)
