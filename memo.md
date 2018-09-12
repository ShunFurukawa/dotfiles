## neovim を インストール
```
brew install neovim
```

## dein.vim install
```
sh ./dotfiles/installer.sh ./.vim/bundles
```

## 設定ファイルのシンボリックリンクを作成
```
ln -s ~/dotfiles/nvim/init.vim ~/.config/nvim/init.vim
ln -s ~/dotfiles/nvim/dein.toml ~/.config/nvim/dein.toml
ln -s ~/dotfiles/nvim/dein_lazy.toml ~/.config/nvim/dein_lazy.toml
```

## fish のシンボリックリンク
```
ln -s ~/dotfiles/fish/config.fish ~/.config/fish/config.fish
```
