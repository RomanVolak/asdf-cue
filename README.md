<div align="center">

# asdf-cue [![Build](https://github.com/RomanVolak/asdf-cue/actions/workflows/build.yml/badge.svg)](https://github.com/RomanVolak/asdf-cue/actions/workflows/build.yml) [![Lint](https://github.com/RomanVolak/asdf-cue/actions/workflows/lint.yml/badge.svg)](https://github.com/RomanVolak/asdf-cue/actions/workflows/lint.yml)

[cue](https://github.com/RomanVolak/asdf-cue) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add cue
# or
asdf plugin add cue https://github.com/RomanVolak/asdf-cue.git
```

cue:

```shell
# Show all installable versions
asdf list-all cue

# Install specific version
asdf install cue latest

# Set a version globally (on your ~/.tool-versions file)
asdf global cue latest

# Now cue commands are available
cue version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/RomanVolak/asdf-cue/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Roman Volák](https://github.com/RomanVolak/)
