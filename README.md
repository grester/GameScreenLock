# GameScreenLock
This program is designed for multiscreen players, to be able to keep multiple screens enabled, but restrict mouse movement boundaries to a single monitor where the game is running.

This is a program that locks the cursor to the primary monitor for games where the devs were too incompetent to do so themselves.

In certain games, for example CS:GO, GTA V in windowed fullscreen and Skyrim, the mouse will not be locked to the primary monitor.
This can cause a user to drag the cursor out of the program, click, suddenly minimize the game and have to switch back in.

## Why make this program?

The original(?) PrimaryLock by AKADEVIL does the job well, but it is a little rudimentary, in that it just locks the cursor as long as PrimaryLock is open. 

My improved version doesn't lock the cursor if you alt-tab out manually or if no fullscreen application is open, allowing much more seamless switching to music players etc.
This also lets you keep the application open while no game is running, so that you don't have to keep in mind to open the application every time you start the game.

All this is made possible by watching what window is focused. Any window both fullscreen and in focus will trigger the primary monitor lock.

# How it works?
