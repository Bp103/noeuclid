Files you care about:

games/test.c < the game.
scripthelpers.h < bunch of useful stuff.
tccexports.cpp < All the stuff exported from the main game engine to TCC.
tileattributes.txt < File containing the visual appearance for various tiles.

Modifying games/test.c while the game is running will just cause it to be recompiled in-place.  Where you are.

Hotkeys:

'a', 's', 'd', 'w' -> Walk around
' ' -> jump
'g' -> Go into noclip mode.
 ']', '[' -> Go up/down
'0' -> Show additional debug info.
'-' -> Go down level.
'+' -> Go up level.
'r' -> Reload current.

There's a map of the 256 different available blocks above Room 4.  It will say what block you are standing on.

You can add new blocks by modifying tileattributes.txt

