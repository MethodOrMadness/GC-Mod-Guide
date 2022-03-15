# GC Mod Guide

currently the language icon is disabled, this will be changed after a crowdin and all that shizz is setup
disabled on line 90 of `_includes/masthead.html`

most things inside curly braces in text bodies indicate links to pages that dont exist yet

## TODO
* Currently the PSOLoad guide is untested but it *should* be working. if someone can test and open an issue that would be amazing
* Save exploits have the base done, but a more in depth tutorial(mostly for picking a save, as well as uploading the save files named properly here need to be done)
* A lot of hardware guides are missing. This is pretty much method's territory so leave those alone
* SDMedia launcher / action replay guides are missing. I know nothing about them so i need someone to give a bit more info.
* Some pictures of a DOL-101 cube. inside and out. all angles. Please contact me(method) through the gamecube discord for more info

### Pages that need work:
+ Action Replay
+ SD Media Launcher
+ Save Exploits(the main page is done):
    + 007
    + AC
    + BMX XXX
    + FZero
    + TP
    + WW
    + Ghost Recon 2
    + Splinter Cell
    + Splinter Cell Pandora
    + TTYOD
    + Colosseum
    + pk XD
    + SMS
    + Melee
+ Disassembly
+ Controller Port LED
+ GCLoader
+ Fan Replacement(needs images)
+ SD2SP2
+ SNES2GC
+ Digital Port in DOL-101
+ Support Braces
+ GCDigital(leave for now

Half done:
+ GCDual
+ Plug and Play

## File Structure
General info should just go in `_pages/en_US`, software guides should go in `_pages/en_US/software`, and hardware guides should go in `_pages/en_US/hardware`

User-downloadable files should be stored in `files`

### Save Exploits
Save exploit guides are stored under `_pages/en_US/software/saveExploits`. there is a file called `saveExploits.md`. this is the main page for save exploits and will have a TOC with all the other pages and other general info

Save exploit files should be in `/files/saves/GAMENAME.zip`. They should also be named properly for gcmm. e.g. paper mario the thousand year door has an NTSC-U game id of `G8ME` so that save file would be `G8ME.gci`

### Hardware

## Contributing

If you are so kind as to contribute to this guide(Thank you!) feel free to fork it and work on the `Development` branch, this branch has the most up-to-date changes before merging into `master`, which is what the website runs