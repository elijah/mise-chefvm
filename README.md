<div align="center">

# asdf-chefvm [![Build](https://github.com/elijah/asdf-chefvm/actions/workflows/build.yml/badge.svg)](https://github.com/elijah/asdf-chefvm/actions/workflows/build.yml) [![Lint](https://github.com/elijah/asdf-chefvm/actions/workflows/lint.yml/badge.svg)](https://github.com/elijah/asdf-chefvm/actions/workflows/lint.yml)

[chefvm](https://github.com/elijah/mise-chefvm) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add chefvm
# or
asdf plugin add chefvm https://github.com/elijah/asdf-chefvm.git
```

chefvm:

```shell
# Show all installable versions
asdf list-all chefvm

# Install specific version
asdf install chefvm latest

# Set a version globally (on your ~/.tool-versions file)
asdf global chefvm latest

# Now chefvm commands are available
chefvm version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/elijah/asdf-chefvm/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Elijah Wright](https://github.com/elijah/)
