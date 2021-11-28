# sm64-decomp-patches
Various patches you can add to the Super Mario 64 decompilation.

File structure:

debug folder
|
---------- papermario-crash.patch: Add Paper Mario-like crash handler to the game. Needs the crash_screen_font.ia1.png file to be placed in textures/crash_screen/ for the code to compile on NTSC and original JPN versions.

crash_screen_font.ia1.png: Font for the Paper Mario-like crash handler. Needed to compile the NTSC and JPN editions with the crash handler. The PAL and Shindou editions already contain this file and will be extracted at compile time.
