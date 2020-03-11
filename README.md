# Ace Centre Cursors

Coloured, Moving and large cursors for all sorts of users. Windows.


### Prerequisites

Windows XP, 7, 8, 10 all supported. 

### Installing

You have a couple of options.

1. **The easy way.**

[Download the installer here](https://github.com/AceCentre/AceCursors/releases/download/1.0/Setup.exe) and run it. It simply places all the cursors at ``C:\Windows\Cursors\Ace Cursors`` - you then open up your mouse control panel and select a new pointer

2. **The manual way.**

[Download a zip of this directory](https://github.com/AceCentre/AceCursors/archive/master.zip) and manually copy and paste the entire ``Ace Cursors`` directory to ``C:\Windows\Cursors\Ace Cursors``

You may also want to pop the ``Mouse Pointers Properties.lnk`` somewhere sensible like the shortcut. Its a quick link to the mouse pointers properties control panel. If you want you can make this yourself by creating a shortcut with the following as the destination

-  Right click on a empty area on desktop, and click on New and Shortcut. 
-  Paste the following in: 

```
%SystemRoot%\System32\rundll32.exe shell32.dll,Control_RunDLL main.cpl,,1
```

## Creating the installer

You will need [NSIS](http://nsis.sourceforge.io) - just download this repo and use the installer file ``Installer.nsi`

## Authors

David Colven, Ace Centre
	
## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

