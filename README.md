# Adding Google Drive File Stream (GDFS) to the Windows Explorer sidebar

For those of you who use OneDrive, Dropbox or Nextcloud you may have noticed that they create non-removable shortcuts in the Explorer sidebar. If you are also a Google Drive File Stream user you&#39;ll notice that Google Drive File Stream doesn&#39;t create the same shortcuts.

Following the steps below you can create the same shortcut for Google Drive File Stream.

**Disclaimer: This was only tested on Windows 10 Professional. Ensure you backup your registry before making any changes.**

## Requirements

Check your Google Drive File Stream version is supported.

![Google Drive File Stream version](https://img.roga.io/GDFS-Version2.jpg)

Supported Versions:

- 43.0.8.0
- 42.0.11.0
- 41.0.2.0

## Installation

1. Download a release matching your Google Drive File Stream version.
2. Open Google Drive File Stream, go to settings and check witch drive letter is used. ![Google Drive File Stream drive letter](https://img.roga.io/GDFS-Drive2.jpg)
3. Open **add-gdfs.reg** in your favourite text editor.
4. Update the TargetFolderPath so that the final value is the drive letter Google Drive File Stream is using (see 2.). Ensure that you use `\\` in the drive letter. eg. `"TargetFolderPath"="G:\\"`
5. Save all changes
6. Double-click **add-gdfs.reg** to install and ensure you click yes when prompted.

## Result

Your Explorer sidebar should look now like this

![Google Drive File Stream Explorer sidebar](https://img.roga.io/GDFS-Explorer2.jpg)

## Uninstall

1. Double-click **remove-gdfs.reg** to uninstall and ensure you click yes when prompted.

Credits: [**luke.digital**](http://luke.digital/adding-google-drive-to-the-explorer-sidebar/)
