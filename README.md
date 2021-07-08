# vue-findings
Bucket for throwing Vuejs related learnings and exxperiments

## frameworks

### Nuxt
- https://nuxtjs.org/

#### Getting Started

```
yarn create nuxt-app my-nuxt-app
```

## tools

### Vim plugin

- https://github.com/leafOfTree/vim-vue-plugin

#### Config

```.vimrc
" vim-vue-plugin
" https://github.com/leafOfTree/vim-vue-plugin
let g:vim_vue_plugin_config = { 
      \'syntax': {
      \   'template': ['html'],
      \   'script': ['typescript', 'javascript'],
      \   'style': ['css'],
      \},
      \'full_syntax': [],
      \'initial_indent': [],
      \'attribute': 1,
      \'keyword': 1,
      \'foldexpr': 0,
      \'debug': 0,
      \}
let g:vim_vue_plugin_highlight_vue_attr = 1
```
