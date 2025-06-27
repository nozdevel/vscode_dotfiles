# vscode_dotfiles

Windows側にneovimをインストールしておくこと

Windows
/mnt/c/Users/xxx/AppData/Roaming/Code/User/settings.json

wsl
code --list-extensions > extensions.txt


Recovery
コピーして上書きかな。Windowsだし
拡張機能のインストールは下記
cat extensions.txt | xargs -n1 code --install-extension