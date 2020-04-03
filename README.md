# editors

Repository for text editor syntax highlighting.


## Syntax for Vim

Although this repo contains syntax files for other editors it should work with 
plugin-managers such as Vundle and Pathogen. Just add this line to the 
`.vimrc`:

```vimrc
Plugin "tamarin-prover/editors"
```
or if you use [vim-plug]( https://github.com/junegunn/vim-plug ) and want to
follow tamarin's  `develop` branch.
```vimrc
Plug 'tamarin-prover/editors', { 'branch': 'develop' }
```

The files

  - `filetype.vim`
  - `syntax/`

are for use with Vim.
