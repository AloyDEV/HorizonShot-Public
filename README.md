# HorizonShot-Public
For ponsting final packaged versions of HorizonShot.  

## Using the program

Download the .zipfile from Releases. <br>
Unzip the file, and run the EXE.  No installation is required. <br>
    Comes bundled with a JRE to that Java does not need to be installed on the local machine <br>
If the program launches successfully, you should see the black & red arrow icon in your system tray <br>
Click on the icon to take a screenshot <br>
Right-click the icon to exit the program, otherwise it will run indefinitely <br>
    Also, if you don't exit using this method, then the log.lck file might stick around
When the initial screenshot is taken, the raw screenshot is copied to the clipboard, in addition to being opened in the editing window <br>

* Includes a Global HotKey to trigger the screenshot at any time (Ctrl + Alt + `)
  * Alternatively, click the system tray icon to take a screenshot.
  * Or Right-Click the system tray icon, and click Take Screenshot

* Severe errors are logged into HShot.log in the EXE directory.
* 
* Editor: Uses a default location when saving the screenshot, the users Home directory.
    * YOu can right-click the Save button to change the file type and save location

* Editor: Undo handler: Removes items drawn on the image
* Editor: Inserting text: Text is editable until another item (arrow, line, box, etc) is drawn on the image.

* Editor: If errors in the editor are encountered, there should be a message on the right informing the user.
