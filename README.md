# My Personal build of st
See [suckless.org](https://st.suckless.org "dwm.suckless.org") for the original source code.


## Patches
- [scrollback](https://st.suckless.org/patches/scrollback/ "scrollback"): Scroll back through terminal output using the mouse scrolling wheel. (all 3 patches applied to use mouse)
- [font2](https://st.suckless.org/patches/font2/ "font2"): This patch allows to add spare font besides default. Some glyphs can be not present in default font. For this glyphs st uses font-config and try to find them in font cache first. This patch append fonts defined in font2 variable to the beginning of font cache. So they will be used first for glyphs that absent in default font.


## Dependencies

For displaying black and white emojis the ttf-symbola font is used. To install this font use yay:

```bash
  yay ttf-symbola
```

## Installation
Clone this repository in whatever folder you want, then go in the cloned directory and build the package:

```bash
  git clone https://www.github.com/rlouage/dwm
  cd st
  sudo make clean install
```
