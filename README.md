<div align="center">

# asdf-clusteradm [![Build](https://github.com/herberton/asdf-clusteradm/actions/workflows/build.yml/badge.svg)](https://github.com/herberton/asdf-clusteradm/actions/workflows/build.yml) [![Lint](https://github.com/herberton/asdf-clusteradm/actions/workflows/lint.yml/badge.svg)](https://github.com/herberton/asdf-clusteradm/actions/workflows/lint.yml)

[clusteradm](https://github.com/open-cluster-management-io/clusteradm) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

**TODO: adapt this section**

- `bash`, `curl`, `tar`, and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).

# Install

Plugin:

```shell
asdf plugin add clusteradm
# or
asdf plugin add clusteradm https://github.com/herberton/asdf-clusteradm.git
```

clusteradm:

```shell
# Show all installable versions
asdf list-all clusteradm

# Install specific version
asdf install clusteradm latest

# Set a version globally (on your ~/.tool-versions file)
asdf global clusteradm latest

# Now clusteradm commands are available
clusteradm version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/herberton/asdf-clusteradm/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Herberton Candido Souza](https://github.com/herberton/)
