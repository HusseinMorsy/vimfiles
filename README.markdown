== Intro

The vimfiles are based on 

* http://amix.dk/vim/vimrc.html
* http://github.com/scrooloose/vimfiles

== Used Plugins

* vim-fugitive - a Git client (see http://github.com/tpope/vim-fugitive)
* complete-T (see http://www.vim.org/scripts/script.php?script_id=3025 und screencast http://s3.wincent.com/command-t/screencasts/command-t-preview.mov)
* colortheme  vividchalk (see http://github.com/tpope/vim-vividchalk)
* ...

== Installatoin

Clone this repo into your home directory either as .vim (linux) or vimfiles (MF
Windows).

Then cd into the repo and run this to get the snippets submodule:

<pre><code>
git submodule init
git submodule update
</code></pre>

Put this in your  .vimrc: 

fun! MySys()
  return "mac"
endfun

source ~/.vim/vimrc
</code></pre>
