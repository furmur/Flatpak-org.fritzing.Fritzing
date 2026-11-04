# build
```
$ flatpak-builder --user --force-clean --install-deps-from=flathub --repo=repo build org.fritzing.Fritzing.json
```

# bundle
```
$ flatpak build-bundle repo fritzing.flatpak org.fritzing.Fritzing --runtime-repo=https://dl.flathub.org/repo/flathub.flatpakrepo
```

# install
```
$ flatpak install fritzing.flatpak
```
