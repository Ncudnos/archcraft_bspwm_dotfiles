# archcraft_bspwm_dotfiles

## Note:

```bash

mv zshrc .zshrc && mv .zshrc ~ && sudo rm -rf /etc/profile && sudo mv profile /etc/

```

- Delete all other files and folders in `~/.config/bspwm`.

- This next step does not include `polybar` folder:

```bash

mv * ~/.config/bspwm && sudo rm -rf ~/.config/bspwm/themes/default

```

- This step will setup `polybar`

```bash

mv polybar ~/.config/bspwm/themes

```


