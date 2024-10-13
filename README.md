# com.gluonhq.SceneBuilder
Flatpak for [Scene Builder](https://gluonhq.com/products/scene-builder)

## Prerequisite

- `flatpak`, `flatpak-builder` packages
- Runtime `org.freedesktop.Platform` version `24.08`
- Runtime `org.freedesktop.Sdk` version `24.08`
- Runtime Extension `org.freedesktop.Sdk.Extension.openjdk`

### Build and install Scene Builder
```bash
flatpak-builder --user --install --force-clean  flatpakbuildir com.gluonhq.SceneBuilder.yml
```
### Run Scene Builder
```bash
flatpak run com.gluonhq.SceneBuilder
```
### Uninstall Scene Builder
```bash
flatpak uninstall --user com.gluonhq.SceneBuilder
```
