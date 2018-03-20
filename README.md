![image](https://raw.githubusercontent.com/alexanderjeurissen/sombre.tmux/master/assets/sombre_logo.png)

> The world’s light shines, shine as it will,
> The world will love its darkness still.
> I doubt though when the world’s in hell,
> It will not love its darkness half so well.
> ~ Poem by Richard Crashaw

A tmux colorscheme that predominately uses white, grays, and black.
Looks even more awesome when combined with [lumiere.vim](https://github.com/alexanderjeurissen/lumiere.vim)

![image](https://raw.githubusercontent.com/alexanderjeurissen/sombre.tmux/master/assets/screenshot.png)

### Installation with [Tmux Plugin Manager](https://github.com/tmux-plugins/tpm) (recommended)

Add plugin to the list of TPM plugins in `.tmux.conf`:

    set -g @plugin 'alexanderjeurissen/sombre.tmux'

Hit `prefix + I` to fetch the plugin and source it.

Reload your tmux configuration and the colorscheme should be loaded.

### Manual Installation

Clone the repo:

    $ git clone https://github.com/alexanderjeurissen/sombre.tmux ~/clone/path

Add this line to the bottom of `.tmux.conf`:

    run-shell ~/clone/path/sombre.tmux

Reload TMUX environment:

    # type this in terminal
    $ tmux source-file ~/.tmux.conf
