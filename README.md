# GC-GBA EmuInjector
This is a Python script that uses several existing tools to inject a GBA ROM (<= 16 MB) into the official GBA emulator found on some Gamecube demo discs, with the option to include a custom overlay.

Keep in mind that the official emulator was only designed to play a handful of specific games, so many games will not run well on it. Additionally, you can only use the built-in save data, meaning games that use save data may start with... interesting save files.

### Usage
Usage: GCGBA_ei.py -a <input GBA> -c <input GC> -t <TPL/PNG>

-a <the GBA ROM that will be injected>
-c <the Gamecube file that the GBA ROM will be injected into; this is zz_MarioVSDonkey_game.tgc, which can be extracted from Interactive Multi-Game Demo Disc Version 16/17, or zz_MarioPinballLand_game.tgc, which can be extracted from Interactive Multi-Game Demo Disc Version 18>
-t <optional; a new texture/PNG file for the background image; if not set, the exiting background will be used>

### Legal Disclaimer
No copyrighted content is included with this program. You have to supply the files for GBA injection.

### Included Programs/Credits
Some of the tools bundled with this program are not made by me, but are required for its use:
- [Gamecube ISO Tool](http://www.wiibackupmanager.co.uk/gcit.html) (Made by FIG2K4)
- [TGCtoGCM](https://www.gc-forever.com/forums/viewtopic.php?t=17&start=24) (Made by Zochwar & Plootid)
- [Wiimms Image Tool](https://szs.wiimm.de/wimgt/) (Made by Wiimm)
