---
title: How to Fix the Camera App When It Can't Save Photos or Videos in Windows
date: 2024-06-25T11:59:22.768Z
updated: 2024-06-26T11:59:22.768Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Fix the Camera App When It Can't Save Photos or Videos in Windows
excerpt: This Article Describes How to Fix the Camera App When It Can't Save Photos or Videos in Windows
keywords: Windows Photo Saving Issue,Fixed Windows Camera App,Solve Windows Video Capture Error,Fix Windows Photo Not Saving,Resolving Windows Image Save Failure,Troubleshoot Windows Camera Problems,Windows Media Saving Solution
thumbnail: https://thmb.techidaily.com/4599f50b602c6cf6fd2e770298cbc820ac519a960550c4309b2e36a11fd875c9.jpg
---

## How to Fix the Camera App When It Can't Save Photos or Videos in Windows

 The Windows Camera app is known for its simplicity and user-friendliness, making it a go-to choice for capturing and preserving memories. However, there are occasions when you encounter problems with the app, like the inability to save photos or videos on your device. This can be particularly frustrating, especially if you intend to share or edit these media files later. Below, we walk you through the steps to resolve issues with the Camera app when it fails to save photos or videos in Windows.

## 1\. Check the Storage Permissions

 If your laptop or computer’s camera doesn’t save photos or videos, we recommend starting your troubleshooting journey by ensuring it has sufficient permissions to store data on your device.

 Here is how you can quickly do that:

1. Press the **Win** \+ **I** keys together to open the Settings app.
2. Choose **Privacy & security** from the left pane.
3. Head over to the App permissions section and choose **Camera** from the list of options available.
4. Turn the toggle on for **Camera access**. You can now close the Settings app and check if the problem is resolved.  
![Enable the Camera Access in the Privacy and Security Tab of the Windows Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/3-enable-the-camera-access-in-the-privacy-and-security-tab-of-the-windows-settings-app.jpg)

 While you are at it, you can also re-add your saved location for storing data and see if that makes a difference.

1. Open the Settings app and navigate to **System** \> **Storage** \> **Where new content is saved**.
2. Expand the dropdown for "New videos and photos will save to:" and pick another location. For instance, if you have a USB device, pick that.  
![Pick a different location to save photos and videos](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/choose-a-different-location.jpg)

 Here is an alternate way of changing the location:

1. Open a Run dialog by pressing the **Win** \+ **R** keys together.
2. Type “%APPDATA%\\Microsoft\\Windows\\Libraries” in Run and click **Enter**. This will launch the libraries section of the File Explorer.
3. Right-click on Camera roll and choose **Properties** from the context menu.
4. In the following dialog, click on the **Add** button.  
![Change where the camera will save photos and videos](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/change-location-for-camera.jpg)
5. Now, add your new preferred location and choose **Set Default Save Location**.
6. Hit **Apply** \> **OK** to save the changes and check if the issue is resolved.

## 2\. Update the Camera Drivers

 Another reason why your camera app might be acting is because of outdated or corrupt drivers. Such issues can be resolved by updating the drivers using either the Device Manager utility or the Windows Update option.

 Here is how you can update your camera driver using the Device Manager:

1. Press the **Win** \+ **S** keys together to open Windows Search.
2. Type "Device Manager" in the search bar and click **Open**.
3. In the following window, expand the Cameras section and right-click on your camera driver.
4. Choose **Update driver** \> **Search automatically for drivers**.  
![Update the Relevant Camera Driver From Windows Device Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/4-update-the-relevant-camera-driver-from-windows-device-manager.jpg)
5. The utility will now start scanning for an updated version of your driver in the system. If it finds any, follow the on-screen instructions to install it. If it does not, you can click on **Search for updated drivers on Windows Update** to see if an update is available.

 You can also head over to your manufacturer’s website, download an updated version from there, and then install it manually.

## 3\. Repair the Camera App

 The camera app itself can be dealing with an inconsistency or a corruption error which might be preventing it from saving photos and videos. To check if this is the case in your situation, you can make use of the repair option for the camera available in the Windows Settings app.

 This feature will do the following to help with the problem:

* Scan for any missing or corrupted files and reinstall them
* Check the Windows Registry and app-specific configuration settings to ensure they are correctly configured
* Verify and reconfigure any dependencies critical for the app to function

 Follow these steps to repair the app:

1. Open the Settings app and choose **Apps** from the left pane.
2. Click on **Apps & features**.
3. Head over to the App list section and click on the three dots associated with the Camera app.
4. Choose **Advanced options** from the context menu.
5. In the Reset section, click on the **Repair** button.  
![Repair Camera app from Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/Repair-Camera.jpg)
6. Wait for the process to complete. This may take a while, depending upon the complexity of the underlying problems.

 Once the app is successfully repaired, check if the issue is fixed. If the app fails to repair, you should see a “We couldn’t repair this app. Try again in a bit.” In that case, you can try using the System File Checker for a more detailed check of the system, or move to the next method below.

## 4\. Check Your Antivirus and Firewall Settings

 Are you using a third-party security program on your Windows device? If so, there is a good chance that the security program is interfering with the operation of the Camera app, preventing it from saving the data.

 To determine if this is true, you can [disable your antivirus program temporarily](https://www.makeuseof.com/cant-enable-windows-firewall/). If you are using the security features offered by Windows, you can [turn off Windows Security](https://www.makeuseof.com/temporarily-disable-windows-security-windows-11/) for some time and retry saving your photos and videos.

 It is, however, important to note that disabling these programs can make your computer vulnerable to risks, so we recommend turning them back on immediately once you are done.

## 5\. Reset or Reinstall the Camera App

 Finally, if the steps listed above have not worked, you can try resetting or reinstalling the camera app as the last resort.

 Resetting the app is a less drastic measure that will restore the camera app's settings to their default values. If this does not fix the problem, you can proceed with a reinstallation, which will essentially remove the existing app from your system.

 You can then download and install a fresh copy from the Microsoft Store (or from another trusted source). It will fix any issues with the previous installation that may be causing the problem.

 To reset the app, open the **Advanced options** menu for the Camera app as we described above. Click on the **Reset** button and follow the on-screen instructions to proceed. To uninstall, launch the Powershell utility as an administrator and execute the following command:

`get-appxpackage *Microsoft.WindowsCamera* | remove-appxpackage`

 Once the command executes, launch Microsoft Store and install the Camera app again.

## Capture and Save Your Moments Again on Windows

 A malfunctioning Camera app that can't save your photos or videos can be a real inconvenience, but it is not impossible to fix. Hopefully, the methods above will help you restore your Camera app's functionality and continue capturing life's moments with confidence. To prevent this issue from occurring in the future, it is best to keep your camera drivers up-to-date at all times.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://windows11.techidaily.com/fix-silent-mode-glitches-on-windows-word-reading-feature/"><u>Fix Silent Mode Glitches on Windows' Word Reading Feature</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-fix-for-invisible-login-window-in-win1011/"><u>Quick Fix for Invisible Login Window in Win10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/launching-the-system-rescue-console-easily/"><u>Launching the System Rescue Console Easily</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-correct-hardware-detection-errors-in-win/"><u>How To Correct Hardware Detection Errors in Win</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-the-mystery-of-non-existent-mmc-snaps/"><u>Unraveling the Mystery of Non-Existent MMC Snaps</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-ais-pitfalls-the-risks-of-chatbots-in-windows-keys/"><u>Navigating AI's Pitfalls: The Risks of Chatbots in Windows Keys</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-a-non-compatible-device-after-windows-11-installation/"><u>Fixing a Non-Compatible Device After Windows 11 Installation</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-failed-zip-file-extraction-in-windows-11/"><u>Troubleshooting Failed: Zip File Extraction in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-windows-11s-insufficient-uninstall-rights/"><u>Fixing Windows 11'S Insufficient Uninstall Rights</u></a></li>
<li><a href="https://windows11.techidaily.com/pursue-peak-performance-customizing-graphics-settings-for-games/"><u>Pursue Peak Performance: Customizing Graphics Settings for Games</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-change-lock-screen-wallpaper-on-oneplus-11-5g-by-drfone-android/"><u>How to Change Lock Screen Wallpaper on OnePlus 11 5G</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/2024-approved-a-compreenas-guide-to-high-quality-mov-recording-in-windows-10/"><u>2024 Approved  A Compreenas Guide to High-Quality MOV Recording in Windows 10</u></a></li>
<li><a href="https://apple-account.techidaily.com/how-to-remove-phone-number-from-your-apple-id-from-your-iphone-6-plus-by-drfone-ios/"><u>How To Remove Phone Number From Your Apple ID from Your iPhone 6 Plus?</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/2024-approved-top-10-facebook-jail-secrets-to-avoid-being-blocked-get-out-of-it/"><u>2024 Approved  Top 10 Facebook Jail Secrets to Avoid Being Blocked / Get Out of It</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-2024-approved-mastering-recording-deciding-between-slower-and-faster-frame-rates/"><u>[New] 2024 Approved  Mastering Recording  Deciding Between Slower and Faster Frame Rates</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-in-2024-mov-file-keeping-hacks-for-new-win-11-users/"><u>[New] In 2024, .MOV File Keeping Hacks for New Win 11 Users</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/2024-approved-effortless-calls-combining-youtube-and-green-screens/"><u>2024 Approved  Effortless Calls  Combining YouTube & Green Screens</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-in-2024-going-back-in-space-and-time-rewind-your-instagram-video/"><u>[Updated] In 2024, Going Back in Space and Time  Rewind Your Instagram Video</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/a-step-by-step-approach-cropping-and-exporting-your-videos-to-instagram-for-2024/"><u>A Step-by-Step Approach  Cropping & Exporting Your Videos to Instagram for 2024</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-explore-the-best-8-mirrorless-cameras-for-youtube-vloggers/"><u>2024 Approved  Explore the Best  8 Mirrorless Cameras for YouTube Vloggers</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>