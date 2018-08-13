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

Borrows heavily from [romainl/flattened](https://github.com/romainl/flattened). The purpose of the changes was to make the focal point the code, and nothing else.


### Subtle Dark

![sdark](https://i.imgur.com/Arxa4qv.png)

### Subtle Light

![slight](https://i.imgur.com/jVflIzk.png)

## Installation

```vim
" Assuming vim-plug
Plug 'kadekillary/subtle_solo'

" colorscheme
colorscheme subtle_? (dark/light)
```

## Tmux

Add the following to your `.tmux.conf`

```text
set-option -ga terminal-overrides ",xterm-256color:Tc"
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

## Terminal

Terminal used in screenshots is [alacritty](https://github.com/jwilm/alacritty).
