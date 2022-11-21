## Toggle Background Function

Solarized comes with a Toggle Background plugin that by default will map to if that mapping is available. If it is not available you will need to either map the function manually or change your current mapping to something else.

To set your own mapping in your .vimrc file, simply add the following line to support normal, insert and visual mode usage, changing the "" value to the key or key combination you wish to use:

```
call togglebg#map("<F5>")
```

Note that you'll want to use a single function key or equivalent if you want the plugin to work in all modes (normal, insert, visual).

## Note

This script has been developed by Ethan Schoonover for his Solarized color scheme.

Original work can be found here: [Original Script]

[Original Script]:https://github.com/altercation/vim-colors-solarized
