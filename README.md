<div align="center">

# asdf-werf [![Build](https://github.com/MxNxPx/asdf-werf/actions/workflows/build.yml/badge.svg)](https://github.com/MxNxPx/asdf-werf/actions/workflows/build.yml) [![Lint](https://github.com/MxNxPx/asdf-werf/actions/workflows/lint.yml/badge.svg)](https://github.com/MxNxPx/asdf-werf/actions/workflows/lint.yml)


[werf](https://werf.io/documentation/) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add werf
# or
asdf plugin add werf https://github.com/MxNxPx/asdf-werf.git
```

werf:

```shell
# Show all installable versions
asdf list-all werf

# Install specific version
asdf install werf latest

# Set a version globally (on your ~/.tool-versions file)
asdf global werf latest

# Now werf commands are available
werf --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/MxNxPx/asdf-werf/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [MxNxPx](https://github.com/MxNxPx/)
