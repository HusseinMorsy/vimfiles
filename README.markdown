
== Used Plugins

* complete-T (see http://www.vim.org/scripts/script.php?script_id=3025 und screencast http://s3.wincent.com/command-t/screencasts/command-t-preview.mov)
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
