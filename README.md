
![vimplus-logo](https://raw.githubusercontent.com/chxuan/vimplus/master/screenshots/vimplus-logo.png)

An automatic configuration program for vim
===============================================

<p align="center">
    <a href="#build" alt="build"><img src="https://img.shields.io/badge/build-passing-brightgreen.svg" /></a>
    <a href="#安装" alt="platform"><img src="https://img.shields.io/badge/platform-MacOSX%20%7C%20Linux%2064bit%20%7C%20Docker%20%7C%20WSL%20%7C%20Android-brightgreen.svg" /></a>
    <a href="https://github.com/lipiston/vimplus/stargazers" alt="stars"><img src="https://img.shields.io/github/stars/lipiston/vimplus.svg?style=popout&label=stars" /></a>
    <a href="https://github.com/lipiston/vimplus/forks" alt="forks"><img src="https://img.shields.io/github/forks/lipiston/vimplus.svg?style=popout&label=forks" /></a>
    <a href="https://github.com/lipiston/vimplus/graphs/contributors" alt="contributors"><img src="https://img.shields.io/github/contributors/lipiston/vimplus" /></a>
    <a href="https://github.com/lipiston/vimplus/blob/master/LICENSE" alt="lincense"><img src="https://img.shields.io/badge/license-MIT-blue.svg" /></a>
</p>

![main](https://raw.githubusercontent.com/chxuan/vimplus/master/screenshots/main.png)

## 安装

### Mac OS X

#### 安装[HomeBrew]
 
    /usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"

#### 安装vimplus

    git clone https://github.com/lipiston/vimplus.git ~/.vimplus
    cd ~/.vimplus
    ./install.sh
    
注: apline用户请预先安装git,bash: apk add git bash  

#### 设置Nerd Font

为防止vimplus显示乱码，需设置mac终端字体为`Droid Sans Mono Nerd Font`。

#### 更新vimplus

紧跟vimplus的步伐，尝鲜新特性

    ./update.sh
    

### Linux 64-bit

#### 支持以下发行版

<table>
<tr>
<td><a href="https://distrowatch.com/table.php?distribution=ubuntu"><img src="https://distrowatch.com/images/yvzhuwbpy/ubuntu.png"/></a><p align="center"></p></td>
<td><a href="https://distrowatch.com/table.php?distribution=ubuntukylin"><img src="https://distrowatch.com/images/yvzhuwbpy/ubuntukylin.png"/></a><p align="center"></p></td>
<td><a href="https://distrowatch.com/table.php?distribution=debian"><img src="https://distrowatch.com/images/yvzhuwbpy/debian.png"/></a><p align="center"></p></td>
<td><a href="https://distrowatch.com/table.php?distribution=kali"><img src="https://distrowatch.com/images/yvzhuwbpy/kali.png"/></a><p align="center"></p></td>
<td><a href="https://distrowatch.com/table.php?distribution=deepin"><img src="https://distrowatch.com/images/yvzhuwbpy/deepin.png"/></a><p align="center"></p></td>
<td><a href="https://distrowatch.com/table.php?distribution=mint"><img src="https://distrowatch.com/images/yvzhuwbpy/mint.png"/></a><p align="center"></p></td>
<td><a href="https://distrowatch.com/table.php?distribution=elementary"><img src="https://distrowatch.com/images/yvzhuwbpy/elementary.png"/></a><p align="center"></p></td>
<td><a href="https://distrowatch.com/table.php?distribution=centos"><img src="https://distrowatch.com/images/yvzhuwbpy/centos.png"/></a><p align="center"></p></td>
<td><a href="https://distrowatch.com/table.php?distribution=fedora"><img src="https://distrowatch.com/images/yvzhuwbpy/fedora.png"/></a><p align="center"></p></td>
<td><a href="https://distrowatch.com/table.php?distribution=arch"><img src="https://distrowatch.com/images/yvzhuwbpy/arch.png"/></a><p align="center"></p></td>
</tr>
<tr>
<td><a href="https://distrowatch.com/table.php?distribution=manjaro"><img src="https://distrowatch.com/images/yvzhuwbpy/manjaro.png"/></a><p align="center"></p></td>
<td><a href="https://distrowatch.com/table.php?distribution=opensuse"><img src="https://distrowatch.com/images/yvzhuwbpy/opensuse.png"/></a><p align="center"></p></td>
<td><a href="https://distrowatch.com/table.php?distribution=gentoo"><img src="https://distrowatch.com/images/yvzhuwbpy/gentoo.png"/></a><p align="center"></p></td>
<td><a href="https://distrowatch.com/table.php?distribution=parrot"><img src="https://distrowatch.com/images/yvzhuwbpy/parrot.png"/></a><p align="center"></p></td>
<td><a href="https://distrowatch.com/table.php?distribution=raspios"><img src="https://distrowatch.com/images/yvzhuwbpy/raspios.png"/></a><p align="center"></p></td>
<td><a href="https://distrowatch.com/table.php?distribution=freebsd"><img src="https://distrowatch.com/images/yvzhuwbpy/freebsd.png"/></a><p align="center"></p></td>
<td><a href="https://distrowatch.com/table.php?distribution=alpine"><img src="https://distrowatch.com/images/yvzhuwbpy/alpine.png"/></a><p align="center"></p></td>
</tr>
</table>


#### 安装vimplus

    git clone https://github.com/lipiston/vimplus.git ~/.vimplus
    cd ~/.vimplus
    ./install.sh //不加sudo
    
#### 设置Nerd Font

为防止vimplus显示乱码，需设置linux终端字体为`Droid Sans Mono Nerd Font`。
    
#### 更新vimplus

紧跟vimplus的步伐，尝鲜新特性

    ./update.sh


### Android 64-bit([Termux])

#### 安装vimplus

    git clone https://github.com/lipiston/vimplus.git ~/.vimplus
    cd ~/.vimplus
    ./install.sh
    
#### 更新vimplus

紧跟vimplus的步伐，尝鲜新特性

    ./update.sh
    

## 自定义

> * [~/.vimrc]为vimplus的默认配置，一般不做修改
> * [~/.vimrc.custom.plugins]为用户自定义插件列表，用户增加、卸载插件请修改该文件

## 快捷键
leader key: ','  
help.md: ',h'

```
"""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""
" 插件列表
"""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""
call plug#begin('~/.vim/plugged')

Plug 'chxuan/cppfun'
Plug 'chxuan/change-colorscheme'
Plug 'Yggdroot/LeaderF'
Plug 'mileszs/ack.vim'
Plug 'easymotion/vim-easymotion'
Plug 'haya14busa/incsearch.vim'
Plug 'iamcco/mathjax-support-for-mkdp'
Plug 'iamcco/markdown-preview.vim'
Plug 'jiangmiao/auto-pairs'
Plug 'scrooloose/nerdtree'
Plug 'tiagofumo/vim-nerdtree-syntax-highlight'
Plug 'Xuyuanp/nerdtree-git-plugin'
" Plug 'Valloric/YouCompleteMe'      " replaced by Deep-TabNine 
Plug 'godlygeek/tabular'
Plug 'tpope/vim-fugitive'
Plug 'tpope/vim-surround'
Plug 'tpope/vim-commentary'
Plug 'tpope/vim-repeat'
Plug 'tpope/vim-endwise'
Plug 'majutsushi/tagbar'
Plug 'octol/vim-cpp-enhanced-highlight'
Plug 'vim-airline/vim-airline'
Plug 'vim-airline/vim-airline-themes'
Plug 'vim-scripts/L9'
Plug 'vim-scripts/a.vim'
Plug 'vim-scripts/txt.vim'
" Plug 'ryanoasis/vim-devicons'
Plug 'mhinz/vim-startify'
Plug 'junegunn/vim-slash'
Plug 'junegunn/gv.vim'
Plug 'kana/vim-textobj-user'
Plug 'kana/vim-textobj-indent'
Plug 'kana/vim-textobj-syntax'
Plug 'kana/vim-textobj-function'
Plug 'sgur/vim-textobj-parameter'
Plug 'Shougo/echodoc.vim'
Plug 'terryma/vim-multiple-cursors'
Plug 'terryma/vim-smooth-scroll'
Plug 'terryma/vim-expand-region'
Plug 'fatih/vim-go', { 'do': ':GoUpdateBinaries' }
Plug 'othree/html5.vim'
Plug 'plasticboy/vim-markdown'
Plug 'flazz/vim-colorschemes'
Plug 'vim-scripts/indentpython.vim'
Plug 'rkulla/pydiction'
Plug 'scrooloose/syntastic'
Plug 'nvie/vim-flake8'
Plug 'nvie/vim-flake8'
Plug 'kien/ctrlp.vim'
Plug 'Yggdroot/indentLine'      "缩进线
Plug 'vim-scripts/DoxygenToolkit.vim'   "代码注释
Plug 'cpiger/NeoDebug'          " C++ debug
Plug 'lervag/vimtex'
Plug 'SirVer/ultisnips'
Plug 'honza/vim-snippets'
Plug 'ervandew/supertab'
Plug 'zxqfl/tabnine-vim'       " Deep TabNine 深度补全插件

call plug#end()            
```

## License

This software is licensed under the [MIT license][75]. © 2023 lipiston


