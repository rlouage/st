# My Personal build of st
See [suckless.org](https://st.suckless.org "dwm.suckless.org") for the original source code.


## Patches
- [scrollback](https://st.suckless.org/patches/scrollback/ "scrollback"): Scroll back through terminal output using the mouse scrolling wheel. (all 3 patches applied to use mouse)
- [xresources](https://st.suckless.org/patches/xresources/ "xresources"): This patch adds the ability to configure st via Xresources. At startup, st will read and apply the resources named in the resources[] array in config.h.



## Installation
Clone this repository in whatever folder you want to keep the source code in, then go in the cloned directory and build the package:

```bash
  git clone https://www.github.com/rlouage/dwm
  cd st
  sudo make clean install
```
