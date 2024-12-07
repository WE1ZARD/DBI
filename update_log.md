## 737

## 735
Fixed display of message about exhaustion of memory for internal buffers.

## 731
Optional exit from DBI after installation

## 729
Fixed ZSDT error 10

## 727
DBI with self-updating capability
The archive should look like name.zip/DBI.nro

Is this how it will work in the config? In the General section

; UpdateURL
DBIUpdateURL=http://192.168.1.47/DBI/latest.zip

With a question about updating the config

## 724
Fix for creating folder by MTR

## 720
A bunch of small fixes in webdav.

## 719
Support WebDAV

## 718
Add WebDAV, alpha testing.

## 716
Added dual progress indicators for game installation:
Separate progress bars for Read (R) and Write (W) operations

## 715
Critical crash when ticket reference is missing
File browser selection state is now preserved after file installation
Various minor bug fixes and stability improvements
New popup notification for missed or wrong keys on application startup
Changed
Enhanced file browser behavior to maintain selected items state

## 713
- Fixed an error `2168-0002 010000000000100D` on 712.

## 712
- Huge and small bugfixes
- Fixed HTTP 404 error handling to display proper error message instead of empty response

## 710
- Fixes for bugs that in some cases can corrupt gamesaves, timezone handling fixes, new version of libzstd with performance increase. 
- Configureble passive port range for FTP. 
- Changes in HTTP server. 
- Some deadlock fixes in rare MTP cases. 
- Support for 18.1 targeted games. 
- Fixes for archived games handling. 
- Add support for blawar's title db. 
- Fix blacklist on update check. 
- Fix memory leak in FTP sessions. 
- Fix ticket install for some corrupted tickets.
- Some optimizations and speed up in save handling.
- Added ProgramSDK version check during installation to verify game compatibility
- Added warning notification if ProgramSDK version is higher than current console firmware
- Expanded "System Information" section in Tools
- Initial preparation for FW 19.0.0 support
- Minor RAM usage optimizations for MTP USB operations

## 709
- Initial preparation for 19.0.0 support and minor optimizations in memory usage when working with MTP.

## 708
- Added function of dumping system firmware of the console (FW) into convenient .
- ZIP-archive via menu "Tools > Dump current firmware", improved work via FTP with Windows-symlinks; work with archives is moved to separate module without unnecessary dependencies on other libraries (libnx, libc, libz).

## 707
- Added the function of dumping the current console system firmware (FW) into a convenient .ZIP archive via the menu "Tools > Dump current firmware" , improved work via FTP with Windows symlinks.

## 705
- If there is a problem with not UltraNx on 701, here is a version with a crutch

## 700
- Added function to dump current console system firmware (FW) into a .ZIP archive via "Tools > Dump current firmware"
- Improved FTP work with Windows symlinks
- Enhanced system cleaning (Tools > "Cleaning the system from garbage", Cleanup orphaned files):
- Automatic deletion of LFS-mods (e.g., Russifiers, graphics mods, cheats) from previously deleted game projects
- Improved MTP-mode:
- Closer to USB-IF technical specifications
- MicroSD, Gamecard, SD Card install storages now removable instead of fixed
- 10% faster listing of folders with numerous small files
- v698: Fixed serious bug with save backup (some files were not included in the backup)

## 699
- I didn't see any change log, so probably bug fixes. I will edit this if one pops up later.

## 698
- I would like to draw your attention to the fact that a serious bug with save backup has been fixed in DBI 698. 
- Some files were not included in the backup. 
- I recommend updating DBI and redoing the save backups. (By the way, JKSV has the same bug related to libnx, only it has not been fixed there)

## 696
- Added ability to edit control.nacp for games on the console (3 flags: LinkingUserAccount, VideoCapture, Screenshot)

## 694
- No changelog provided, possibly bugfixes.

## 694
- No changelog as of yet, more than likely bugfixes.

## 693
- New clipboard system for copying files from remote servers
- Added loading indicator when connecting to remote servers
- Optimization of parsing semi-wide n-space
- Support for directory icons (folder.jpg, up to 512 KB) in the lower right corner of the interface
- Improved "Update games from here" function by skipping titles with installed LFS mods

## 688
- Added file name filtering with ZR+ZL key combination
- Added additional decompression stream for network transfers (HTTP, FTP) to increase download speed
- Removed Chunked Transfer
- Fixed sorting
- Improved reliability of connections to remote servers
- v678: Bugfixes and improvements in save files handling

## 678
- A new version of our favorite tool. Only in russian language. As for the changelog, according to the developer, it contains some bugfixes and improvements in save files handling. Source
- As always, thanks to duckbill for still supporting his app, and shoutout to Brickachu for posting it on that russian forum.

## 675
- Thanks to duckbill for sharing this, and shout-out to Brikachu for posting it on that russian forum. No idea what has been updated, sorry.