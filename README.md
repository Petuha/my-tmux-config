# Установка

```bash
sudo pacman -S tmux
git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm
mkdir -p ~/.config/tmux
cd ~/.config/tmux
git clone https://github.com/Petuha/my-tmux-config .
```

При первом входе установить плагины: `<prefix> + I`

# Бинды

`<prefix>` - `CTRL + SPACE`

`ALT + PageUp/PageDown` - переключение окон
`ALT + Shift + PageUp/PageDown` - двигать текущее окно относительно других окон

`<prefix> + n` - новое окно

`<prefix> + ;` - ввести промт

`<prefix> + c` - переход в copy-mode-vi
