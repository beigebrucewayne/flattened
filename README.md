# Subtle Solo

Borrows heavily from [romainl/flattened](https://github.com/romainl/flattened). The main focus was to make everything far more subtle. Overall, should allow you to focus more on the code, and less on the noise.

Suggested python syntax highlighting plugin - [here](Hyleus/vim-python-syntax). This option is selected due to support of `pythonDocstring`.

Additionally, for proper Indentation Line coloring see below and use the following plugin - [here](https://github.com/Yggdroot/indentLine).

```vim
" << INDENT LINE >> {{{

let g:indentLine_char = '¦'
" subtle light
let g:indentLine_color_gui = "#eee8d5"
" subtle dark
let g:indentLine_color_gui = "#073642"
" }}}
```

### Flattened (original)
![flattened](https://i.imgur.com/87Q9Ubw.png)

### Subtle Solo (updated)
![minsolo](https://i.imgur.com/e98a75F.png)
