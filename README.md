# veeship
Fast, advanced and modern starship config.  
See the **[blog post](https://vipau.dev/posts/veeship/)** for screenshots and more details.  

<img src="https://vipau.dev/images/prompt-1.png" />

This config works really well with [zsimple](https://github.com/vipau/zsimple). Try both together with:  
`docker run --rm -it ghcr.io/vipau/zsimple:debian-latest`

## Installation

### Manual install
1. Install [starship](https://starship.rs/) if it's not installed.  
2. Hope your terminal is using a Powerline compatible font. If not, change the prompt or install the fonts.  
3. Copy starship.toml to the starship configuration directory, usually `~/.config/`. Done!

### zsimple
I wrote zsimple to go together with this theme, making the terminal feel modern but fast.  
The zsimple installer can also [install veeship alongside it](https://github.com/vipau/zsimple/tree/main?tab=readme-ov-file#install).  

1. Install [starship](https://starship.rs/) if it's not installed.  
2. Hope your terminal is using a Powerline compatible font. If not, change the prompt or install the fonts.  
3. Install zsimple+veeship:
```bash
git clone --recursive https://github.com/vipau/zsimple.git
cd zsimple
ZSIMPLE_INSTALL_THEME=1 sh install.sh
zsh
```

## Other notes
For non-standard config paths, you can export the STARSHIP_CONFIG variable with the full path to the .toml file.  
More info on the [official starship documentation](https://starship.rs/config/)
