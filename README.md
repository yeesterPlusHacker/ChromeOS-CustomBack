<div align="center">
  <img src="/img/icon.svg" alt="logo" width="180" height="180" />
  <h1>ChromeOS CustomBack</h1>
  <p>Custom background for ChromeOS built-in pages/apps</p>
</div>

## Installation
> [!NOTE]
> The `Extensions on chrome:// URLs` flag needs to be enabled first, otherwise this extension will not work.
>
> If it is not enabled, go to `chrome://flags/#extensions-on-chrome-urls` and enable it

- Download [the latest release of this extension (in `zip`)](https://github.com/supechicken/ChromeOS-CustomBack/releases/latest) and unzip it
- Unpack the zip file by:
  - Double click the zip file in the file manager. The zip file will show contents in what looks like a flash drive
  - Drag the folder within the zip file into the Downloads folder
  - Optionally delete the zip file
- Go to [chrome://extensions](chrome://extensions) and enable Developer Mode
- Click "Pack Extension", click "Browse" under "Extension Root Directory", then click on the folder named `ChromeOS-AutoStart-main`, and click "Open"
- Click "Pack Extension", then click "Okay"
- Open the file manager, go to Downloads and drag the `.crx` file into the chrome://extensions window.
- Click "Add Extension"
- Optionally delete the generated `.crx` packaged file and `.pem` key file

## License
This project including all of its source files is released under the terms of [GNU General Public License (version 3 or later)](http://www.gnu.org/licenses/gpl.txt).