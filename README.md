# Kakoune Selenized

Port of [Selenized] color theme for [Kakoune] text editor.

Ported variants:

- [x] Selenized light
- [ ] Selenized dark
- [x] Selenized black
- [ ] Selenized white

## Screenshot

![light theme](./screenshots/light.png)
![dark theme](./screenshots/dark.png)

## Installation

Only last stable release of Kakoune is supported (see changelog).

### [Plug.kak]

```kak
plug "TeddyDD/kakoune-selenized" domain "GitHub.com" theme
```

### Manual

Copy themes you like to `~/.config/kak/colors/` and load with `:colorscheme`
command.

## Changelog

- 0.1 2019-05-05:
    - **Kakoune v2019.01.20**
- 0.2 2019-06-30:
    - make primary selection brighter in black variant


[Selenized]: https://github.com/jan-warchol/selenized
[Kakoune]: http://kakoune.org/
[Plug.kak]: https://github.com/andreyorst/plug.kak
