# vscode_dotfiles

> [!IMPORTANT]
> Windows側にneovimをインストールしておくこと
> 2025/06/28のstable release
> https://github.com/neovim/neovim/releases/latest/download/nvim-win64.msi

Windows
/mnt/c/Users/xxx/AppData/Roaming/Code/User/settings.json

wsl
code --list-extensions > extensions.txt


Recovery
コピーして上書きかな。Windowsだし
拡張機能のインストールは下記
cat extensions.txt | xargs -n1 code --install-extension