# goda-cmp-ui-inline.vim

The UI `inline` of [goda-cmp.vim](https://github.com/Shougo/goda-cmp.vim):
the first item as virtual text, for a single candidate (ddc-ui-inline).

## Requirements

- [goda-cmp.vim](https://github.com/Shougo/goda-cmp.vim)

## Usage

Add it in the configuration of goda-cmp.vim:

```go
import "github.com/Shougo/goda-cmp-ui-inline.vim/ext/ui/inline"

b.AddUI(inline.New())
b.PatchGlobal(cmp.Config{UI: "inline"})
```

See `:help goda-cmp-ui-inline`.
