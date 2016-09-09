tender
======

A true color colorscheme for Vim and its ecosystem. (with 256 colors fallback)

(generated by [Estilo](https://github.com/jacoborus/estilo))

![color palette](https://cloud.githubusercontent.com/assets/829859/16198567/a8a915f0-3706-11e6-96ed-941aeb9ccfc1.png)


## Installation

Install manually or use a package manager:

```viml
" vim-plug
Plug 'jacoborus/tender'
" NeoBundle
NeoBundle 'jacoborus/tender'
" Vundle
Plugin 'jacoborus/tender'
```

Once your plugin is installed you can set the color scheme in your `.vimrc` or `init.vim`

Enable true color in neovim:

```viml
set termguicolors
```

Enable true color in vim v7.4.1770 or newer:

```viml
set guicolors
```

Fix for MacVim:

```viml
let macvim_skip_colorscheme=1
```

Regular theme:

```viml
colorscheme tender
```

**Tender** includes [lightline](https://github.com/itchyny/lightline.vim) and [airline](https://github.com/vim-airline/vim-airline) themes, to enable it add the next lines to your vim config:

**lightline:**

```viml
" enable tender lightline theme
let g:tender_lightline = 1
" set lighline theme (inside lightline config)
let g:lightline = { 'colorscheme': 'tender' }
```

**airline:**

```viml
" enable tender airline theme
let g:tender_airline = 1
" set airline theme
let g:airline_theme = 'tender'
```


## Features:

- dark background
- tender colors
- minimal interface
- lightline theme
- airline theme
- fine tune colorization for languages and plugins:
  - javascript
  - css
  - markdown
  - yaml
  - json
  - gitcommit
  - NERDTree
  - GitGutter
  - pangloss/javascript
  - pangloss/javascript
  - jelera/vim-javascript-syntax
  - ... more coming soon (contributions are welcome)

## Screenshots

![javascript](https://cloud.githubusercontent.com/assets/829859/15333458/01b57d62-1c6a-11e6-8b2f-94ee49717922.png)
![nerdtree, json and yaml](https://cloud.githubusercontent.com/assets/829859/15333480/1ae0f442-1c6a-11e6-92a1-53fe5a264501.png)
![diff](https://cloud.githubusercontent.com/assets/829859/15333530/4cce7d9e-1c6a-11e6-8a66-f955c2a99681.png)
![lightline](https://cloud.githubusercontent.com/assets/829859/15333539/57e8d710-1c6a-11e6-9809-ef5768ca4103.png)
![gitcommit](https://cloud.githubusercontent.com/assets/829859/15333549/6372bb00-1c6a-11e6-901c-45dbcfc022c5.png)


## Contribute

Clone the repo and install dependencies with nodejs, then follow [Estilo instructions](https://github.com/jacoborus/estilo/#step-by-step)

<br><br>

---

© 2016 [jacoborus](https://jacoborus.codes) - Released under [MIT License](https://raw.github.com/jacoborus/nanobar/master/LICENSE)
