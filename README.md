<div align="center">

# mise-chefvm [![Build](https://github.com/elijah/mise-chefvm/actions/workflows/build.yml/badge.svg)](https://github.com/elijah/mise-chefvm/actions/workflows/build.yml) [![Lint](https://github.com/elijah/mise-chefvm/actions/workflows/lint.yml/badge.svg)](https://github.com/elijah/mise-chefvm/actions/workflows/lint.yml)

[chefvm](https://github.com/torbrock/chefvm) plugin for the [mise version manager](https://mise.jdx.dev/).

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
mise plugins install chefvm
# or
mise plugins install chefvm https://github.com/elijah/mise-chefvm.git
```

chefvm:

```shell
# Show all installable versions
mise ls-remote chefvm

# Install specific version
mise install chefvm@v1.3.1

# Now chefvm commands are available
chefvm version
```

Check [mise](https://github.com/jdx/mise) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/elijah/mise-chefvm/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Elijah Wright](https://github.com/elijah/)
