# Quick and Dirty Python/Qt Wad Loader for Mac.
 App builds failed for py2app, fbs, and PyInstaller
 Should have used Tkinter; lessons learned.

# Requirements
 Python 3.5 or higher (brew install python3)
 PyQt5 (pip install PyQt5)
 GZDoom (brew install GZDoom)

# Instructions

## Starting GrimmWadLoader:
 Run "python3 grimmWadLoader.py" in terminal.
 -or-
 Use chmod to make grimmWadLoader.py execuable so that you can simply
 double click to run. (may require modifying the #! for your system)

## Using GrimmWadLoader:

### Selecting Files
 GrimmWadLoader is just a script generator for GZDoom. Select GZDoom compatible *.wad, *.iwad, *.pk3, etc,... by clicking the "IWAD Slot #" buttons and navigating to the desired files. Often, the order of the 
 files is important so be sure to check the README files associated
 with the wads to be used. Slot 0 should be the base game wad.

### Runing a Mod Script
 After selecting the desired files. Simply click the "Run" button at 
 the bottom of the application. 

### Saving a Mod Script
 To save a mod script, simply enter a unique name in the text entry field directly below the words "Mod Script Name" and click the "Save Mod
 Script" button below. The name of your new script should then appear in the "Saved Mod Scripts" list on the right side of the application.

### Load a Mod Script
 To load a mod script, highlight the Mod Script name in the list on the right hand side of the application. Then click the "Load Mod Script" button. The wad associated with the script should be slotted. Click "Run" to start your Mod Script.

### Delete a Mod Script
 Select the mod script you wish to delete from the list by clicking to highlight it. Then click the "Delete Mod Script" button. The script should disappear from the "Saved Mod Script" list.

# Warnings
## Do not delete or modify the savedScripts.json file.
## The author is not liable for any damages of any kind to you or your proporty in any way, shape, or form.