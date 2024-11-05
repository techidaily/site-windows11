---
title: Navigating Through VirtualBox USB Connectivity Glitches & Errors
date: 2024-11-01T20:24:40.483Z
updated: 2024-11-05T05:40:55.952Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Navigating Through VirtualBox USB Connectivity Glitches & Errors
excerpt: This Article Describes Navigating Through VirtualBox USB Connectivity Glitches & Errors
keywords: VirtualBox USB Issues,Fixing VBox USB Errors,VirtualBox USB Troubleshoot,USB Connection in VirtualBox,Resolve VBox USB Glitches,VirtualBox USB Optimization,Enhance VirtualBox USB Stability
thumbnail: https://thmb.techidaily.com/ce2efe940111a7e6cca801caf2d213cdd3c650dded56c51fea507b1e98fc61ee.jpg
---

## Navigating Through VirtualBox USB Connectivity Glitches & Errors

 VirtualBox lets you run many operating systems in a virtual environment without affecting your host system files. It is a great hypervisor platform perfect for trying out any operating system without installing it alongside your host operating system. But many users face an issue while connecting a USB device to their VirtualBox Virtual machine.

 VirtualBox does support USB devices out of the box but requires an extension pack to enable USB 2.0 and USB 3.0 devices. If you see the ‘Failed to Attach the USB Device’ error every time you try to connect a USB device, don’t fret. We will list out the possible reasons why you see the error code along with multiple fixes to resolve the issue.

## Reasons for the "Failed to Attach the USB Device" Error

Here are some possible reasons for the VirtualBox USB devices error.

1. The USB drive is corrupt or the USB port is not working.
2. You haven’t installed the correct VirtualBox extension pack on your system.
3. You are running an outdated version of VirtualBox.
4. You haven’t added the USB device to the virtual machine using USB settings.

 Now, you know the possible reasons why VirtualBox throws an error code when you connect a USB device. Here are the following methods you can try to fix the error code and successfully connect the USB device to the virtual machine.

## How to Fix the "Failed to Attach the USB Device" Error in Windows

 Now that we know what's potentially causing the issue, let's explore the fixes.

### 1\. Restart VirtualBox

 Before you move on to other advanced fixes, restart the VirtualBox application. If restarting the app doesn’t work, restart Windows. It will restart all the processes and services including the ones VirtualBox needs to function properly. Now, connect a USB device and try to attach it to a virtual machine in VirtualBox. If it still doesn’t show up, move to the next fix.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068411/7443" target="_top" id="2068411">
  <img src="//a.impactradius-go.com/display-ad/7443-2068411" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068411/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### 2\. Check the USB Device on the Host System

 Before trying to attach the USB device to the VirtualBox virtual machine, first check if it shows up on your host system. Launch the File Explorer and go to This PC and check if the USB drive appears there. If you don’t see the USB drive, do as follows:

1. First, open Device Manager. There are many[different ways to open the Device Manager](https://www.makeuseof.com/windows-open-device-manager/) , but a quick way is to press**Win + R** to launch the Run command box. Type**devmgmt.msc** and press the**Enter** key to launch the Device Manager.  
![Check the USB Device on the Host System](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Check-the-USB-Device-on-the-Host-System.jpg)
2. Navigate to the**Disk Drives** option and click the**arrow** icon to expand the section.
3. Find the USB drive you connected to the host system. If it is not present in the list, pull it out and reconnect it to another USB port on your system.

 If the USB port on your system malfunctions, the USB drive won’t show up in Device Manager or File Explorer. But if the USB drive doesn’t appear in the device manager even after changing the port, it could have a hardware malfunction. In that case, try connecting another USB drive to VirtualBox virtual machine.

<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2136548/16384" target="_top" id="2136548">
  <img src="//a.impactradius-go.com/display-ad/16384-2136548" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ursime.pxf.io/i/5597632/2136548/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### 3\. Install the VirtualBox Extension Pack

 VirtualBox can only attach USB 1.0 devices to a virtual machine. You need to install the extension pack to add USB 2.0 or 3.0 devices. Here’s how to do it.

1. Open VirtualBox on your system and navigate to**Help > About VirtualBox** . Note the version currently installed on your system.
2. Launch any web browser on your system and go to the[official VirtualBox download page](https://www.virtualbox.org/wiki/Downloads) .
3. Click on the build number which is present on your system. Scroll down and download its corresponding extension pack.
4. Now, open VirtualBox. Navigate to**File > Tools > Extension Pack Manager** .  
![_Install the VirtualBox Extension Pack](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/_Install-the-VirtualBox-Extension-Pack.jpg)
5. Click on the**Install** icon and select the extension pack file you downloaded in step 3.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135368/19272" target="_top" id="2135368">
  <img src="//a.impactradius-go.com/display-ad/19272-2135368" border="0" alt="https://techidaily.com" width="250" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135368/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

6. Click on the**Install** button, accept the**EULA** and click on the**I Agree** button.
7. Wait for the extension pack to install.
8. Run the virtual machine and try to connect the USB device to it.

### 4\. Update VirtualBox

 An outdated version of VirtualBox can encounter errors. So, you need to update VirtualBox to fix the underlying bugs and get access to new features offered by the developers. Here’s how to update VirtualBox on Windows.

1. Launch VirtualBox on your system. It will automatically notify you if a newer version is available. You can go to**Help > About VirtualBox** and check the current version info there.
2. Then, navigate to**Help > VirtualBox Web Site** . It will redirect you to the official website.
3. Click on the**Downloads** section and download the latest version. Also, download the corresponding extension pack.
4. Close the VirtualBox app and end all associated processes using Task Manager.
5. Run the downloaded executable file and follow the on-screen instructions to install it on your system. Also, install the extension pack as illustrated in Method 3 above.
6. Now, try to connect the USB device to the virtual machine using the settings menu.

### 5\. Configure the USB Controller in Virtual Machine Settings

 A mismatch in the USB controller settings can also produce the VirtualBox error. If you want to add a USB device to the VirtualBox virtual machine, you must select the correct USB controller option in the USB settings.

1. Open VirtualBox and click on the virtual machine to which you want to add the USB drive.
2. Click on the**Settings** icon on the top. Then click on the**USB** option in the list.
3. Firstly, click the**Enable USB controller** checkbox to enable the USB device attaching feature to the virtual machine.
4. Then, select the USB 2.0 or 3.0 controller option located below the**Enable USB controller** option.  
![Configure the USB Controller](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Configure-the-USB-Controller.jpg)
5. Now, click on the**Add new USB filter** and pick the USB device you want to connect to the virtual machine.
6. Click on the**OK** button and close the settings window. Start the virtual machine and check if the error pops up now.

<!-- affiliate ads begin -->
<a href="https://wigfever.sjv.io/c/5597632/2014849/22899" target="_top" id="2014849">
  <img src="//a.impactradius-go.com/display-ad/22899-2014849" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://wigfever.sjv.io/i/5597632/2014849/22899" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### 6\. Reinstall the VBox USB drivers

 Corrupt or missing VBox USB drivers on your system could cause the Virtual Box error code. Reinstalling the USB drivers can fix the driver issue and allow USB devices to connect with the virtual machine.

1. Launch File Explorer on your Windows system. Visit the following path:**C:\\Program Files\\Oracle\\VirtualBox\\drivers\\USB**
2. Navigate to the**Device** subfolder and find the**VBoxUSB.inf** file.
3. Right-click on the file and select the**Install** option.
4. Now, navigate to the**Filters** subfolder and locate the**VBoxUSBMon.inf** file.
5. Right-click on the file and select the**Install** option.
6. Close Virtual Box and restart your system. Connect the USB device to the virtual machine and check whether the error code pops up.

### 7\. Reinstall VirtualBox

 If all the above methods don’t solve the ‘Failed to Attach the USB Device’ Error code, consider reinstalling the VirtualBox app on your system. Here’s how to do it.

1. Press the**Win + R** key to launch the Run command box (see[how to open Windows Run](https://www.makeuseof.com/windows-open-run-command-dialog-box/) for more ways). Type**appwiz.cpl** and press the enter key. The Programs and Features window will launch.
2. Locate VirtualBox from the list of installed programs and double-click on it.  
![Reinstall VirtualBox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Reinstall-VirtualBox.jpg)
3. **UAC** will pop up. Click on**Yes** to continue.
4. Follow the on-screen prompts to uninstall VirtualBox from your system.
5. Now visit the[official VirtualBox website](https://www.virtualbox.org/wiki/Downloads) and download the app and the corresponding extension pack.
6. Open the download location and run the setup file. Follow the on-screen prompts to install and then install the extension pack as described in method 3.
7. Now, attach a USB device and start the virtual machine to check if the error code occurs or not.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137206/26400" target="_top" id="2137206">
  <img src="//a.impactradius-go.com/display-ad/26400-2137206" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137206/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Easily Connect USB Devices to Your Virtual Machine Once More

 VirtualBox needs the extension pack to enable connectivity for USB 2.0 and 3.0 devices. Check your USB devices for errors and verify that they mount properly on the host system. Reinstall USB drivers if you face the error again. Lastly, remove VirtualBox from the system and do a fresh installation.

<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>

<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-sure.techidaily.com/onvert-youtube-music-seamlessly-for-mac-users-2023-edition-for-2024/"><u>[New] Convert YouTube Music Seamlessly for Mac Users, 2023 Edition for 2024</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-2024-approved-light-up-the-screen-tips-and-steps-for-adding-gifs-to-snapchats/"><u>[Updated] 2024 Approved Light Up the Screen Tips and Steps for Adding GIFs to Snapchats</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ed-masterclass-refining-youtube-videos-through-imovie-for-2024/"><u>[Updated] Masterclass Refining YouTube Videos Through iMovie for 2024</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/a-user-friendly-guide-to-seamless-collaboration-across-different-operating-systems-via-skype-group-chats/"><u>A User-Friendly Guide to Seamless Collaboration Across Different Operating Systems via Skype Group Chats</u></a></li>
<li><a href="https://techidaily.com/how-to-update-apple-iphone-15-to-the-latest-iosipados-version-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How to Update Apple iPhone 15 to the Latest iOS/iPadOS Version? | Dr.fone</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-best-10-mock-location-apps-worth-trying-on-infinix-zero-30-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Best 10 Mock Location Apps Worth Trying On Infinix Zero 30 5G | Dr.fone</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/install-the-latest-intel-me-drivers-for-windows-systems-w10-81-and-7/"><u>Install the Latest Intel ME Drivers for Windows Systems (W10, 8.1, & 7)</u></a></li>
<li><a href="https://windows11.techidaily.com/larger-than-life-boosting-taskbar-icons-in-w11/"><u>Larger-than-Life: Boosting Taskbar Icons in W11</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-windows-11-settings-for-effortless-administration/"><u>Mastering Windows 11 Settings for Effortless Administration</u></a></li>
<li><a href="https://windows11.techidaily.com/nexus-controller-detection-woes-heres-how-to-win-them-back/"><u>Nexus Controller Detection Woes? Here's How to Win Them Back</u></a></li>
<li><a href="https://windows11.techidaily.com/tricks-to-launch-websites-after-installation/"><u>Tricks to Launch Websites After Installation</u></a></li>
<li><a href="https://howto.techidaily.com/what-to-do-if-your-samsung-galaxy-z-fold-5-auto-does-not-work-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>What To Do if Your Samsung Galaxy Z Fold 5 Auto Does Not Work | Dr.fone</u></a></li>
<li><a href="https://media-tips.techidaily.com/why-you-no-longer-have-access-to-purchasing-tv-show-selections-on-google-tv/"><u>Why You No Longer Have Access to Purchasing TV Show Selections on Google TV</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-machine-wattage-determining-computational-power-use/"><u>Windows Machine Wattage: Determining Computational Power Use</u></a></li>
<li><a href="https://windows11.techidaily.com/winning-at-learning-7-efficient-techniques-for-windows/"><u>Winning at Learning: 7 Efficient Techniques for Windows</u></a></li>
</ul></div>

