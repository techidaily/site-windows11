---
title: Techniques for Turning On/Off the Registry Editor
date: 2024-08-15T15:44:00.246Z
updated: 2024-08-16T15:44:00.246Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Techniques for Turning On/Off the Registry Editor
excerpt: This Article Describes Techniques for Turning On/Off the Registry Editor
keywords: Enable Windows Regedit,Disable Windows Regedit,Start Regedit Trick,Hide System Folders,Regedit Shortcut,Editing Windows Registry,Safeboot Windows
thumbnail: https://thmb.techidaily.com/214585cc6f04e9f51b09b50240658d386b443c6b610883b05f292e6c6a7a4335.jpg
---

## Techniques for Turning On/Off the Registry Editor

 Although the Registry Editor on Windows makes it easy for administrators to access critical settings and configurations, making incorrect changes to registry files can cause the system to become unstable and compromise its security. This is a common concern among Windows users who share their computers with others.

 Fortunately, it’s possible to disable (or enable) Registry Editor access on your Windows 11 PC. Let's see how.

## 1\. How to Disable or Enable Registry Editor Access via the Group Policy Editor

 The most straightforward way to block access to the Registry Editor on Windows is via the Group Policy Editor. However, it’s important to note that this tool is only available on Windows Pro, Education, and Enterprise editions. If you happen to be using Windows Home, refer to our guide on [how to access the Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) before proceeding.

1. Press **Win + R** to open the Run dialog box.
2. Type **gpedit.msc** in the box and press **Enter**.
3. In the Local Group Policy Editor window, use the left pane to navigate to **User Configuration > Administrative Templates > System**.
4. Double-click the **Prevent access to registry editing tools** policy in the right pane.
5. Select the **Enabled** option.
6. Click **Apply** followed by **OK**.  
![Block Registry Editor Access via Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/block-registry-editor-access-via-group-policy-editor.jpg)

 Following this, users will see the “Registry editing has been disabled by your administrator” message when they attempt to access the Registry Editor. If you want to re-enable Registry Editor later, repeat the above steps and set the **Prevent access to registry editing tools** policy to **Not configured** or **Disabled**.

<!-- affiliate ads begin -->
<span id="1993652">
					<video width="720" height="300" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1993652.jpeg"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1993652">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1993652.jpeg" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:720px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1993652%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1993652/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 2\. How to Disable or Enable Registry Editor Access via the Registry Editor

 Another way to restrict the Registry Editor access on Windows involves using the Registry Editor itself. Here are the steps you can follow.

1. Click the **search icon** on the taskbar to access the search menu.
2. Type **regedit** in the box and press **Enter**.
3. Select **Yes** when [the User Account Control (UAC) prompt](https://www.makeuseof.com/windows-11-disable-user-account-control-prompt/) appears.
4. In the Registry Editor window, use the left pane to navigate to **HKEY\_CURRENT\_USER > SOFTWARE > Microsoft > Windows > CurrentVersion > Policies**.
5. Right-click on the **Policies** key and select **New > Key**. Name it **System**.
6. Right-click on the **System** key and select **New > DWORD (32-bit) Value**. Name it **DisableRegistryTools**.
7. Double-click the newly created DWORD, type **1** in the Value data field, and hit **OK**.  
![Block Registry Editor Access via Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/block-registry-editor-access-via-registry-editor.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BGeneral%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/general-970x90.gif" border="0"></a>
<!-- affiliate ads end -->

 Once you complete the above steps, the Registry Editor will be disabled on your PC.

 Although you cannot access the Registry Editor to reverse the above changes, it's still possible to re-enable Registry Editor access. For that, you will have to [create and run a REG file](https://www.makeuseof.com/windows-registry-file-guide/). Here’s how you can go about it.

1. Press **Win + S** to open the search menu.
2. Type **notepad** in the search box and press **Enter**.
3. In the notepad window, paste the following command.  
`Windows Registry Editor Version 5.00  
[HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Policies\System] "DisableRegistryTools"=dword:00000000`  
![Create Reg File to Enable Registry Editor Access on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/create-reg-file-to-enable-registry-editor-access-on-windows.jpg)
<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=4612444&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/pt-728x90.jpg" border="0"></a>
<!-- affiliate ads end -->
4. Click the **File** menu and select **Save as**.
5. Select **Desktop** in the **Save as** dialog box.
6. Enter a suitable name followed by ".reg" and hit **Save**. For instance, you could name the file **ReEnableRegistry.reg** or something similar.
7. Use one of the many [ways to open the Command Prompt with admin rights](https://www.makeuseof.com/windows-run-command-prompt-admin/).
8. Type the following command in the console and hit **Enter**. Make sure you replace the **\[username\]** in the following command with your actual username.  
`cd C:\Users\[username]\Desktop`
9. Paste the following command, replace **FileName** with the actual name of the REG file, and press **Enter**.  
`regedit.exe /s FileName.reg`

 Once you run the above command, the Registry Editor will become accessible again.

<!-- affiliate ads begin -->
<a href="https://ukaidot.sjv.io/c/5597632/1793234/19578" target="_top" id="1793234"><img src="//a.impactradius-go.com/display-ad/19578-1793234" border="0" alt="" width="678" height="452"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793234/19578" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Allowing or Disallowing Registry Editor Access on Windows

 Blocking access to the Registry Editor is an effective way to protect your system from registry mishaps. Nonetheless, if you opt to re-enable access to the Registry Editor on your PC, make sure to exercise caution to avoid messing up the Windows Registry.

 Fortunately, it’s possible to disable (or enable) Registry Editor access on your Windows 11 PC. Let's see how.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-docs.techidaily.com/024-approved-secrets-to-stellar-youtube-livestreaming-top-cameras/"><u>[New] 2024 Approved  Secrets to Stellar YouTube Livestreaming - Top Cameras</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-achieve-financial-insight-the-simple-three-steps-to-assess-youtube-earning-potential-for-2024/"><u>[New] Achieve Financial Insight  The Simple Three Steps To Assess YouTube Earning Potential for 2024</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-in-2024-eyefirefox-capture-extensions/"><u>[New] In 2024, EyeFirefox Capture Extensions</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-in-2024-xbox-extended-storage-5-must-have-hdds/"><u>[New] In 2024, Xbox Extended Storage  5 Must-Have HDDs</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-smoothly-lowering-sound-levels-using-garageband/"><u>[New] Smoothly Lowering Sound Levels Using Garageband</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-transforming-photos-and-videos-from-instagram-to-iphones-for-2024/"><u>[New] Transforming Photos and Videos  From Instagram to iPhones for 2024</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-2024-approved-innovative-integration-mastering-vids-in-the-facebook-realm/"><u>[Updated] 2024 Approved  Innovative Integration  Mastering Vids in the Facebook Realm</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-astonishing-freeness-of-screen-dance-duels-for-2024/"><u>[Updated] Astonishing Freeness of Screen Dance Duels for 2024</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-flavorful-frontier-groundbrenant-title-strategies-for-food-networks/"><u>2024 Approved  Flavorful Frontier  Groundbrenant Title Strategies for Food Networks</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-unlock-the-power-of-time-markings-in-your-youtube-content/"><u>2024 Approved  Unlock the Power of Time Markings in Your YouTube Content</u></a></li>
<li><a href="https://android-location.techidaily.com/9-best-free-android-monitoring-apps-to-monitor-phone-remotely-for-your-tecno-pova-5-pro-drfone-by-drfone-virtual/"><u>9 Best Free Android Monitoring Apps to Monitor Phone Remotely For your Tecno Pova 5 Pro | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/easily-resolve-bluetooth-pairing-failures-on-windows-1011/"><u>Easily Resolve Bluetooth Pairing Failures on Windows 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/easing-out-of-the-eclipse-ending-dark-mode-anomaly/"><u>Easing Out of the Eclipse: Ending Dark Mode Anomaly</u></a></li>
<li><a href="https://windows11.techidaily.com/efficiency-boost-for-winwms-excessive-graphics-use/"><u>Efficiency Boost for WinWM's Excessive Graphics Use</u></a></li>
<li><a href="https://windows11.techidaily.com/efficient-method-to-engagedisengage-bings-taskbar-assist/"><u>Efficient Method to Engage/Disengage Bing's Taskbar Assist</u></a></li>
<li><a href="https://windows11.techidaily.com/efficiently-navigate-your-workflow-essential-command-tips-for-win11/"><u>Efficiently Navigate Your Workflow: Essential Command Tips for Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/effortless-usb-prep-for-upgrading-to-windows-11-3-tried-and-true-methods/"><u>Effortless USB Prep for Upgrading to Windows 11: 3 Tried-and-True Methods</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-windows-productivity-the-best-tech-tools-for-success/"><u>Elevate Windows Productivity: The Best Tech Tools for Success</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-your-visual-experience-increasing-vram-capacity/"><u>Elevate Your Visual Experience: Increasing VRAM Capacity</u></a></li>
<li><a href="https://windows11.techidaily.com/elevating-security-controlling-user-biometrics-in-windows-11/"><u>Elevating Security: Controlling User Biometrics in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-steams-content-server-unreachable-problem-in-windows/"><u>Eliminating Steam's Content Server Unreachable Problem in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-windows-error-0xc00000f-in-minutes/"><u>Eliminating Windows Error 0Xc00000f in Minutes</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-windows-error-0x80072f8f-0x20000/"><u>Eliminating Windows Error: 0X80072f8f-0x20000</u></a></li>
<li><a href="https://windows11.techidaily.com/eluding-eyes-the-art-of-concealing-buttons/"><u>Eluding Eyes: The Art of Concealing Buttons</u></a></li>
<li><a href="https://windows11.techidaily.com/embellishing-windows-tray-adding-number-lock-symbols/"><u>Embellishing Windows Tray: Adding Number Lock Symbols</u></a></li>
<li><a href="https://windows11.techidaily.com/embracing-linguistic-diversity-with-windows-fonts/"><u>Embracing Linguistic Diversity with Windows Fonts</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-graphics-memory-capability-for-hogwarts-virtual-learning-experience/"><u>Enhancing Graphics Memory Capability for Hogwarts Virtual Learning Experience</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-system-analysis-widgets-for-hardware-monitoring/"><u>Enhancing System Analysis: Widgets for Hardware Monitoring</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-user-experience-in-windows-11/"><u>Enhancing User Experience in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-visibility-notifications-for-win11-webcam-use/"><u>Enhancing Visibility: Notifications for Win11 WebCam Use</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-windowed-discords-query-system/"><u>Enhancing Windowed Discord's Query System</u></a></li>
<li><a href="https://windows11.techidaily.com/error-busters-for-windows-top-10-must-haves/"><u>Error Busters for Windows: Top 10 Must-Haves</u></a></li>
<li><a href="https://windows11.techidaily.com/error-e8024002e-fixes-for-updated-windows/"><u>Error E:8024002E Fixes for Updated Windows</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-fix-error-495-while-downloadupdating-android-apps-on-motorola-razr-40-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Fix Error 495 While Download/Updating Android Apps On Motorola Razr 40 | Dr.fone</u></a></li>
<li><a href="https://meme-emoji.techidaily.com/in-2024-best-10-emoji-makers-to-create-your-own-emojispconlineandroidiphone/"><u>In 2024, Best 10 Emoji Makers to Create Your Own EmojisPC/Online/Android/iPhone</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/in-2024-step-by-step-guide-to-add-fun-filters-and-graphics-to-your-snapchat-story/"><u>In 2024, Step-by-Step Guide to Add Fun Filters and Graphics to Your Snapchat Story</u></a></li>
<li><a href="https://buynow-help.techidaily.com/test-your-skies-the-ultimate-guide-to-the-syma-x3d-ultra-hover-copter-value-meets-performance/"><u>Test Your Skies: The Ultimate Guide to the Syma X3D-Ultra Hover Copter - Value Meets Performance</u></a></li>
</ul></div>
