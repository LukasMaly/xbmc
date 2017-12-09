# My Kodi customizations

## Music visualisation black background

Sets the music visualisation background to black color so the TV will switch off the screen to save power.

### Instructions

1. Copy `skin.esturay` from original (read-only) location:

```shell
cp -r /usr/share/kodi/addons/skin.estuary /storage/.kodi/addons/skin.estuary
```

2. Replace `MusicVisualisation.xml`:

```shell
scp ./skin.estuary/xml/MusicVisualizasion.xml root@libreelec.local:/storage/.kodi/addons/skin.estuary/xml/MusicVisualisation.xml
```

3. Reboot the Kodi
