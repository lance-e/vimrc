<p align="center">personal vim configuration</p>


### usage:
copy the content of vimrc file into ``~/.vimrc``


### Q&A:
##### vim version
install vim9 in older version linux:

ubuntu22 like this:
```bash
sudo add-apt-repository ppa:jonathonf/vim

sudo apt install vim
```

##### coc.nvim
Make sure use Vim >= 9.0.0438 or Neovim >= 0.8.0.

Install nodejs >= 16.18.0
```bash
curl -sL install-node.vercel.app/lts | bash
```

Install extension like this:
~~~
:CocInstall coc-json coc-go coc-clangd
~~~

##### tagbar
* Vim >= 7.3.1058 or any version of NeoVim.

* A ctags implementation: We highly recommend any version of Universal Ctags. It is a maintained fork of Exuberant Ctags with many bugfixes, support for many more formats, and proper Unicode support.Exuberant Ctags 5.5 or higher works to some degree but will be deprecated eventually.Some additional formats can also be handled by other providers such as jsctags or phpctags.

like this:
```bash
sudo apt-get install universal-ctags
```

