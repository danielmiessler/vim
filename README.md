# vim
My Vim configuration.

## Steps to install
1. Clone this repo
`git clone https://github.com/Dow-J/vim.git`

2. Symlink my .vimrc file to yours
```
touch ~/.vimrc
ln -sf ~/vim/.vim/vimrc ~/.vimrc
```

3. Download pathogen
```
mkdir -p ~/.vim/autoload ~/.vim/bundle
curl -LSso ~/.vim/autoload/pathogen.vim https://tpo.pe/pathogen.vim
```
