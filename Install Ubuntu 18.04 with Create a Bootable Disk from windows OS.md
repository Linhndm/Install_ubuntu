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

    ![](/Image/2.png)

3. A "File Explorer" windows should show. Select "ubuntu-18.04.3-desktop-amd64" and click "Open."

    ![](/Image/3.png)

4. Click "Start"

    ![](/Image/4.png)

5. Click "Yes" 

    ![](/Image/5.png)

6. Be sure to leave the default - Write in ISO Image mode (Recommended). Click "OK"

    ![](/Image/6.png)

7. If you are sure that you have all important files on USB device moved to another location, click "OK." 

    ![](/Image/7.png)

8. Rufus" will now start the function of making the USB device bootable. It will take a few minutes.
   
    ![](/Image/8.png)

9.  You will see "READY" status once the process is complete. 

    ![](/Image/9.png)

## Step 3: Boot from Flash Drive

1. Boot from the USB device.

    How to boot from the USB device all depends on the motherboard you have. Get into the "BIOS" of your motherboard or access the "Boot Manager" to select the bootable USB device that has "Ubuntu 18.04 LTS" made with "Rufus."

    *Hint: On some motherboards, repeatedly pressing **F2** or **DEL** or <F12> just after you pressed the power button, will allow you access "BIOS" or "Boot Manager." Please reference your PC/motherboard manufacture for the proper key to access "BIOS" or "Boot Manager."*

2. Select "Try Ubuntu without installing" 
   
   ![](/Image/10.png)

3. Click on "Live session user" 

   ![](/Image/11.png)

4. Double click "Install Ubuntu 18.04 LTS" icon
   
    ![](/Image/12.png)

5. Select the desired language and click "Continue."

    ![](/Image/13.png)

6. Select desired "Keyboard layout" and click "Continue."
   
   ![](/Image/14.png)   
7. Preparing to Install Ubuntu and other Software and click "Continue."
  
    In the next screen, you’ll be provided following beneath options including:
    * Type of Installation: Normal Installation or Minimal installation, If you want a minimal installation then select second option otherwise go for the Normal Installation. In my case I am doing Normal Installation
    * Download Updates While Installing Ubuntu (select this option if your system has internet connectivity during installation)
    * Install third party software for graphics and Wi-Fi hardware, MP3 and additional media formats  Select this option if your system has internet connectivity)

    ![](/Image/15.png)

8. Select the appropriate Installation Type 

    Next the installer presents you with the following installation options including:

    * Erase Disk and Install Ubuntu
    * Encrypt the new Ubuntu installation for security
    * Use LVM with the new Ubuntu installation
    * Something Else
    ***
    **Erase Disk and Install Ubuntu** – Choose this option if your system is going to have only Ubuntu and erasing anything other than that is not a problem. This ensures a fresh copy of Ubuntu 18.04 LTS is installed in your system.

    **Encrypt the new Ubuntu installation for security** – Choose this option if you are looking for extended security for your disks as your disks will be completely encrypted. If you are beginner, then it is better not to worry about this option.

    **Use LVM with the new Ubuntu installation** – Choose this option if you want to use LVM based file systems.

    **Something Else** – Choose this option if you are advanced user and you want to manually create your own partitions and want to install Ubuntu along with existing OS (May be Windows or other Linux Flavor)

    ![](/Image/16.png)

9. Make sure that the desired hard drive "Ubuntu 18.04 LTS"  is to be installed on is selected.
    
    ![](/Image/17.png)

10. If the hard drive is new and "Something else" was selected in the earlier section, the hard drive will not have any partition table. In that case, click "New Partition Table..."

    ![](/Image/18.png)

11. Click "Continue."

    ![](/Image/19.png)

12. Select "free space" and click on the "+" icon.

    ![](/Image/20.png)

13. Create an "EFI System Partition" of 512 MB disk space, with the following settings marked in the screenshot below, and click "OK."

    ![](/Image/21.png)

14. Create a "/boot" partition of 512 MB disk space, with the following settings marked in the screenshot below, and click "OK."
    
    ![](/Image/22.png)

15. Create a "/ (root)" partition and give it the rest of the free disk space. Make sure it has the follow settings marked in the screenshot below, and click "OK."
    
    ![](/Image/23.png)

16. Once all the partitions have been created, it should look something like the screenshot below. Click on "Install Now."
    
    ![](/Image/24.png)

17. Click "Continue."
    
    ![](/Image/25.png)

18. Select the desired "Location" from the map or by typing in the text box. Once the desired location is selected, click "Continue."
    
    ![](/Image/26.png)

19. Fill in the details and click "Continue."
    
    ![](/Image/27.png)

20. The installation should then start.
    
    ![](/Image/28.png)

21. It should take a few minutes for the installation to complete. Once it's completed, the following window should appear. Click "Restart Now."
    
    ![](/Image/29.png)

22. The PC should restart and boot into the "Ubuntu 18.04 LTS" operating system. Once the PC has booted, a login window should appear. Type in your "Password" that you have set during installation and click "Sign In."
    
    ![](/Image/30.png)

23. Once the above steps are completed, the PC should be logged in to the new "Ubuntu 18.04 LTS" operating system.
