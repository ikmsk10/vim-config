# vim-config

1. Remove simlink *bundle*
2. install apt-vim 
```bash
curl -sL https://raw.githubusercontent.com/egalpin/apt-vim/master/install.sh | sh
```
3. install NerdTree
```bash
apt-vim install -y https://github.com/scrooloose/nerdtree.git
```
4. install Smart Tabs
```bash
apt-vim install -y https://github.com/vim-scripts/Smart-Tabs.git
```
5. Create symlink
```bash
ln -s /path-to-home/.vim/vimrc /path-to-home/.vimrc
```
