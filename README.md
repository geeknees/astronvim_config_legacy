# astronvim_config

https://astronvim.com/

## 🛠️ Installation

#### Make a backup of your current nvim and shared folder

```shell
mv ~/.config/nvim ~/.config/nvim.bak
mv ~/.local/share/nvim ~/.local/share/nvim.bak
```

#### Clone the repository

```shell
git clone https://github.com/AstroNvim/AstroNvim ~/.config/nvim
nvim +PackerSync
```

#### User Configuration

```
git clone git@github.com:geeknees/astronvim_config.git ~/.config/nvim/lua/user
```

#### Initialize AstroNvim

```
nvim  --headless -c 'autocmd User PackerComplete quitall'
```
