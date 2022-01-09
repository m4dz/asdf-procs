<div align="center">

# asdf-procs ![Build](https://github.com/barolab/asdf-procs/workflows/Build/badge.svg) ![Lint](https://github.com/barolab/asdf-procs/workflows/Lint/badge.svg)

[procs](https://github.com/dalance/procs) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Contents](#contents)
- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)
- [Credits](#credits)

# Dependencies

- `bash`, `curl`, `unzip`.

# Install

Plugin:

```shell
asdf plugin add procs
# or
asdf plugin add procs https://github.com/barolab/asdf-procs.git
```

procs:

```shell
# Show all installable versions
asdf list-all procs

# Install specific version
asdf install procs latest

# Set a version globally (on your ~/.tool-versions file)
asdf global procs latest

# Now procs commands are available
procs --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/barolab/asdf-procs/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Romain Bailly](https://github.com/barolab/)

# Credits

This repository was heavily inspired from [asdf-exa](https://github.com/nyrst/asdf-exa)
