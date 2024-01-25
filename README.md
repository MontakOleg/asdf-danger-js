<div align="center">

# asdf-danger-js [![Build](https://github.com/MontakOleg/asdf-danger-js/actions/workflows/build.yml/badge.svg)](https://github.com/MontakOleg/asdf-danger-js/actions/workflows/build.yml) [![Lint](https://github.com/MontakOleg/asdf-danger-js/actions/workflows/lint.yml/badge.svg)](https://github.com/MontakOleg/asdf-danger-js/actions/workflows/lint.yml)

[danger-js](https://danger.systems/js/) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add danger-js
# or
asdf plugin add danger-js https://github.com/MontakOleg/asdf-danger-js.git
```

danger-js:

```shell
# Show all installable versions
asdf list-all danger-js

# Install specific version
asdf install danger-js latest

# Set a version globally (on your ~/.tool-versions file)
asdf global danger-js latest

# Now danger-js commands are available
danger --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/MontakOleg/asdf-danger-js/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Oleg Montak](https://github.com/MontakOleg/)
