# Howl

___Lightweight editor with keyboard-centric minimalistic interface___

Howl is a general purpose editor that aims to be both lightweight and fully customizable. It is built on top of the very fast LuaJIT runtime, and can be extended in either Lua or Moonscript. It has a minimalistic UI driven mainly by the keyboard. 

---

## Manual Install and Run

Make sure you follow the [setup guide for your Linux distribution](https://flathub.org/en/setup) before installing

```
flatpak install flathub io.howl.Editor
flatpak run io.howl.Editor
```

## Building

```
git clone git@github.com:flathub/io.howl.Editor.git
flatpak run org.flatpak.Builder build-dir --user --ccache --force-clean --install io.howl.Editor.yaml
```

---

**Technologies**: GNOME, GTK3, Lua, C
