## DBI 785
## DBI 784
- Generating DLC unlockers

## DBI 783
- Fix for FTP installation of a large number of files + fixes in dbibackend

## DBI 782
- Fixed checking for LFS presence when determining whether a title should be blacklisted.

## DBI 781
- Fix "Extract to LFS" function

## DBI 780
- Age rating editor for installed games

## DBI 779
- Possibly(!) fix for the problem with MTP connection.

## DBI 778
- Fix hash when installing CustomXCI + signature check in integrity check

## DBI 777
- Trying to solve the problem with Can not read from URL

## DBI 776
- The promised UserAgent + a little more info than just Can not read from URL

## DBI 775
- Fixed critical bug with updates installation containing delta fragments
- Added one-click shortcut for hbmenu

## DBI 774
- hotfix msp [msp buider](https://github.com/arabianq/build_msp)

## DBI 773
- Fix for installing mods with ips files only

## DBI 772
- Archive with the new version of DBI + config + location file with the new repository

## DBI 763
Fixes
- Minor fix: Zero-filling can now be interrupted. It can also be used as a write speed benchmark for the SD card. The speed displayed corresponds to the maximum game installation speed. On a good cable, they should match.
New Features
- FTP Setting: Added an option to use MSG_WAITALL in recv. This increases FTP server transfer speed but may cause issues with some FTP clients, especially on mobile.
- Image Viewer: Added new zoom options—pixel-to-pixel and 2x zoom—alongside existing "fit to screen" and "fit to width" modes.
- 7zip Integration
Experimental Changes
- IPC System Overhaul: The entire inter-process communication (IPC) system for interacting with system services has been reworked. This version is experimental and may be unstable.

## DBI 761
In addition to screen and width scales, dot-to-dot and doubling scales have been added to image viewing.

## DBI 760
New setting for FTP: Use MSG_WAITALL in recv. Increases the transfer speed of the FTP server, but may work strangely with some FTP clients (especially on mobile)

## DBI 759
Working with 7zip. Upd. comics in cb7 format including

## DBI 758
Reworked controls for reading FB2

## DBI 757
Minor fix: now zero-filling can be interrupted. At the same time, it can be used as a benchmark for the speed of writing to the card. The speed there is the maximum speed of installing games. On a good cable, they should match.

## DBI 754
Added support for e-books in FB2 format, as well as bug fixes

## DBI 750
Various fixes + random certificates for tickets

## DBI 749
Russian encodings in the editor
Fixed
Resolved a bug with SD_Cache save operations.
Added
Support for multi-threaded HTTP downloads in title mode.
Automatic encoding detection for Windows-1251, CP 866, KOI-8, IBM855, ISO/IEC 8859-5, and MacCyrillic.

## DBI 747
fix lots of bugs in the text editor

## DBI 744
Option for previous behavior:
[MTP]
; Send Object_Removed event for files copied to Install storages
AutoremoveInstalled=true

## DBI 741
Fixed 739, 740 critical bugs
## DBI 740
Added ability to create forwarders for NRO

## DBI 739
Added the function to create NSP forwarder from any NRO with the possibility of automatic installationa and addition launch arguments

## DBI 737

## DBI 735
Fixed display of message about exhaustion of memory for internal buffers.

## DBI 731
Optional exit from DBI after installation

## DBI 729
Fixed ZSDT error 10

## DBI 727
DBI with self-updating capability
The archive should look like name.zip/DBI.nro

Is this how it will work in the config? In the General section

; UpdateURL
DBIUpdateURL=http://192.168.1.47/DBI/latest.zip

With a question about updating the config

## DBI 724
Fix for creating folder by MTR

## DBI 720
A bunch of small fixes in webdav.

## DBI 719
Support WebDAV

## DBI 718
Add WebDAV, alpha testing.

## DBI 716
Added dual progress indicators for game installation:
Separate progress bars for Read (R) and Write (W) operations

## DBI 715
Critical crash when ticket reference is missing
File browser selection state is now preserved after file installation
Various minor bug fixes and stability improvements
New popup notification for missed or wrong keys on application startup
Changed
Enhanced file browser behavior to maintain selected items state

## DBI 713
- Fixed an error `2168-0002 010000000000100D` on 712.

## DBI 712
- Huge and small bugfixes
- Fixed HTTP 404 error handling to display proper error message instead of empty response

## DBI 710
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

## DBI 709
- Initial preparation for 19.0.0 support and minor optimizations in memory usage when working with MTP.

## DBI 708
- Added function of dumping system firmware of the console (FW) into convenient .
- ZIP-archive via menu "Tools > Dump current firmware", improved work via FTP with Windows-symlinks; work with archives is moved to separate module without unnecessary dependencies on other libraries (libnx, libc, libz).

## DBI 707
- Added the function of dumping the current console system firmware (FW) into a convenient .ZIP archive via the menu "Tools > Dump current firmware" , improved work via FTP with Windows symlinks.

## DBI 705
- If there is a problem with not UltraNx on 701, here is a version with a crutch

## DBI 700
- Added function to dump current console system firmware (FW) into a .ZIP archive via "Tools > Dump current firmware"
- Improved FTP work with Windows symlinks
- Enhanced system cleaning (Tools > "Cleaning the system from garbage", Cleanup orphaned files):
- Automatic deletion of LFS-mods (e.g., Russifiers, graphics mods, cheats) from previously deleted game projects
- Improved MTP-mode:
- Closer to USB-IF technical specifications
- MicroSD, Gamecard, SD Card install storages now removable instead of fixed
- 10% faster listing of folders with numerous small files
- v698: Fixed serious bug with save backup (some files were not included in the backup)

## DBI 699
- I didn't see any change log, so probably bug fixes. I will edit this if one pops up later.

## DBI 698
- I would like to draw your attention to the fact that a serious bug with save backup has been fixed in DBI 698. 
- Some files were not included in the backup. 
- I recommend updating DBI and redoing the save backups. (By the way, JKSV has the same bug related to libnx, only it has not been fixed there)

## DBI 696
- Added ability to edit control.nacp for games on the console (3 flags: LinkingUserAccount, VideoCapture, Screenshot)

## DBI 694
- No changelog provided, possibly bugfixes.

## DBI 694
- No changelog as of yet, more than likely bugfixes.

## DBI 693
- New clipboard system for copying files from remote servers
- Added loading indicator when connecting to remote servers
- Optimization of parsing semi-wide n-space
- Support for directory icons (folder.jpg, up to 512 KB) in the lower right corner of the interface
- Improved "Update games from here" function by skipping titles with installed LFS mods

## DBI 688
- Added file name filtering with ZR+ZL key combination
- Added additional decompression stream for network transfers (HTTP, FTP) to increase download speed
- Removed Chunked Transfer
- Fixed sorting
- Improved reliability of connections to remote servers
- v678: Bugfixes and improvements in save files handling

## DBI 678
- A new version of our favorite tool. Only in russian language. As for the changelog, according to the developer, it contains some bugfixes and improvements in save files handling. Source
- As always, thanks to duckbill for still supporting his app, and shoutout to Brickachu for posting it on that russian forum.

## DBI 675
- Thanks to duckbill for sharing this, and shout-out to Brikachu for posting it on that russian forum. No idea what has been updated, sorry.

```
  _____         _     
 |     |___ ___|_|___   The Minimalistic OC Suite Of Switch
 | | | | . | . | |  _|
 |_|_|_|___|_  |_|___|
           |___|        https://github.com/we1zard/magic-suite
 powered by we1zard cc
```