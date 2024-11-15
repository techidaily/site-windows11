---
title: Using iCloud Keychain for iOS/Android Network Access
date: 2024-11-08T16:17:53.973Z
updated: 2024-11-15T16:20:37.836Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Using iCloud Keychain for iOS/Android Network Access
excerpt: This Article Describes Using iCloud Keychain for iOS/Android Network Access
keywords: ICloud Keychain Login,IOS Keychain Sync,Android Network Share,ICloud Passcode Sharing,Cross-Platform Credential,Apple Security Storage,Cloud Account Access
thumbnail: https://thmb.techidaily.com/90e284fb29c37a4c0c2a2e6970ee3fa6b56745fa434982e234c62e6bb83237e0.jpg
---

## Using iCloud Keychain for iOS/Android Network Access

 If you searched for ways to access your Windows files from your Android/iOS devices, chances are you landed on guides suggesting you to download all sorts of external applications, free or paid. Did you know that you absolutely don't need any external application for file transfers across your devices? Well, now you do. Windows Network Share is a really easy way of sharing files, folders, or entire drives across devices on the same network. Let's learn how to set up Windows Network Share to access your PC files from Android/iOS.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## What Is Network File Sharing?

 When you want to share a file or folder with someone, sometimes it is faster to share it over your local network, rather than uploading to the cloud or looking for a USB flash drive. This process is called network file sharing. File Transfer Protocol (FTP) is also a valid option for file sharing remotely or on the local network but, it's much more of a hassle to set up than Windows Network Share.

 Windows Network Share utilizes the SMB protocol internally to make files, directories, or, entire drives available for read/write access for devices on the local network. While it's super easy and swift to set up, it's also a common target for adversaries. So, it's wise that you learn [how the SMB protocol works and some common SMB vulnerabilities](https://www.makeuseof.com/what-is-smb-protocol-and-what-are-its-risks/) to ensure that your network perimeter isn't breached.

## How to Share a Windows Drive on Your Local Network

 To access your computer's files, you need to share them on the local network. For the demonstration, I'll be sharing a drive on the local network. If you wish to share a folder or a single file instead, you can follow the same steps but with only the folder(s) and file(s) selected.

 Before you dive into the steps, it's recommended you [create a separate, local Windows user account](https://www.makeuseof.com/windows-11-create-local-user-account/) to be used solely for network drive access.

 Here are the steps to share files on the local network in Windows 10/11:

1. **Right-click** on the drive you want to share.
2. From the drop-down menu, click on **Properties**.
3. In the **Properties** menu, go to the **Sharing** tab.  
![sharing tab open in properties menu of a drive-1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/sharing-tab-open-in-properties-menu-of-a-drive-1.jpg)
4. Click on **Advanced Settings** in the new pop-up menu, check the **Share this folder** box, and wait, it's not over yet. Now to prevent unsolicited access to your locally shared drives, click on **Permissions**.

5. In the new menu that pops up, click on **Add**. Yet another box should pop up. Here, type in the username of your user account. Use a dedicated user account only for network access or use your primary account's username and press **Enter**. You should find your name is present on the list of users with permission to the shared drive.  
![Adding a new user in the access group of the shared drive](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/adding-a-new-user-in-the-access-group-of-the-shared-drive.jpg)
6. Finally, click on your account name, and in the **Permissions for <account name>** section, check the **Full Control** box and hit **Apply**.  

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2144280/7443" target="_top" id="2144280">
  <img src="//a.impactradius-go.com/display-ad/7443-2144280" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144280/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![Adding permissions to the user account and confimring changes by pressing on Apply](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/adding-permissions-to-the-user-account-and-confimring-changes-by-pressing-on-apply.jpg)

 That's all the steps to share your drive on the local network. However, if you run into any trouble, it's recommended you check out the [dedicated guide on enabling Windows Network Share](https://www.makeuseof.com/how-network-file-share-windows-10/).

## How to Access Your Windows Files From an Android Device

 Now that you have shared the drive on the local network you'll be able to access your newly shared drives and files from your Android device in just a few taps. Make sure your Android device and Windows PC are connected to the same Wi-Fi network. With these checks out of the way, let's look at the steps to access Windows network shared files from Android:

1. Fire up the **Files** application on your Android device.
2. On the **Files** application, scroll to **Network Storage** and tap on it.
3. Inside **Network Storage**, tap on **Add network storage**. You might be asked to select an option from a list of protocols. Tap on **Network Drive** or any option with **SMB** in the name.
4. Your device will start to scan for locally shared drives. Wait for it to locate your Windows drive. If your device is unable to locate it follow the next steps. First, you need to [find the IP address of your Windows PC](https://www.makeuseof.com/find-ip-mac-address-windows-powershell/).
5. After noting the IP address, go back to your Android device and tap on **Add Manually**.
6. In the new window, type in the IPv4 address you copied earlier into the Address field. Then, type **445** into the **Port** field. Finally, fill in the **Username** and **Password** fields with your account credentials and hit on **Add** or **Connect**.

![Selecting Network Share on Files app](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/selecting-network-share-on-files-app.jpg)

![Selecting SMB Protocol](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/selecting-smb-protocol.jpg)

<!-- affiliate ads begin -->
<span id="1424527">
					<video width="864" height="1536" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1424527.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/16446-1424527">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1424527.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Flaganoo.pxf.io%2Fc%2F5597632%2F1424527%2F16446'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1424527/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![Manually adding the device and account details](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/manually-adding-the-device-and-account-details.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2100542/7443" target="_top" id="2100542">
  <img src="//a.impactradius-go.com/display-ad/7443-2100542" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2100542/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![Access established to the drive](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/access-established-to-the-drive.jpg)

Close

 Now, you should be able to access files on your Windows PC from your Android device. You can modify the files or download them to your Android device. All done without ever needing any external application!

 On some devices, such as Samsung phones, when you click on **Network Storage**, you might be asked to update the Files app to add the network access functionality. Proceed to do so, and then return to the guide.

## How to Access Your Windows Files From an iOS Device

 The steps to access Windows files from iOS are pretty much identical to the steps required for Android devices. Here's how you can access your Windows PC's files from iOS:

1. Before opening your iOS device. You need to grab the IP address of your Windows PC. There are multiple ways to do it. The easiest one being typing in **cmd** in the search box and then using the **ipconfig** command to fetch network-related details. Note down the value of the IPv4 field.
2. Fire up the **Files** application on your iOS device.
3. Click on the three horizontal dots (ellipsis) in the top right corner. From there, select **Connect to Server**.
4. A new window should open up asking you to input the IP address of the shared drive. Type in the IP address that you previously noted down and tap on **Next**.
5. Then, you will be prompted to enter the user account credentials to access the shared drive. Type them in and tap on **Next**.

![Connecting to the shared drive](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/connecting-to-the-shared-drive.jpeg)

<!-- affiliate ads begin -->
<a href="https://aidotcom.pxf.io/c/5597632/2129042/19576" target="_top" id="2129042">
  <img src="//a.impactradius-go.com/display-ad/19576-2129042" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aidotcom.pxf.io/i/5597632/2129042/19576" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![Typing in the IP of the Windows PC](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/typing-in-the-ip-of-the-windows-pc.jpeg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1975802/19272" target="_top" id="1975802">
  <img src="//a.impactradius-go.com/display-ad/19272-1975802" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1975802/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![Typing in user account credentials](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/typing-in-user-account-credentials.jpeg)

![Access established to the drive](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/access-established-to-the-drive.jpeg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1868495/19272" target="_top" id="1868495">
  <img src="//a.impactradius-go.com/display-ad/19272-1868495" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1868495/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![The shared drive being listed on the Browse Menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/the-shared-drive-being-listed-on-the-browse-menu.jpeg)

Close

 Now you should be able to view the files on the shared drive. You can now download, upload or modify the local files on your Windows PC with ease and without having to download any third-party application.

## Access Your PC Files on iOS/Android Without Third-Party Apps

 Now that you know how to access your PC files using Windows Network Share, uploading, downloading, and modifying files should be super easy to do. You won't have to rely on downloading and testing third-party applications for minor tasks like copying over a PDF file from your Windows PC to your Android/iOS devices.

 If you wish to share files between computers on the same network, that is possible as well. But, for heavy file sharing between two computers, a few alternatives to network sharing may be worth checking out if you'll be sharing large chunks of data.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-zero.techidaily.com/024-approved-ignite-your-creativity-making-dynamic-splitscreen-videos/"><u>[New] 2024 Approved Ignite Your Creativity Making Dynamic Splitscreen Videos</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-enhancing-filmmaking-top-choices-in-camera-lenses-for-2024/"><u>[New] Enhancing Filmmaking Top Choices in Camera Lenses for 2024</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-low-end-pc-visual-logging-software/"><u>[Updated] Low-End PC Visual Logging Software</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/asus-launches-the-pioneering-rog-nuc-desktop-pc-with-high-end-specs-including-core-ultra-9-processors-and-rtx-4070-graphics-from-1629/"><u>Asus Launches the Pioneering ROG NUC Desktop PC with High-End Specs Including Core Ultra 9 Processors and RTX 4070 Graphics From $1,629</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/comprehensive-lenovo-thinkpad-x1-carbon-gen-10-assessment-is-it-the-top-choice-for-professionals-insights/"><u>Comprehensive Lenovo ThinkPad X1 Carbon Gen 10 Assessment: Is It the Top Choice for Professionals? Insights</u></a></li>
<li><a href="https://fox-info.techidaily.com/fortified-process-for-adding-tiktok-profile-hyperlinks-for-2024/"><u>Fortified Process for Adding TikTok Profile Hyperlinks for 2024</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/from-typing-to-tech-wizardry-discover-the-raspberry-pi-400s-mini-pc-magic-in-this-comprehensive-review/"><u>From Typing to Tech Wizardry: Discover the Raspberry Pi 400'S Mini PC Magic in This Comprehensive Review</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-add-a-desktop-trash-bin-for-permanently-deleting-files-on-windows-10-and-11/"><u>How to Add a Desktop Trash Bin for Permanently Deleting Files on Windows 10 & 11</u></a></li>
<li><a href="https://buynow-help.techidaily.com/inside-the-specs-and-performance-of-a-modest-contender-dells-inspiron-3671-desktop-critique/"><u>Inside the Specs and Performance of a Modest Contender: Dell's Inspiron 3671 Desktop Critique</u></a></li>
<li><a href="https://windows11.techidaily.com/minimizing-time-outs-and-lag-in-windows-discord-service/"><u>Minimizing Time-Outs and Lag in Windows Discord Service</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-usb30-device-failure-on-windows-oses/"><u>Resolving USB3.0 Device Failure on Windows OSes</u></a></li>
<li><a href="https://windows11.techidaily.com/secure-your-system-top-5-ways-to-reactivate-defender-threat-detection/"><u>Secure Your System: Top 5 Ways to Reactivate Defender Threat Detection</u></a></li>
<li><a href="https://windows11.techidaily.com/setting-new-preferred-pdf-reader-in-windows/"><u>Setting New Preferred PDF Reader in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-the-obstacle-of-file-creation-windows-error-30005/"><u>Tackling the Obstacle of File Creation - Windows Error 30005</u></a></li>
<li><a href="https://common-error.techidaily.com/the-ultimate-guide-to-restoring-charge-on-a-plugged-in-yet-unresponsive-surface-device/"><u>The Ultimate Guide To Restoring Charge On A Plugged In, Yet Unresponsive Surface Device</u></a></li>
<li><a href="https://windows11.techidaily.com/turn-on-windows-11s-direct-image-viewing/"><u>Turn On Windows 11'S Direct Image Viewing</u></a></li>
<li><a href="https://windows11.techidaily.com/understanding-impactful-windows-11-service-disabling/"><u>Understanding Impactful Windows 11 Service Disabling</u></a></li>
<li><a href="https://windows11.techidaily.com/upgrade-security-mastering-windows-11-password-change/"><u>Upgrade Security: Mastering Windows 11 Password Change</u></a></li>
<li><a href="https://techidaily.com/use-device-manager-to-identify-some-outdated-hardware-drivers-in-windows-11107-by-drivereasy-guide/"><u>Use Device Manager to identify some outdated hardware drivers in Windows 11/10/7</u></a></li>
</ul></div>

