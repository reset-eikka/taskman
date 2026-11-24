Taskman

A Windhawk mod that puts a bunch of small tools into one place: pinned program windows, a mini task manager overlay, an opacity bar, Alt+Q quit, display scaling with the mouse wheel and a screenshot shortcut.

Made by Eikka, written together with Claude (Anthropic's AI).

Press Ctrl+Numpad 0 any time to see a list of the shortcuts that are on right now.

Install
Install Windhawk
In Windhawk press "Create a new mod" and paste the whole contents of taskman.wh.cpp over the template
Press "Compile mod" and then enable it

If you have the old separate mods (Alt+Q Quit, Scale Scroll, Taskumatti) turn them off first, otherwise the shortcuts fire twice.

Shortcuts

Numpad ones need NumLock off, unless you change that in the settings.

Keys	What it does
Ctrl+Num 1-9	show / hide the program in that slot
Shift+Num 1-9	save the position and size of that program
Ctrl+Num 3	task manager overlay (Shift+Num 3 saves its position)
Ctrl+Num 4	opacity bar (Shift+Num 4 saves its position)
Ctrl+Num 7	hide / show everything
Ctrl+Num 0	shortcut help
Alt+Q	quit the focused program, all its windows
Alt+Shift+mouse wheel	change the Windows display scaling
Shift+Space	screenshot (sends Win+Shift+S)
Shift or Alt + mouse wheel	zoom Obsidian while the pointer is over it
Programs

The program slots are in the mod settings. For each slot you give:

the program, either an exe name like claude.exe or the full path to the .exe (with a full path it also gets started if it isn't running)
the numpad key (1-9)
if the key works with NumLock off, on or both
optionally a part of the window title

The defaults are Claude, Obsidian, Spotify, Sticky Notes and File Explorer. Store apps like Sticky Notes live inside ApplicationFrameHost.exe, so for those use that and fill in the window title.

Opacity

The opacity bar sets a base value. Windows get more opaque as they get wider, and a window that is half the monitor wide or more is fully opaque.

Notes
Windows only, needs Windhawk
Shift+Space also fires if you type a capital letter and press space while Shift is still down, so it can be turned off in the settings
Alt+Q won't close Explorer, Windhawk or system processes
