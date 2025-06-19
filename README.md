# Simple Terminal ![st](https://img.shields.io/static/v1?label=st&message=0.9.2&color=blue&style=flat-square)

`st` is a simple terminal implementation for X.

## Upstream

The upstream development for `st` can be found [here](https://git.suckless.org/st).

# Patches

- [alpha](https://st.suckless.org/patches/alpha_focus_highlight/)
- [clipboard](https://st.suckless.org/patches/clipboard/)
- [boxdraw](https://st.suckless.org/patches/boxdraw/)
- [ligatures](https://st.suckless.org/patches/ligatures/)
- [pipe](https://st.suckless.org/patches/externalpipe/)
  - [scrollback compatibility](https://st.suckless.org/patches/externalpipe/) (w/ manual fixes)
- [scrollback](https://st.suckless.org/patches/scrollback/) (ringbuffer)
  - [boxdraw compatibility](https://st.suckless.org/patches/ligatures/)
- [xresources](https://st.suckless.org/patches/xresources/)

# Install

Download the source code from this repository:

```
git clone https://github.com/v3natio/st.git
cd st
sudo make clean install
```
