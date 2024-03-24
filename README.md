<div align="center">

# asdf-licenseplist [![Build](https://github.com/protothomasdev/asdf-licenseplist/actions/workflows/build.yml/badge.svg)](https://github.com/protothomasdev/asdf-licenseplist/actions/workflows/build.yml) [![Lint](https://github.com/protothomasdev/asdf-licenseplist/actions/workflows/lint.yml/badge.svg)](https://github.com/protothomasdev/asdf-licenseplist/actions/workflows/lint.yml)

[licenseplist](https://github.com/mono0926/LicensePlist) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add licenseplist
# or
asdf plugin add licenseplist https://github.com/protothomasdev/asdf-licenseplist.git
```

licenseplist:

```shell
# Show all installable versions
asdf list-all licenseplist

# Install specific version
asdf install licenseplist latest

# Set a version globally (on your ~/.tool-versions file)
asdf global licenseplist latest

# Now licenseplist commands are available
license-plist --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/protothomasdev/asdf-licenseplist/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Thomas Meyer](https://github.com/protothomasdev/)
