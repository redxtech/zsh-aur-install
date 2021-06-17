# aur-install
> aur-install is a zsh plugin that provides a function to install a package from the AUR.

## Installing

### zinit
Add this to your zinit config (.zshrc):
```zsh
zinit light redxtech/zsh-aur-install

# it also works with turbo mode:
zinit ice wait lucid
zinit load redxtech/zsh-aur-install
```

### oh-my-zsh
Install it with your favourite zsh package manager, or clone it directly to your
`$ZSH_CUSTOM/plugins` directory with git, and add `zsh-aur-install` to the plugins
array in your `.zshrc` file:

```zsh
plugins=(... zsh-aur-install)
```

## Usage
`aur-install` is very easy to use, simply run the command with the name of the
package you wish to install as the only arg:

```zsh
aur-install package
```

## Author
**aur-install** © [Gabe Dunn](https://github.com/redxtech), Released under the [MIT](./license.md) License.

