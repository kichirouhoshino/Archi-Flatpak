# Archi-Flatpak

This is a Flatpak package of Archi. This uses the release binaries from the official site.

You can install it from my personal flatpak repo (remove the --user argument to install system-wide)
``` bash
flatpak remote-add --user roddy-flatpak https://kichirouhoshino.github.io/roddy-flatpaks/index.flatpakrepo
flatpak install roddy-flatpak com.archimatetool.Archi
```

While the app can be built from source, it is currently a pain to do as flatpak-builder does not have proper maven support yet. If support does finally arrive, someone else would've probably made a proper (or official) flatpak for it.
