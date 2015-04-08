## Map commands in different modes

This mapping applies only when we are in normal mode.

```
:nmap \ dd
```

This mapping applies only when we are in visual mode.

```
:vmap \ dd
```

This mapping applies only when we are in insert mode. We need the `<esc>` keystroke before `dd` otherwise two `d` characters will literally get inserted when we are in insert mode.

```
:imap <c-d> <esc>dd
```

And this perfects our mapping so that we return to insert mode.

```
:imap <c-d> <esc>ddi
```
