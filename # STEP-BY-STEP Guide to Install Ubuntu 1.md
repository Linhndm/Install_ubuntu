# STEP-BY-STEP Guide to Install Ubuntu 18.04 LTS on your Laptop or Desktop

## Step 1: Download Ubuntu 18.04 LTS ISO File

Please make sure you have the latest version of Ubuntu 18.04 LTS, If not, please download the ISO file from the ubuntu official website: [Link here](https://www.ubuntu.com/download/desktop)

Since Ubuntu 18.04 LTS only comes in a 64-bit edition, so you can install it on a system that supports 64-bit architecture.

## Step 2) Create a Bootable Disk

Once the ISO file is downloaded then next step is to burn the downloaded ISO image into the USB/DVD or flash drive to boot the computer from that drive.

Also make sure you change the boot sequence so that system boots using the bootable CD/DVD or flash drive.

I suggest to use **Rufus** to create it. [Link here](https://rufus.ie/).

<span style="color:red"> **NOTE: "Rufus" will format (remove) everything from your USB device. If you have any important data on the USB device, please be sure to move it somewhere safe before you go through the next steps**</span>

1. While "Rufus" is open, insert your USB drive (minimum 8GB) that you wish to make Ubuntu bootable. It should be automatically detected by "Rufus." 
   ![](/Image/1.png)
2. Click "SELECT"
3. A "File Explorer" windows should show. Select "ubuntu-18.04.3-desktop-amd64" and click "Open."
4. Click "Start"
5. Click "Yes" 
6. Be sure to leave the default - Write in ISO Image mode (Recommended). Click "OK"
7. If you are sure that you have all important files on USB device moved to another location, click "OK." 
8. Rufus" will now start the function of making the USB device bootable. It will take a few minutes.
9. You will see "READY" status once the process is complete. 