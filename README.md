Flatpak build for [io.github.simonaking.ScrcpyGui](https://github.com/SimonAKing/scrcpy-gui)

```
flatpak run org.flatpak.Builder \
  --force-clean \
  --user \
  --install \
  --install-deps-from=flathub \
  build-dir \
  io.github.simonaking.ScrcpyGui.json
  
  flatpak run io.github.simonaking.ScrcpyGui
```
