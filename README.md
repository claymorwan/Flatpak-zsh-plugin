# Flatpak plugin

This plugin adds a few aliases for [Flatpak](https://docs.flatpak.org/en/latest/using-flatpak.html).

To use it, add `flatpak` to the plugins array in your zshrc file:
```zsh
plugins=(... archlinux)
```
## Aliases

| Alias        | Command                                | Description                                                      |
|--------------|----------------------------------------|------------------------------------------------------------------|
| flatin       | `flatpak install`                      | Install an application or runtime                                |
| flatre       | `flatpak uninstall`                    | Uninstall an application or runtime                              |
| flatupg      | `flatpak update`                       | Update an application or runtime                                 |
| flatlist     | `flatpak list`                         | List installed applications and/or runtimes                      |
| flatrun      | `flatpak run`                          | Run an application or open a shell in a runtime                  |
| flatrep      | `flatpak repair`                       | Repair a flatpak installation                                    |
| flatkill     | `flatpak kill`                         | Stop a running application                                       |

# Credit
- Made by [claymorwan](https://github.com/claymorwan)
- Inspired by the [Arch Linux plugin](https://github.com/ohmyzsh/ohmyzsh/tree/master/plugins/archlinux)