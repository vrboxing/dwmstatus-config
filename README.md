# sugud0r's dwmstatus config

Just very simple as my style and needs.

## Characteristics

For now, just show the current date.

## Configure

You need to modify `dwmstatus.c`file to add, delete or modify characteristics, thus, you need to know some C to get it.

## Installation

```
make
make install
```

Now add `dwmstatus 2>&1 >/dev/null &` in your `.xinitrc` file to execute `dwmstatus` when the Xorg server start.
