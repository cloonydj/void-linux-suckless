# About
Setup your void linux with suckless tools as dwm, dmenu or st. See [suckless](https://suckless.org/).

# Configuration suckless tools
Changes should be made in `config.h`. File `config.def.h` is for default value. If `config.h` does not exist, then `make install` copy `config.def.h` to `config.h`. See [suckless - dwm](https://dwm.suckless.org/customisation/)  

# Configure paths
It is necessary change paths `X11INC` and `X11LIB` in file `config.mk` in each suckless tool.  

```
X11INC = /usr/X11R6/include -->  X11INC = /usr/include/X11
X11LIB = /usr/X11R6/lib --> X11LIB = /usr/lib/X11
```

