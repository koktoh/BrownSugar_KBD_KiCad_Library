# BrownSugar Keyboard KiCad Library

KiCad library for building keyboard

![footprint](https://github.com/koktoh/BrownSugar_KBD_KiCad_Library/blob/img/img/footprint_all.png)

## KiCad Symbols and Footprints

The symbols and footprints in this repository are created using KiCad version 5.x.

## 3D Models

For now, the 3D models in this repository are WRL file only.

Some of the 3D models are included as git submodules.

Please use the 3D models of submodules in accordance with their respective licenses.

### Submodules

- https://github.com/koktoh/keyswitch_model
- https://github.com/koktoh/keycap_model

## How to use

### Clone repository

Run this command.
```
git clone git@github.com:koktoh/BrownSugar_KBD_KiCad_Library.git
```

### Init git submodule

Run this command.
```
git submodule init
git submodule update
```

### Register path on KiCad

Register path for rendering the 3D models in KiCad 3D view.

|Name|Path|
|:--|:--|
|`BROWNSUGAR_KBD_3DMOD`|`[cloned directory]\BrownSugar_KBD.3D` (ex. `C:\foo\bar\BrownSugar_KBD.3D`)|

![Setting menu](https://github.com/koktoh/BrownSugar_KBD_KiCad_Library/blob/img/img/001.png)

![Setting window](https://github.com/koktoh/BrownSugar_KBD_KiCad_Library/blob/img/img/002.png)
