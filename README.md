Переходим в папку где будем хранить конифигурацию nvim:

```bash
~/.config
```

Скачиваем репозиторий в папку nvim:

```bash
git clone https://github.com/TarhunNyan/nvim-configuration.git ./nvim
```

Устанавливаем [VimPlug](https://github.com/junegunn/vim-plug#neovim). Открываем через nvim файл init.vim. Вызываем внутри vim команды:

```bash
:soure %
:PlugInstall
```
