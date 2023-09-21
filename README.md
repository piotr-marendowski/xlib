# xlib

### Most of them are from Guy Keren's ["Basic Graphics Programming With The Xlib Library"](https://ftp.dim13.org/pub/doc/Xlib.pdf).

### simple-drawing.c

![simple-drawing](assets/simple-drawing.png)

### events.c

![events](assets/events.png)

### simple-text.c

![simple-text](assets/simple-text.png)

### simple-wm-hints.c

Integrates well with dwm, but I don't have patch allowing me to display icons. On Qtile it doesn't show icon either.

![simple-wm-hints](assets/simple-wm-hints.png)



### Compile and run

```
gcc -g -o out simple-drawing.c -lX11 && ./out
```

Don't see any need for a Makefile.
