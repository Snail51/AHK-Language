# AHK Language Assistant
 Simple AutoHotKey script to assist in typing non-english characters.
 Focuses on German and Spanish characters.

# Before you Begin
 - This solution is designed for Windows 10, but will work on other windows versions.
 - Untested on Linux.
 - Guaranteed to **NOT** work on Apple/MacOS.

# Installation
 YouTube Guide (given to classmates): https://youtu.be/OOhoSKhPhVM
 (Backup of this video is available in this repo, `tutorial.mp4`)

 1. Download AutoHotKey from website: https://www.autohotkey.com/
 2. Create dedicated AHK folder somewhere on your computer.
 3. Download "Language.ahk" from this repo.
 4. Right click `.ahk` file and click "Compile Script"/"Compile Script (GUI)". This will produce a `.exe` of the same name in the same directory.
 5. Double click the `.exe` to start running the script. You can check it is running in the taskbar.

# Run on startup (Optional)
 Follow these steps if you want the script to start running automatically when the computer starts.

 1. press `WINDOWS` + `r`
 2. search `shell:startup`
 3. click `okay`. This will open `C:\Users\mobre\AppData\Roaming\Microsoft\Windows\Start Menu\Programs\Startup`.
 4. right click `Language.exe`, click "create shortcut"
 5. put shortcut in the `Startup` folder. **DO NOT PUT THE ACTUAL .exe HERE, JUST THE SHORTCUT!**
 6. `Language.exe` will now start automatically on computer startup.


# Key Codes
 Alt + Control + a = ä
 Alt + Control + o = ö
 Alt + Control + u = ü
 Alt + Control + Shift + a = Ä
 Alt + Control + Shift + o = Ö
 Alt + Control + Shift + u = Ü
 Alt + Control + s = ß
 Alt + Control + Shift + 4 = €

