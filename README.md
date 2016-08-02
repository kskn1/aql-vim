# aql-vim
A simple vim syntax highlighting config for AQL (ArangoDB Query Language), the language used for querying [ArangoDB](http://www.arangodb.com)

I could point you to the emacs one, but if you're here why would you want or need to go there?

### Installation
Place aql.vim into your vim folder, usually: `~/.vim/syntax/`

Then to make it recognize on start, edit in either your `~/.vimrc` or create a file in `~/.vim/ftdetect/aql.vim` to put

```
au BufRead,BufNewFile *.aql set filetype=aql
```
