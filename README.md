# Gruvbox High Dark theme for ARGVUS

Official ARGVUS Dark theme, `gruvbox-high-dark`, with its Sticky and Float variants.

[![CI](https://github.com/argvus/argvus-theme-gruvbox-high-dark/actions/workflows/ci.yml/badge.svg)](https://github.com/argvus/argvus-theme-gruvbox-high-dark/actions/workflows/ci.yml)
[![Release](https://github.com/argvus/argvus-theme-gruvbox-high-dark/actions/workflows/release.yml/badge.svg)](https://github.com/argvus/argvus-theme-gruvbox-high-dark/actions/workflows/release.yml)
[![License](https://img.shields.io/badge/License-GPL--3.0-blue.svg)](LICENSE)
[![Language: Shell](https://img.shields.io/badge/Shell-POSIX-4EAA25?logo=gnubash&logoColor=white)](https://www.gnu.org/software/bash/)
[![Platform: Arch Linux | Wayland](https://img.shields.io/badge/platform-Arch%20Linux%20%7C%20Wayland-1793D1?logo=archlinux&logoColor=white)](https://archlinux.org/)
[![Pull requests](https://img.shields.io/github/issues-pr/argvus/argvus-theme-gruvbox-high-dark)](https://github.com/argvus/argvus-theme-gruvbox-high-dark/pulls)
[![Issues](https://img.shields.io/github/issues/argvus/argvus-theme-gruvbox-high-dark)](https://github.com/argvus/argvus-theme-gruvbox-high-dark/issues)
[![Last commit](https://img.shields.io/github/last-commit/argvus/argvus-theme-gruvbox-high-dark)](https://github.com/argvus/argvus-theme-gruvbox-high-dark/commits/main)

## Theme identity

| Field | Value |
| --- | --- |
| Theme ID | `gruvbox-high-dark` (Float variant: `gruvbox-high-dark-float`) |
| Display name | Gruvbox High Dark |
| Mode | `dark` |
| Default highlight | `#D79921` |
| GTK color scheme | `prefer-dark` |
| Calendar stylesheet | `gruvbox-high-dark` |
| Package | `argvus-theme-gruvbox-high-dark` |
| Wallpaper | `/usr/share/backgrounds/argvus/abstract/dark/gruvbox-high-abstract-dark.jxl` |

The values above are the ones declared in
`src/usr/share/argvus/appearance/themes.d/gruvbox-high-dark/theme.toml`, the manifest that the
desktop reads. The manifest is the source of truth; this page describes it.

## Installing

The package depends on `argvus` and `argvus-appearance`, so pacman installs them with it.

```sh
sudo pacman -S argvus-theme-gruvbox-high-dark
```

Select the theme in the Control Center (Appearance > Themes), or run
`argvus theme-switch gruvbox-high-dark`.

## Files

The package installs the theme's per-component files under `/usr/share/argvus` (and the
calendar stylesheet under `/etc/argvus/taskbar/calendar/themes`). Each component that
the theme styles has its own directory, listed by `find src -type f` in this repository.

## Development

Validate with `make validate` before building. The design rules are in
[DEVELOPMENT.md](DEVELOPMENT.md); the ARGVUS documentation for themes is in
`argvus/docs/en/user-guide/appearance.md` of the `argvus` repository.

## Contributing and policies

- [CONTRIBUTING.md](https://github.com/argvus/.github/blob/main/CONTRIBUTING.md) — contribution workflow
- [SECURITY.md](https://github.com/argvus/.github/blob/main/SECURITY.md) — private vulnerability reports
- [Code of Conduct](https://github.com/argvus/.github/blob/main/policies/CODE_OF_CONDUCT.md) — community standards
- [AI usage policy](https://github.com/argvus/.github/blob/main/policies/IA_USAGE.md) — rules for AI-assisted contributions

## License

GPL-3.0-only. See [LICENSE](LICENSE).
