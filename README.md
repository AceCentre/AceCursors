# Ace Centre Cursors

Coloured, Moving and large cursors for all sorts of users. Windows.

![](https://github.com/AceCentre/AceCursors/blob/master/cursors.jpg?raw=true)

### Prerequisites

Windows XP, 7, 8, 10 all supported. 

### Installing

You have a couple of options.

1. **The easy way.**

[Download the installer here](https://github.com/AceCentre/AceCursors/releases/download/1.0/Setup.exe) and run it. It simply places all the cursors at ``C:\Windows\Cursors\Ace Cursors`` - you then open up your mouse control panel and select a new pointer. We have tried to make this a bit easier by creating a shortcut to this in your ``Start Menu/Ace Centre/Ace Cursors`` folder. 

2. **The manual way.**

[Download a zip of this directory](https://github.com/AceCentre/AceCursors/archive/master.zip) and manually copy and paste the entire ``Ace Cursors`` directory to ``C:\Windows\Cursors\Ace Cursors``

You may also want to pop the ``Mouse Pointers Properties.lnk`` somewhere sensible like the desktop. Its a quick link to the mouse pointers properties control panel. If you want you can make this yourself:

-  Right click on a empty area on desktop, and click on New and Shortcut. 
-  Paste the following in: 

```
%SystemRoot%\System32\rundll32.exe shell32.dll,Control_RunDLL main.cpl,,1
```

## Uninstalling

Navigate to: ``%ProgramData%\Microsoft\Windows\Start Menu\Programs\Ace centre\Ace cursors``
or 
``%AppData%\Microsoft\Windows\Start Menu\Programs\Ace centre\Ace cursors`` and double click on the ``UninstallAceCursors.exe`` 

If you have installed it using the manual method - just remove anything found in ``C:\Windows\Cursors\Ace Cursors``

## How to actually change the cursor?

[![Install cursors](https://github.com/AceCentre/AceCursors/blob/master/install.gif?raw=true)](https://github.com/AceCentre/AceCursors/blob/master/install.gif?raw=true)

## Creating the installer

You will need [NSIS](http://nsis.sourceforge.io) - just download this repo and use the installer file ``Installer.nsi``

## Making your own cursors?

The simple answer is to use [RealWorld Cursor Editor](http://www.rw-designer.com/cursor-maker). **.cur** files are basically **.ico** files with a different extension. So you can edit them in anything that edits ico files (e.g. [CursorWorkshop](https://www.axialis.com/cursorworkshop/) and [Inkscape](https://inkscape.org/).) 

## Authors

David Colven, Ace Centre
	
## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

