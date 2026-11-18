StickFigure

A living stickman that walks across the Windows desktop over all windows.

Written in Python

What it can do:

Walks across the screen on its own, explores the space, remembers its “home” and returns there

At night, it walks slower and sometimes “yawns”

If the mouse doesn’t move for a long time, it approaches the cursor

Reacts to the mouse: notices, looks, approaches

Dragging: hold down the left mouse button — drag; release — it falls according to physics

It breaks free if you shake the mouse or hold it for too long.

Right‑click on it — menu: Rename, Pet, Edit, Delete.

Edit — customization panel: color (presets + RGB sliders), hats, glasses, neck accessory, empty/filled head.

Pet — pet (move the mouse over the head, affection grows).

Relationships: from -100 to +100, affect behavior (high values — it comes closer on its own, low values — it runs away).

Secret modes

Name the stickman via Rename:

The Chosen One — flies, fire, lasers from eyes, cuts the screen, resists renaming and doesn’t let itself be pet

The Dark Lord — dark aura, throws black balls with a red border, the menu is infected (only ESC), you can’t rename/delete/pet it

The modes are incompatible: the last name entered determines the mode.

Management

Right-click on the stickman — menu

Hold down the LMB — drag

ESC — close the menu/panel, press again — exit the program

Delete in the menu — close the program

Installation and launch

You need Windows (the project is based on win32api/win32gui, it won’t work on Mac/Linux).

Download stick.exe from the releases and run it. No installation is required.

Antivirus may swear at an exe compiled through PyInstaller — this is a false positive, add it to the exceptions.
