# dotfiles-public
========

Overview
--------

These are the base dotfiles that I start with when I set up a new environment.

#### shell environment

* `.zshrc`
* `.zshrc.local` - not included, explained below

#### git

* `.gitconfig`
* `.gitconfig.local` - not included, explained below

Setup
-----

To set up the dotfiles:

```bash
git clone github.com/ibnufachrizal/dotfiles-public.git
cd dotfiles-public
```

Customize
---------

#### `~/.zshrc.local`

The `~/.zshrc.local` file will be automatically sourced after all the other
`zsh` related files, thus, allowing its content to add to or overwrite the
existing aliases, settings, `PATH`, etc.

#### `~/.gitconfig.local`

Use `~/.gitconfig.local` to store sensitive information such as the `Git`
user credentials, etc.

Screenshots
-----------

|  macOS                         |  Ubuntu                          |
|--------------------------------|----------------------------------|
| ![Setup on macOS][setup macos] | ![Setup on Ubuntu][setup ubuntu] |

See also
--------

* [MacOS Setup Guide][setup macos guide]
* [Ubuntu Setup Guide][setup ubuntu guide]

License
-------

The MIT License (MIT)

[setup macos]: https://raw.github.com/williambelle/dotfiles/master/docs/screenshots/macos.png
[setup ubuntu]: https://raw.github.com/williambelle/dotfiles/master/docs/screenshots/ubuntu.png
[setup macos guide]: https://sourabhbajaj.com/mac-setup/
[setup ubuntu guide]: https://innovativeinnovation.github.io/ubuntu-setup/
