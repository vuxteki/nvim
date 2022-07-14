""Vim-Plug""
https://github.com/junegunn/vim-plug
""Terminal syntax""
git clone https://github.com/zsh-users/zsh-syntax-highlighting.git "$HOME/.zsh-syntax-highlighting" --depth 1
echo "source $HOME/.zsh-syntax-highlighting/zsh-syntax-highlighting.zsh" >> "$HOME/.zshrc"
""Update nodejs""
sudo npm cache clean -f
sudo npm i -g n
sudo n latest
""Pass github""
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
