<div align="center">

# <YOUR TOOL> ![Build Status](<TOOL REPO>/badges/<PRIMARY BRANCH>/pipeline.svg)

[<YOUR TOOL>](<TOOL HOMEPAGE>) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

**TODO: adapt this section**

- `bash`, `curl`, `tar`: and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

# Install

Plugin:

```shell
asdf plugin add <YOUR TOOL>
# or
asdf plugin add <TOOL REPO>.git
```

<YOUR TOOL>:

```shell
# Show all installable versions
asdf list-all <YOUR TOOL>

# Install specific version
asdf install <YOUR TOOL> latest

# Set a version globally (on your ~/.tool-versions file)
asdf global <YOUR TOOL> latest

# Now <YOUR TOOL> commands are available
<TOOL CHECK>
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](<TOOL REPO>/graphs/<PRIMARY BRANCH>)!

# License

See [LICENSE](LICENSE) © [<YOUR NAME>](https://gitlab.com/<YOUR GIT USERNAME>/)
