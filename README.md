<div align="center">

# asdf-oras [![Build](https://github.com/bodgit/asdf-oras/actions/workflows/build.yml/badge.svg)](https://github.com/bodgit/asdf-oras/actions/workflows/build.yml) [![Lint](https://github.com/bodgit/asdf-oras/actions/workflows/lint.yml/badge.svg)](https://github.com/bodgit/asdf-oras/actions/workflows/lint.yml)

[oras](https://oras.land/docs/category/oras-commands/) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add oras
# or
asdf plugin add oras https://github.com/bodgit/asdf-oras.git
```

oras:

```shell
# Show all installable versions
asdf list-all oras

# Install specific version
asdf install oras latest

# Set a version globally (on your ~/.tool-versions file)
asdf global oras latest

# Now oras commands are available
oras version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/bodgit/asdf-oras/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Matt Dainty](https://github.com/bodgit/)
