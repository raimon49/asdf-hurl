<div align="center">

# asdf-hurl [![Build](https://github.com/raimon49/asdf-hurl/actions/workflows/build.yml/badge.svg)](https://github.com/raimon49/asdf-hurl/actions/workflows/build.yml) [![Lint](https://github.com/raimon49/asdf-hurl/actions/workflows/lint.yml/badge.svg)](https://github.com/raimon49/asdf-hurl/actions/workflows/lint.yml)


[hurl](https://github.com/raimon49/asdf-hurl) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add hurl
# or
asdf plugin add hurl https://github.com/raimon49/asdf-hurl.git
```

hurl:

```shell
# Show all installable versions
asdf list-all hurl

# Install specific version
asdf install hurl latest

# Set a version globally (on your ~/.tool-versions file)
asdf global hurl latest

# Now hurl commands are available
hurl --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/raimon49/asdf-hurl/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [raimon](https://github.com/raimon49/)
