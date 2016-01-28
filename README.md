# Maximizing script (mxmzngscrpt)
Stretches to the bounds of the screen currently active app on MacOS X. 
So far works only for single monitor.

## How to use

When I need my current app to be stretched for the whole screen 
(and I need to see progress bar at the top too) - 
I simply open Spotlight (`options+space`) and than start typing 
`mxm..` than hit `Return`. WHOOP! Now app borders are bounded to 
screen borders. Fantastic! No need to find a mouse, than a cursor, 
than stretch.. 

## Install

### <a name="install-semi-automatically"></a>Semi-automatically 
You can simply download `mxmzngscrpt.app` and put it in anywhere, 
for example into your Applications folder;

After first time you try to open it - you'll see an alert, because 
this app needs to be granted permissions at `System Preferences ->
 Security & Privacy -> "Privacy" tab -> "Accessibility"`. There 
 add this app to the list on the right. And here we go!
 
 *`System preferences` will be launched automatically after you close the alert.

###Build manually
Also you can create your own app using `Automator` app (system 
pre-installed on MacOS X) and `main.scpt` that is in the root of this repo.

1) Open `Automator` app;

2) Choose `Application`;

3) Drag-n-drop `Run AppleScript` from the list the second from the left to the right;
 
4) Replace template text that appears on the right with the contents of the file `main.scpt`;

5) Save as application wherever you want.

Don't forget to grant permissions for your app at `System Preferences` 
the same way as it was shown in [Install: Semi-automatically](#install-semi-automatically) section.