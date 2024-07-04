<div align="center">

# asdf-kubeone [![Build](https://github.com/PandaScience/asdf-kubeone/actions/workflows/build.yml/badge.svg)](https://github.com/PandaScience/asdf-kubeone/actions/workflows/build.yml) [![Lint](https://github.com/PandaScience/asdf-kubeone/actions/workflows/lint.yml/badge.svg)](https://github.com/PandaScience/asdf-kubeone/actions/workflows/lint.yml)

[kubeone](https://docs.kubermatic.com/kubeone) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add kubeone
# or
asdf plugin add kubeone https://github.com/PandaScience/asdf-kubeone.git
```

kubeone:

```shell
# Show all installable versions
asdf list-all kubeone

# Install specific version
asdf install kubeone latest

# Set a version globally (on your ~/.tool-versions file)
asdf global kubeone latest

# Now kubeone commands are available
kubeone version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/PandaScience/asdf-kubeone/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [René Wirnata](https://github.com/PandaScience/)
