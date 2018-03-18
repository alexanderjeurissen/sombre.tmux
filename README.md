# ⚫️ DSombre.tmux

> The world’s light shines, shine as it will,
> The world will love its darkness still.
> I doubt though when the world’s in hell,
> It will not love its darkness half so well.
> ~ Poem by Richard Crashaw

A tmux colorscheme that predominately uses white text on a black background.

![image](https://raw.githubusercontent.com/alexanderjeurissen/tmux-colors-sombre/master/screenshots/screenshot.png)

### Installation with [Tmux Plugin Manager](https://github.com/tmux-plugins/tpm) (recommended)

Add plugin to the list of TPM plugins in `.tmux.conf`:

    set -g @plugin 'alexanderjeurissen/tmux-colors-sombre'

Hit `prefix + I` to fetch the plugin and source it.

Reload your tmux configuration and the colorscheme should be loaded.

### Manual Installation

Clone the repo:

    $ git clone https://github.com/alexanderjeurissen/tmux-colors-sombre ~/clone/path

Add this line to the bottom of `.tmux.conf`:

    run-shell ~/clone/path/tmux_colors_sombre.tmux

Reload TMUX environment:

    # type this in terminal
    $ tmux source-file ~/.tmux.conf
