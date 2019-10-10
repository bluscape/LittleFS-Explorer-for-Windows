# LittleFS Explorer for Windows

LittleFS (LFS) is a fail-safe file system designed for microcontrollers: https://github.com/ARMmbed/littlefs

LittleFS Explorer (LFSE) is a file explorer for LFS in Windows. 

![GitHub Logo](/images/ExplorerWAbout.jpg)

## Features
* Automatically detects, mount and unmount LFS formatted disks.
* Format any accessible disk to LFS.
* Automatically detects the operating system disk and prevents formatting the operating system disk.
* Define custom LFS configuration parameters when formatting a disk.
* Browse folders.
* Drag and drop, single or multiple, files and folders from Windows explorer to LFSE.
* Create new folders.
* Rename and delete files and folders.
* View and edit files with the default associated Windows program.
* View and edit files with a specific Windows program.
* Grid view or detail view (file size).

## Pending features
* Migrate from a previous version of LFS (LFS_MIGRATE). 
* Drag and drop, single or multiple, files and folders from LFSE to Windows explorer. 
* Folder and file search.
* Cut, copy and paste folders and files inside LFSE.

## User Guide, Implementation, Compatibility, Testing, etc.
https://bluscape.blog/2019/10/01/littlefs-explorer-lfse-for-windows/

## Revision history

### Revision format
vA.B.C where A = Major Version, B = Minor Version and C = Beta Version. If C = Zero, it is a stable release.

#### v1.0.2 (Beta)
* Jumped a Beta version since the first release was supposed to be a Beta (v1.0.1)
* Corrected the file copy dialog when overwriting existing files
* If the LFS configuration has not been defined, it will display the LFS configuration dialog prior to mounting or formatting the disk
* Added a volume delete option to the disk popup menu
* Corrected some issues with the LFS DLL disk access functions
* LFSE has only been tested with an SD card with the following parameters (Block Size = 512, Read Size = 512, Prog Size = 512). Could someone please leave feedback if they test with a device with different parameters.

#### v1.0.0 (Beta)
* First release of LittleFS Explorer for Windows
