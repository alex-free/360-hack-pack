# [360 Hack Pack - The Ultimate Xbox 360 Starter Pack](readme.md) -> Changelog

## Version 1.0.4 (12/8/2025)

Changes:

* Updated [XeUnshackle](https://github.com/Byrom90/XeUnshackle) to v1.0.3 BETA.

* Updated [FreeMyXe](https://github.com/FreeMyXe/FreeMyXe) to v1.1.

* The above changes add compatibility with [Bad Storage (2TB HDD support)](https://fatxplorer.eaton-works.com/bad-storage/). They also seem to increase reliability and speed improvements for the exploit to me anyways...

TODO:

* Patch Aurora.xex/make it boot automatically after FreeMyXe. This already works for XeUnShackle, but I need to integrate actually patching of the Aurora before making the zip file for FreeMyXe to auto-launch after exploit.

* Implement Dashboard exploit/HDD avatar exploit.

* More options for original Xbox compatibility included by default.

* ?? You tell me. I've been very happy with this. All my games from Fallout 3+GOTY DLC to GTA V have worked since pretty much the begining. 

---------------------------------------

## Version 1.0.3 (8/8/2025)

Changes:

* Updated [BadUpdate](https://github.com/grimdoomer/Xbox360BadUpdate) to v1.2. This has some serious [success rate improvements](https://github.com/grimdoomer/Xbox360BadUpdate/pull/24) compared to the previous releases of BadUpdate with noticable [results](https://gbatemp.net/threads/new-xbox-360-hypervisor-exploit-software-based.662219/post-10706382).

* Xell Reloaded for Winchester (a build I have created with the updated LibXennon toolchain that is now Winchester compatible, see this [thread](https://gbatemp.net/threads/xell-reloaded-build-compatible-with-all-consoles-including-winchester.670339/)) is now available. To start it on your console, launch  `apps\xell-reloaded-v0.993-d4f08b4-winchester\default.xex` with Aurora file manager or XeXMenu. This uses Xell Launch to bring up Xell Reloaded. Note that this is labeled specifically 'for Winchesters' because there is a [report](https://gbatemp.net/threads/xell-reloaded-build-compatible-with-all-consoles-including-winchester.670339/post-10659739) that it does not work on at least a Jasper v3. As I only have a Winchester at the moment, I can't debug anything for other consoles. However I can [confirm](https://gbatemp.net/threads/xell-reloaded-build-compatible-with-all-consoles-including-winchester.670339/post-10662028) the last official Xell Reloaded release works for consoles older then the Winchester model. If you want to use Xell Reloaded on a console older then the Winchester, start `apps\xell-reloaded-v0.993\default.xex`.

* Substantial improvements to `build` and `360hp` scripts. 360hp script now works again on Fedora Linux. The `unrar` command is now used once again to extract all downloaded rar files in download mode, since Fedora has the insanity to remove rar support from p7zip (but still allow the GUI Gnome desktop shipped with official ISOs to support extracting them).

---------------------------------------

* [360-hack-pack-v1.0.3-freemyxe-ready-to-copy.zip](https://github.com/alex-free/360-hack-pack/releases/download/v1.0.3/360-hack-pack-v1.0.3-freemyxe-ready-to-copy.zip) _Complete file set for FreeMyXe_

* [360-hack-pack-v1.0.3-xeunshackle-ready-to-copy.zip](https://github.com/alex-free/360-hack-pack/releases/download/v1.0.3/360-hack-pack-v1.0.3-xeunshackle-ready-to-copy.zip) _Complete file set for XeUnshackle_

* [360-hack-pack-v1.0.3-downloader.zip](https://github.com/alex-free/360-hack-pack/releases/download/v1.0.3/360-hack-pack-v1.0.3-downloader.zip) _Downloader for Linux/Mac OS_

---------------------------------------

## Version 1.0.2 (4/7/2025)

Changes:

* Added the ability to use [XeUnshackle](https://github.com/Byrom90/XeUnshackle) or [FreeMyXe](https://github.com/FreeMyXe/FreeMyXe).

* XeUnshackle sets Aurora as your default launcher.

* Added [HDD Compat Partition Fixer (for original Xbox backwards compatibility)](https://consolemods.org/wiki/File:Hdd_compat_partition_fixer_v1.zip) v1.

* Added [Hacked Compatibility Files (for original Xbox backwards compatibility)](https://consolemods.org/wiki/Xbox_360:Original_Xbox_Games) 12-09-2019.

* Added [Xell-Reloaded](https://github.com/Free60Project/xell-reloaded) v0.993. This is setup on the FreeMyXe editions to allow it to be loaded immedietly after exploit as an option (rather then the stock NXE dashboard). On the XeUnshacked editions, Xell-Reloaded is at `apps\xell-reloaded-v0.993`. Note: Xell-Reloaded does not work on Xbox 360 E Winchester (it loads to a black screen, with no recourse other then to reboot the console and not use it when asked by FreeMyXe) so don't bother yet until this issue is [addressed](https://github.com/FreeMyXe/FreeMyXe/issues/14#issuecomment-2782039804) if your on an Xbox 360 E Winchester. Every other console revision works fine.

* Improved folder name conventions in `apps` folder.

* Downloader is more verbose on what it is doing.

* Creates a `backup` folder that you can place your important files (such as NAND flash backup, cpu key txt, etc.).

---------------------------------------

* [360-hack-pack-v1.0.2-freemyxe-ready-to-copy.zip](https://github.com/alex-free/360-hack-pack/releases/download/v1.0.2/360-hack-pack-v1.0.2-freemyxe-ready-to-copy.zip) _Complete file set for FreeMyXe_

* [360-hack-pack-v1.0.2-xeunshackle-ready-to-copy.zip](https://github.com/alex-free/360-hack-pack/releases/download/v1.0.2/360-hack-pack-v1.0.2-xeunshackle-ready-to-copy.zip) _Complete file set for XeUnshackle_

* [360-hack-pack-v1.0.2-downloader.zip](https://github.com/alex-free/360-hack-pack/releases/download/v1.0.2/360-hack-pack-v1.0.2-downloader.zip) _Downloader for Linux/Mac OS_

---------------------------------------

## Version 1.0.1 (3/28/2025)

Changes:

* Now includes a build of Simple 360 Nand Flasher v1.5b (latest commit as of 3/27/2025) using the new Read Only target. The Read Only builds do not allow writing to the NAND, only dumping of it. This is specifically for BadUpdate consoles that can't write to NAND without bricking.

---------------------------------------

* [360-hack-pack-v1.0.1-ready-to-copy.zip](https://github.com/alex-free/360-hack-pack/releases/download/v1.0.1/360-hack-pack-v1.0.1-ready-to-copy.zip) _Complete file set_

* [360-hack-pack-v1.0.1-downloader.zip](https://github.com/alex-free/360-hack-pack/releases/download/v1.0.1/360-hack-pack-v1.0.1-downloader.zip) _Downloader for Linux/Mac OS_

---------------------------------------

## Version 1.0 (3/24/2025)

Changes:

* Initial release.

----------------------------------------------------

* [360-hack-pack-v1.0-ready-to-copy.zip](https://github.com/alex-free/360-hack-pack/releases/download/v1.0/360-hack-pack-v1.0-ready-to-copy.zip) _Complete file set_

* [360-hack-pack-v1.0-downloader.zip](https://github.com/alex-free/360-hack-pack/releases/download/v1.0/360-hack-pack-v1.0-downloader.zip) _Downloader for Linux/Mac OS_

---------------------------------------