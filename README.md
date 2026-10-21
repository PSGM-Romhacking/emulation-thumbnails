# emulation-thumbnails

Box art, title screens and gameplay screens for games that run on emulators and are missing
from [libretro-thumbnails](https://github.com/libretro-thumbnails/libretro-thumbnails):
homebrew and other games released after the systems' commercial life.

Made for [Mil Capivaras](https://github.com/PSGM-Romhacking/mil_capivaras), a Casio PV-1000
emulator, but free for anyone to use: any emulator, frontend or collection.

## Layout

The same as libretro-thumbnails: one folder per system, named as in libretro, with three
folders inside.

```
<System>/
├── Named_Boxarts/   box art
├── Named_Titles/    title screen
└── Named_Snaps/     gameplay
```

## Naming

The same rules as libretro-thumbnails, so the images work in RetroArch as they are:

- the system folder has libretro's exact name (`Casio - PV-1000`);
- the file name is the ROM's No-Intro name, letter by letter, with
  ``& * / : ` < > ? \ | "`` replaced by `_`:
  `Cacorm (World) (Aftermarket) (Unl).png`;
- a game with several ROMs (one per language, for instance) has one image per ROM name;
- images are PNG.

## Systems

- Casio - PV-1000: the box art uses the layout of the original boxes in blue, where the
  official games are red, so they are never mistaken for them.
- Funtech - Super Acan: *Rebel Star*, which only reached a few sample cartridges and is the one
  game of the system missing from libretro-thumbnails. Same sizes as libretro's images for the
  system: box 512 × 896, screens 320 × 224 (the 224 visible lines; the game draws 240).

## Credits

The games belong to their authors. The title and gameplay screens were captured in
emulators; box art without an official version follows the layout of the system's original
boxes.

Exception: the box art of *Rebel Star* (Funtech - Super Acan) is the front of an original sample
box, cropped and straightened from a collector's photo
(<https://vgs-media.s3.ca-central-1.amazonaws.com/monthly_2023_09/Rebel.png.a9a19d4a339bfa730dcede08ec51da00.png>).
It is not covered by the CC0 licence below: the artwork belongs to its publisher and the photo
to its author.

## License

[CC0 1.0](LICENSE): public domain. Copy, modify, redistribute and use them for anything,
with no need to ask or to give credit. This covers the images made for this repository;
the games themselves, and anything in them, remain their authors'.
