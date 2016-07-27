# aql-vim
A simple syntax highlighting for AQL (ArangoDB Query Language).

### Installation
Place aql.vim into your vim folder, usually: `~/.vim/syntax/`

Then to make it recognize on start, edit in either your `~/.vimrc` or create a file in `~/.vim/ftdetect/aql.vim` to put

```
au BufRead,BufNewFile *.aql set filetype=aql
```
I