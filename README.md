<div align="center">

# asdf-kubeone [![Build](https://github.com/PandaScience/asdf-kubeone/actions/workflows/build.yml/badge.svg)](https://github.com/PandaScience/asdf-kubeone/actions/workflows/build.yml) [![Lint](https://github.com/PandaScience/asdf-kubeone/actions/workflows/lint.yml/badge.svg)](https://github.com/PandaScience/asdf-kubeone/actions/workflows/lint.yml)

[kubeone](https://docs.kubermatic.com/kubeone) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

## Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

## Dependencies

- `bash`, `curl`, `unzip`, and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).

## Installation

### asdf

Install with [asdf](https://github.com/asdf-vm/asdf):

```shell
# Add plugin
asdf plugin add kubeone https://github.com/PandaScience/asdf-kubeone.git

# Show all available versions
asdf list-all kubeone

# Install specific version
asdf install kubeone latest

# Set a version locally ($PWD/.tool-versions)
asdf local kubeone latest

# Set a version globally (~/.tool-versions)
asdf global kubeone latest
```

See [asdf docs](https://asdf-vm.com/manage/versions.html) for full command reference.

### mise

Install with [mise](https://mise.jdx.dev/):

```shell
# Add plugin
mise plugin install kubeone https://github.com/PandaScience/asdf-kubeone.git

# Show all available versions
mise ls-remote kubeone

# Set & install a version locally ($PWD/.mise.toml)
mise use kubeone@latest

# Set & install a version globally (~/.config/mise/config.toml)
mise use -g kubeone@latest
```

See [mise docs](https://mise.jdx.dev/cli/#mise-use-options-tool-version) for full command reference.

## Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/PandaScience/asdf-kubeone/graphs/contributors)!

## License

See [LICENSE](LICENSE) © [René Wirnata](https://github.com/PandaScience/)
