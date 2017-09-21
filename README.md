# PHP Server

Host/Serve current workspace (or subfolder) with PHP.

## Features

You can execute it with:
- Ctrl+shift+P and searching for "Serve Project with PHP"
- Clicking on the editor's button (right superior corner)
- Right-clicking on the editor.

To stop the server just search for "Stop PHP Server" or right-click on the editor.

Now with Windows support, auto open localhost in browser.

## Requirements

PHP installed.

## Extension Settings
This extension contributes the following settings:

* `phpserver.port`: Server Port Number (Default: 3000)
* `phpserver.relativePath`: Path relative to project (In case that you want to serve a different folder than workspace, Default: "")
* `phpserver.browser`: Select the browser that will open localhost (Default: "firefox", Options: "chrome, firefox, edge, ''").
* `phpserver.ip`: Server IP ('localhost', '0.0.0.0', ...).


## Release Notes
### 2.0.1
* Browser is opened every time server is started
* Settings' changes are applied without restart the VScode editor
### 2.0.0
* **Windows console output fixed**
* IP option added
* RelativeUrl option removed (Now is "relativePath");
* Microsoft edge browser added
### 1.1.0
Code rewritten (almost):
* Windows support.
* Auto open localhost in browser (optional).
* Added context menu commands.
* Fixed problem with relative url.
### 1.0.0
Initial release of PHP Server

## Known bugs

#### ~~No console output in Windows~~
-----------------------------------------------------------------------------------------------------------

## For more information

* [GitHub](http://github.com/brapifra)

**Enjoy!**
