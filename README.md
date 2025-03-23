<div align="center">

# asdf-git-worktree-wrapper [![Build](https://github.com/kedwards/asdf-git-worktree-wrapper/actions/workflows/build.yml/badge.svg)](https://github.com/kedwards/asdf-git-worktree-wrapper/actions/workflows/build.yml) [![Lint](https://github.com/kedwards/asdf-git-worktree-wrapper/actions/workflows/lint.yml/badge.svg)](https://github.com/kedwards/asdf-git-worktree-wrapper/actions/workflows/lint.yml)

[git-worktree-wrapper](https://github.com/kedwards/git-worktree-wrapper) plugin for the [asdf version manager](https://asdf-vm.com) an/or [mise](https://mise.jdx.dev).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`, and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).

# Install

Plugin:

```shell
asdf plugin add git-worktree-wrapper
# or
asdf plugin add git-worktree-wrapper https://github.com/kedwards/asdf-git-worktree-wrapper.git
```

```shell
mise use git-worktree-wrapper
```

git-worktree-wrapper:

```shell
# Show all installable versions
asdf list-all git-worktree-wrapper

# Install specific version
asdf install git-worktree-wrapper latest

# Set a version globally (on your ~/.tool-versions file)
asdf global git-worktree-wrapper latest

# Now git-worktree-wrapper commands are available
git-worktree-wrapper --help
```

Check [asdf](https://github.com/asdf-vm/asdf) or [mise](https://mise.jdx.dev/walkthrough.html#installing-dev-tools) readme for more instructions on how to install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/kedwards/asdf-git-worktree-wrapper/graphs/contributors)!

# License

See [LICENSE](LICENSE) ©
