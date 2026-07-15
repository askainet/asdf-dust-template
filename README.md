<div align="center">

# asdf-dust [![Build](https://github.com/askainet/asdf-dust/actions/workflows/build.yml/badge.svg)](https://github.com/askainet/asdf-dust/actions/workflows/build.yml) [![Lint](https://github.com/askainet/asdf-dust/actions/workflows/lint.yml/badge.svg)](https://github.com/askainet/asdf-dust/actions/workflows/lint.yml)

[dust](https://github.com/bootandy/dust) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

**TODO: adapt this section**

- `bash`, `curl`, `tar`, and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

# Install

Plugin:

```shell
asdf plugin add dust
# or
asdf plugin add dust https://github.com/askainet/asdf-dust.git
```

dust:

```shell
# Show all installable versions
asdf list-all dust

# Install specific version
asdf install dust latest

# Set a version globally (on your ~/.tool-versions file)
asdf global dust latest

# Now dust commands are available
dust --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/askainet/asdf-dust/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Ivan Lopez](https://github.com/askainet/)
