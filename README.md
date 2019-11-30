# asyncomplete-vlime.vim

[Vlime](https://github.com/l04m33/vlime) completion source for [asyncomplete.vim](https://github.com/prabirshrestha/asyncomplete.vim)

## Dependencies

- [asyncomplete.vim](https://github.com/prabirshrestha/asyncomplete.vim)
- [Vlime](https://github.com/l04m33/vlime)

## Registration

```vim
autocmd User asyncomplete_setup call asyncomplete#register_source(asyncomplete#sources#vlime#get_source_options({
\ 'priority': 10
\ }))
```

