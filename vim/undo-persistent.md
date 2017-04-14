# Undo persistent

Isn't that very annoying when you do some change in a file and after close it you can't undo the change you made? Vim by default can't undo the change because you closed the file.

To solve that you can tweak some settings in your vimrc file.

```vim
" vim undo persistent
set undofile
set undodir=$HOME/.vim/undo
set undolevels=1000
set undoreload=10000
```

After that your changes will be able to undo any changes, even if you close vim.
