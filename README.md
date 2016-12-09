# cross-browser-extension
##Cross browser extension using Kango Framwork

## 1. Creation of new project
Create a directory for the project and run kango.py from the framework directory:
```
python kango_dir/kango.py create "my_project_dir"
```
On request for project name enter Gmail Checker.

Now you may start writing code of your extension.

Later on you can set name and version of your extension using file common\extension_info.json.

## 2. Writing Gmail Checker¶
The extension will check number of unread messages on Gmail from time to time and show such number on a browser button.
After creation of project open directory ```src\common``` to see that template is already created in the file ```main.js```.
## 3. Icons
You should place icons in PNG format with names button.png, icon32.png, icon48.png, icon100.png, icon128.png with 
dimensions ```16x16, 32x32, 48x48, 100x100, 128x128 ```pixels respectively into directory ```common/icons```, as well as icon
```button_gray.png``` in order to display inactive state.

## 3. Project building
In order to build the project run kango.py with argument build and path to the project directory:
```
python kango_dir/kango.py build "my_project_dir"
```
Google Chrome or Chromium should be installed so that you could build an extension for Chrome.

In output you are supposed to get``` gmailchecker_1.1.0.crx, gmailchecker_1.1.0.xpi, gmailchecker_1.1.0.exe ```which are ready 
extension files.

Visit for more info about <a href="http://kangoextensions.com/">Kango Framwork</a>
