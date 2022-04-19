# OMSK Retail PKG Installer

Method to install any retail pkgs (games, updates, apps) by using IDU OMSK Daemon on non-jailbroken PS4s

## How does it work and who is it for?

* This is a way to install any Retail PKG without the need of Debug Settings and/or any jailbreak. **Note!: You still need to own your games and/or have a license for the content you wish to launch.**
* The way it works is by utilizing IDU mode that is basically built-in every PS4's firmware. IDU (Individual Display Unit) is a mode used by Kiosk/Demo units found on game/electronic stores. Those do not use any special PS4s like TestKits or DevKits, and just use regular retail PS4s and use a IDU disk like <a href="https://ia802802.us.archive.org/1/items/redump-id-62880/PS4%20IDU%20-%202018%20Winter%20Refresh%20-%20GameStop%20%28USA%29%20-%20Disc%20Label.jpg"> this </a>.
* **Note!: Buying the disc is not needed!**
* This method can be used on any firmware (>5.00), and **does not need a jailbreak**.

## How to install and how to use it?

* **Note!: TAKE BACKUP OF SETTINGS AND SAVE DATA BEFORE INSTALLING THIS METHOD, AS IT WILL REPLACE YOUR USER WITH A GENERIC USER1!**
* Grab a USB drive, and format it as exFAT or FAT32 (FAT32 is not recommended because of 4GB filesize limit).
* Copy PS4 folder from "PS4 User1 Backup and Restore" to the root of the USB drive.
* Plug the USB to the PS4 and Navigate to Settings > System > Back Up and Restore.
* Select Restore PS4. Select OMSK Executable & Daemon restore file.
* Wait until it restores, after it's finished, you will see 2 new applications on the homescreen (★ OMSK Executable and ★ OMSK Daemon).
* Done. You can now restore your previously backed up settings and save data.

## How to send/install Retail PKGs?

* Grab a USB drive, and format it as exFAT or FAT32 (FAT32 is not recommended because of 4GB filesize limit).
* Copy all the contents of "USB Retail PKG Installer" to the root of the UBS drive.
* In "pkg" folder simply copy all your Retail PKGs. **Note!: For digital Retail Games and Demos PKGs you also need to add .rif and .idx files in "pkg" folder.**
* Back on the PS4, simply Open ★ OMSK Daemon. **It will give a error, but it's still running in the background!**
* Insert the USB drive to the PS4 and wait for a bit. You will soon get a progress notifications and all your Retail PKG will install in order.
* Done, when the pkgs are installed, simply close ★ OMSK Daemon by hitting Options button > Close Application.
* **Note!: DO NOT remove/uninstall ★ OMSK Executable. The reason you do need it, it's because it acts like a FPKG placeholder, so that the official full OMSK wouldn't install and cause problems.**

## Photos

![](/Images/Daemon.jpg)
![](/Images/DaemonOpening.jpg)
![](/Images/Executable.jpg)
![](/Images/RetailPKGInstall.jpg)
![](/Images/RetailPKGFinished.jpg)
