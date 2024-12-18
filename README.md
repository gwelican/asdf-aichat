<div align="center">

# asdf-aichat [![Build](https://github.com/gwelican/asdf-aichat/actions/workflows/build.yml/badge.svg)](https://github.com/gwelican/asdf-aichat/actions/workflows/build.yml) [![Lint](https://github.com/gwelican/asdf-aichat/actions/workflows/lint.yml/badge.svg)](https://github.com/gwelican/asdf-aichat/actions/workflows/lint.yml)

[aichat](https://github.com/sigoden/aichat) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add aichat
# or
asdf plugin add aichat https://github.com/gwelican/asdf-aichat.git
```

aichat:

```shell
# Show all installable versions
asdf list-all aichat

# Install specific version
asdf install aichat latest

# Set a version globally (on your ~/.tool-versions file)
asdf global aichat latest

# Now aichat commands are available
aichat --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/gwelican/asdf-aichat/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Peter Varsanyi](https://github.com/gwelican/)
