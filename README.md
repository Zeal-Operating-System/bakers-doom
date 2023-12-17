# bakers-doom

Chocolate Doom Loader and Translation Layer for TempleOS.

By Alec Murphy for TempleOS.

Ported to ZealOS on 12/17/2023.

![chocolate-doom](preview.gif "chocolate-doom")

# Usage

Clone the repo into your /Home/ folder.

Use the sync script in the ZealOS `build` folder to sync the files to your VM. 

Then, `#include "Run";`

# Notes

The WAD file for the Shareware version of DOOM is included,
other game WADs supported by chocolate-doom may or may not work.

If testing other WADs, edit `Load.ZC` chocolate-doom args.

Save games not implemented yet; if you try to save your game,
it will crash. 

# TODO

- Sound support
- Save games
- Bugfixes
