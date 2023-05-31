<div align="center">

# asdf-clj-kondo [![Build](https://github.com/sumbach/asdf-clj-kondo/actions/workflows/build.yml/badge.svg)](https://github.com/sumbach/asdf-clj-kondo/actions/workflows/build.yml) [![Lint](https://github.com/sumbach/asdf-clj-kondo/actions/workflows/lint.yml/badge.svg)](https://github.com/sumbach/asdf-clj-kondo/actions/workflows/lint.yml)


[clj-kondo](https://github.com/clj-kondo/clj-kondo) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add clj-kondo https://github.com/sumbach/asdf-clj-kondo.git
```

clj-kondo:

```shell
# Show all installable versions
asdf list-all clj-kondo

# Install specific version
asdf install clj-kondo latest

# Set a version globally (on your ~/.tool-versions file)
asdf global clj-kondo latest

# Now clj-kondo commands are available
clj-kondo --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/sumbach/asdf-clj-kondo/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Sam Umbach](https://github.com/sumbach/)
