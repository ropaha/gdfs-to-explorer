# Adding Google Drive File Stream to the Windows Explorer sidebar

For those of you who use OneDrive, Dropbox or Nextcloud you may have noticed that they create non-removable shortcuts in the Explorer sidebar. If you are also a Google Drive File Stream user you&#39;ll notice that Google Drive File Stream doesn&#39;t create the same shortcuts.

Following the steps below you can create the same shortcut for Google Drive File Stream.

**Disclaimer: This was only tested on Windows 10 Professional. Ensure you backup your registry before making any changes.**

## Installation

- Download this repository.
- Open  **GoogleDrive.reg**  in your favourite text editor.
- Update the TargetFolderPath so that the final value is the drive letter Google Drive File Stream is using. Ensure that you use `\\` in the drive letter. eg. `"TargetFolderPath"="G:\\"`
- Save all changes
- Double-click  **GoogleDrive.reg**  to install and ensure you click yes when prompted.

Credits: [**luke.digital**](http://luke.digital/adding-google-drive-to-the-explorer-sidebar/)
