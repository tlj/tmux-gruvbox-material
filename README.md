# Gruvbox Material for Tmux

[Gruvbox Material][gruvbox-material] color scheme configuration for Tmux, forked from [egel/tmux-gruvbox][tmux-gruvbox]

## Installation

### Install manually

The simplest way is just:

> HINT: Always make a backup of your config files before any action.

```bash
cat tmux-gruvbox-dark.conf >> ~/.tmux.conf
```

### Install through [Tmux Plugin Manager](https://github.com/tmux-plugins/tpm)

Add plugin to the list of TPM plugins in `.tmux.conf` and select desired theme

```bash
set -g @plugin 'hasundue/tmux-gruvbox-material'
set -g @gruvbox-material_theme 'dark' # or 'light'
set -g @gruvbox-material_contrast 'medium' # or 'soft' or 'hard'
```

Hit `prefix + I` to fetch the plugin and source it. Your Tmux should be updated with the theme at this point.

## License

GPLv3 - Maciej Sypień

[github-tmux]: https://github.com/tmux/tmux
[github-grovbox]: https://github.com/morhetz/gruvbox
[github-hack]: https://github.com/chrissimpkins/Hack
[tmux-color-solarized]: https://github.com/seebi/tmux-colors-solarized
[tmux-gruvbox]: https://github.com/egel/tmux-gruvbox
[gruvbox-material]: https://github.com/sainnhe/gruvbox-material
