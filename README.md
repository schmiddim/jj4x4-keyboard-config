# Anleitung Numpad flashen
## Name PCB: JJ4x4

## Software
- Python2 
- setuptools
- wheel
- libusb-dev
- ....

## Konfig erzeugen + Tutorial
[Qmk GithubPages](https://config.qmk.fm/#/jj4x4/LAYOUT_ortho_4x4)


## In den Bootloader starten:
2. Reihe von oben 2. Taste von links beim einstecken halten

**Flashen:**
```
bootloadHID -r <filename>.hex
```
