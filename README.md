# Bclose

## Deleting a buffer without closing the window

- Grab the script below
- Add the remap below

" GRB: use fancy buffer closing that doesn't close the split
cnoremap <expr> bd (getcmdtype() == ':' ? 'Bclose' : 'bd')

## References
http://vim.wikia.com/wiki/Deleting_a_buffer_without_closing_the_window
http://stackoverflow.com/questions/1250943/minibufexplorer-and-nerd-tree-closing-buffers-unexpected-behavior
