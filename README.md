```text
                                          W A N T E D

                   F O R   C R I M E S   A G A I N S T   T H E   E M P I R E
                                  _________________________ 
                                 |      .x%%%%%%x.         |
                                 |     ,%%%%%%%%%%%        |
                                 |    ,%%%'  )'  \%        |
                                 |   ,%x%) __   _ Y        |
                                 |   :%%% ~=-. <=~|        |
                                 |   :%%::. .:,\  |        |
                                 |   `;%:`\. `-' .'        |
                                 |    ``x`. -===-;         |
                                 |     / `:`.__.;          |
                                 |  .d8b.  :: ..`.         |
                                 | d88888b.  '  /8         |
                                 |d888888888b. ( 8b       /|
                                 |~   ~`888888b  `8b     /:|
                                 |  ' ' `888888   `8. _ /:/|
                                 |'      )88888b   8b |):X |
                                 |   ~ - |888888   `8b/:/:\|
                                 |       |888888    88\/~~;|
                                 |       (888888b   88|  / |
                                 |\       \888888   8-:   /|
                                 |_\_______\88888_.'___\__/|

                                     ~~~  SUBTLE SOLO  ~~~

                                        Smuggler, Pirate
                                        200,000 credits
```

Borrows heavily from [romainl/flattened](https://github.com/romainl/flattened). The main focus was to make everything far more subtle. Overall, should allow you to focus more on the code, and less on the noise.

Suggested python syntax highlighting plugin - [here](Hyleus/vim-python-syntax). This option is selected due to support of `pythonDocstring`.

### Subtle Solo

![sdark](https://i.imgur.com/kmhTimh.png)
![slight](https://i.imgur.com/VxatK5s.png)

## Installation

```vim
" Assuming vim-plug
Plug 'beigebrucewayne/subtle_solo'

" colorscheme
colorscheme subtle_? (dark/light)
```

## IndentLine

To get the indentation line coloring from above, see below, and use the following plugin - [here](https://github.com/Yggdroot/indentLine).

```vim
" << INDENT LINE >> {{{

let g:indentLine_char = '¦'

" Choose one or the other

" subtle light
let g:indentLine_color_gui = "#eee8d5"

" subtle dark
let g:indentLine_color_gui = "#073642"
" }}}
```
