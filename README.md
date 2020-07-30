# Vim_Configuration
This project is the vim configuration


### 1. Need to install the following software

```c
sudo apt-get install ctags

sudo apt-get install cscope

sudo apt-get install build-essential cmake python3-dev
```

### 2. Install Vundle
```c
git clone https://github.com/VundleVim/Vundle.vim.git  ~/.vim/bundle/Vundle.vim
```

### 3. Copy all plugin package to the target directory(**~/.vim/bundle/**)

### 4. YouCompleteMe compile
```c
cd ~/.vim/bundle/YouCompleteMe
./install.py --clang-completer
```
After compile these files, must do some configuration for this plugin
```c
cp ~/.vim/bundle/YouCompleteMe/third_party/ycmd/examples/.ycm_extra_conf.py  ~/.vim/
```
