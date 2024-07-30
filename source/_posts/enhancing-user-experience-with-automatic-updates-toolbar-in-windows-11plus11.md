---
title: Enhancing User Experience with Automatic Updates Toolbar in Windows 11+11
date: 2024-07-29T04:27:58.915Z
updated: 2024-07-30T04:27:58.915Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Enhancing User Experience with Automatic Updates Toolbar in Windows 11+11
excerpt: This Article Describes Enhancing User Experience with Automatic Updates Toolbar in Windows 11+11
keywords: WinXtend UX Update Toolbar,Windows 11+ Auto-Update Bar,Efficient User Toolbar,Intuitive UI Updates,Seamless System Tweaks,Enhanced PC Interface,Smart OS Upgrade Tool
thumbnail: https://thmb.techidaily.com/7fc466e5e2b7732daf41c9b5f420c5c5add88815dae1954866b21ab967027c21.jpg
---

## Enhancing User Experience with Automatic Updates Toolbar in Windows 11+11

 Microsoft regularly releases patch updates for both Windows 10 and 11 every month. These patch updates typically address security vulnerabilities and fix Windows bugs and issues. Although those updates are usually automatically installed, sometimes your PC will miss the memo. And sometimes, the update itself is an optional download.

 To ensure your Windows 11/10 PC has all the patch updates available for it, it’s a good idea to check for new ones via Settings. The **Windows Update** tab includes a **Check for updates** button. You can add a shortcut for that tab to the desktop’s context menu with the method below.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37100474&QTY=1&AFFILIATE=108875&CART=1"><img src="https://awario.com/images/pages/index/img-platform-ui-1280@1x.avif" border="0"></a>
<!-- affiliate ads end -->
## Add a Check for Updates Shortcut to the Context Menu

 Windows 11 doesn’t include any built-in options for adding shortcuts to the desktop’s right-click context menu. However, you can still add a **Check for Updates** shortcut for the **Windows Update** tab to that menu by [manually editing the registry](https://www.makeuseof.com/tag/what-is-the-windows-registry-editor-and-how-do-i-use-it-makeuseof-explains/). Once done, you can open the **Windows Update** tab directly from the desktop’s context menu.

 To add that context menu shortcut, edit the registry as follows:

1. Right-click the **Start** button and select the **Run** shortcut to launch that accessory.
2. [Open the Registry Editor](https://www.makeuseof.com/windows-11-open-registry-editor/) by typing **regedit** in the **Open** box and clicking **OK**.
3. Then navigate to the **Computer** \> **HKEY\_CLASSES\_ROOT** \> **DesktopBackground** \> **Shell** registry key.
4. Right-click the **Shell** key to select the **New** submenu option.
5. Select the **Key** option.  
![The Key option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/11/key-option.png)

1. Type **Check for Updates** to be the new key’s name.
2. Right-click the **Check for Updates** key and select **New** on the context menu.
3. Click the **Key** option again.
4. Now input **command** for the new key’s name.
5. Select the **Check for Updates** key, and then right-click a space on the right side of the Registry Editor to select **New > String Value**.  
![The String Value option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/11/string-value-option.png)

1. Type **SettingsURI** to be the new string’s name.
2. Double-click **SettingsURI** to open an Edit String window.
3. Type **ms-settings:windowsupdate-action** within the Value data box, and click **OK**.  
![The Edit String window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/11/edit-string-window.png)
4. Right-click the **command** key and select the **New** \> **String Value** options.
5. Enter the string title **DelegateExecute**, and press the **Return** key.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4699091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/bccefcc1b1eee9eca3ae4f5c1a281482/products/1_jutoh-logo-1200x1600.jpg" border="0">Jutoh Plus -  Jutoh is an ebook creator for Epub, Kindle and more. It's fast, runs on Windows, Mac, and Linux, comes with a cover design editor, and allows book variations to be created with alternate text, style sheets and cover designs. Jutoh Plus adds scripting so you can automate ebook import and creation operations. It also allows customisation of ebook HTML via templates and source code documents; and you can create Windows CHM and wxWidgets HTB help files. </a>
<!-- affiliate ads end -->
![The DelegateExecute string for the command key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/11/delegateexecute_string.png)
6. Double-click the **DelegateExecute** string to bring up its Value data box.
7. Type **{556FF0D6-A1EE-49E5-9FA4-90AE116AD744}** in the Value data text box, and press the **OK** button.
8. Close the Registry Editor’s window.

 Now right-click an area of your Windows 11 desktop and select **Show more options** to bring up the classic context menu. If you’ve edited the registry correctly, that menu will include a **Check for Updates** option. Select that option to open Settings’ **Windows Update** tab. Then you can click the **Check for updates** button on that tab.

![The Check for Updates context menu option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/11/check-for-updates-context-menu-option.png)

 Alternatively, press the **Shift** + **F10** hotkey to bring up the classic context menu without right-clicking the desktop. That keyboard shortcut opens the classic context menu at the top left of the desktop. Then you can select **Check for Updates** from there to bring up the tab shown below.

<!-- affiliate ads begin -->
<a href="https://parisrhonecom.sjv.io/c/5597632/1922358/21553" target="_top" id="1922358"><img src="//a.impactradius-go.com/display-ad/21553-1922358" border="0" alt="" width="1080" height="1080"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1922358/21553" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![The Windows Update tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/11/check_for_updates_button.png)

 This registry trick works much the same on Windows 10\. The only difference is that you won’t need to select **Show more options**. As Windows 10’s desktop context menu is the classic one, it doesn’t include **Show more options**. You can select **Check for Updates** on its primary context menu.

 If you ever want to remove the **Check for Updates** shortcut from the context menu, open the **Shell** key in the Registry Editor again. Then right-click the **Check for Updates** key to select **Delete**.

## Add a Windows Update Submenu to the Context Menu With Winaero Tweaker

 Winaero Tweaker is a freely available customization software for Windows with which you can customize the context menu in many ways. That software has an option you can select to add a **Windows Update** submenu to the context menu, which includes a **Check for updates** shortcut. This is how you can add a **Check for updates** shortcut to the desktop’s right-click menu with Winaero Tweaker:

1. Go to this [Winaero Tweaker webpage](https://winaero.com/download-winaero-tweaker/) in your browsing software.
2. Next, click the **Click here to download file** link.
3. Install and run the Winaero Tweaker software with the downloaded setup file. This [Winaero Tweaker customization guide](https://www.makeuseof.com/windows-11-winaero-tweaker-guide/) includes full installation instructions for that software.
4. Double-click the **Context menu** category within Winaero Tweaker’s left sidebar.
5. Click on the **Windows Update** setting.  
<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296685&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2022/video-pp/ScreenshotSlider/Nero-Video-Advanced-editing.JPG" border="0">Simple and intuitive video editing
🎬 Nero Video:
The powerful video editing program for your Windows PC</a>
<!-- affiliate ads end -->
![The Add Windows Update submenu to Desktop context menu option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/the-add-windows-update-to-context-menu-option.jpg)
6. Select the **Add Windows Update submenu to Desktop context menu** option.

 Now look at the new Windows Update submenu on the desktop’s context menu. Press **Shift** \+ **F10** to view the classic context menu. Move the cursor over the **Windows Update** submenu to view its options. There you can select a **Check for updates** option to bring up the **Check for updates** button.

![The Windows Update submenu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/the-windows-update-submenu.jpg)

 The **Windows Update** submenu also has four other shortcuts to update settings. Click **Update history** to view the installed update list. Or select **Advanced options** to bring up the additional settings for updates. The **Restart options** shortcut opens the settings for scheduling update times.

 Winaero Tweaker also has a customization option for adding a **Windows Update** shortcut to the Control panel. To access that option, click **Settings and** **Control Panel** \> **Add Windows Update** in Winaero Tweaker’s sidebar. Click the **Add Windows Update to Control Panel\\System and Security** checkbox to select that option.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087484/7443" target="_top" id="2087484"><img src="//a.impactradius-go.com/display-ad/7443-2087484" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087484/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![The Add Windows Update to Control Panel option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/the-add-windows-update-to-control-panel-option.jpg)

 Then you’ll see a **Windows Update** shortcut within the Control Panel. [Open the Control Panel](https://www.makeuseof.com/windows-11-open-control-panel/) and click the **System and Security** category. Clicking the **Windows Update** shortcut there will open the **Settings** tab with the **Check for updates** button.

<!-- affiliate ads begin -->
<a href="https://otszone.ots7.com/order/checkout.php?PRODS=4713322&QTY=1&AFFILIATE=108875&CART=1"><img src="https://green.ots7.com/screenshots/OtsAV/OtsAVRadio1.90-300x188.jpg" border="0">OtsAV Radio Webcaster</a>
<!-- affiliate ads end -->
![The Windows Update Control Panel shortcut](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/windows-update-in-control-panel.jpg)

## Keep an Eye Out For New Windows Updates

 So, now you can select a handy **Check for Updates** shortcut on your desktop’s context menu. That shortcut will save you from having to manually open Settings and its **Windows Update** tab whenever you need to check for updates. Instead, you can simply click the **Check for Updates** context menu option to open the update tab directly from the desktop.

 Select that shortcut to keep an eye out for new updates regularly. When optional updates are available, you’ll see them listed on the tab with **Download and install** options. Clicking **Check for updates** will automatically download and install available updates.

 To ensure your Windows 11/10 PC has all the patch updates available for it, it’s a good idea to check for new ones via Settings. The **Windows Update** tab includes a **Check for updates** button. You can add a shortcut for that tab to the desktop’s context menu with the method below.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://instagram-clips.techidaily.com/2024-approved-how-to-use-filters-on-instagram-2023/"><u>2024 Approved  How to Use Filters on Instagram 2023?</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/2024-approved-secret-glance-at-fb-snapshots/"><u>2024 Approved  Secret Glance at FB Snapshots</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/2024-approved-your-digital-journey-to-youtube-and-facebook-video-gems/"><u>2024 Approved  Your Digital Journey to YouTube and Facebook Video Gems</u></a></li>
<li><a href="https://windows11.techidaily.com/7-ways-to-fix-a-profile-error-occured-in-google-chrome-for-windows/"><u>7 Ways to Fix A Profile Error Occured in Google Chrome for Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/brain-benefits-and-heartbeats-the-joint-impact-of-mindfulness/"><u>Brain Benefits and Heartbeats: The Joint Impact of Mindfulness</u></a></li>
<li><a href="https://windows11.techidaily.com/clearing-up-exit-point-not-found-errors/"><u>Clearing Up Exit Point Not Found Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/configuring-fingerprint-login-for-windows-11-users/"><u>Configuring Fingerprint Login for Windows 11 Users</u></a></li>
<li><a href="https://windows11.techidaily.com/conquering-the-challenge-0x80072af9-errors/"><u>Conquering the Challenge: 0X80072AF9 Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/eradicating-error-code-xc0f1103f-with-nvidias-geforce-now/"><u>Eradicating Error Code Xc0f1103f with NVIDIA's GeForce Now</u></a></li>
<li><a href="https://windows11.techidaily.com/exploring-advanced-windows-startup-techniques/"><u>Exploring Advanced Windows Startup Techniques</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-fix-life360-shows-wrong-location-on-oneplus-nord-ce-3-5g-drfone-by-drfone-virtual-android/"><u>How to Fix Life360 Shows Wrong Location On OnePlus Nord CE 3 5G? | Dr.fone</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-8-safe-and-effective-methods-to-unlock-your-iphone-14-pro-without-a-passcode-drfone-by-drfone-ios/"><u>In 2024, 8 Safe and Effective Methods to Unlock Your iPhone 14 Pro Without a Passcode | Dr.fone</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/in-2024-best-in-class-facebook-media-firefox-edition/"><u>In 2024, Best-in-Class Facebook Media  FireFox Edition</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-detailed-guide-of-ispoofer-for-pogo-installation-on-nubia-red-magic-8s-proplus-drfone-by-drfone-virtual-android/"><u>In 2024, Detailed guide of ispoofer for pogo installation On Nubia Red Magic 8S Pro+ | Dr.fone</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-detailed-review-of-doctorsim-unlock-service-for-iphone-6s-by-drfone-ios/"><u>In 2024, Detailed Review of doctorSIM Unlock Service For iPhone 6s</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-data-from-vivo-x100-pro-to-other-android-devices-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Data from Vivo X100 Pro to Other Android Devices? | Dr.fone</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/in-2024-the-ultimate-playbook-for-facebook-videos-to-attract-more-viewers/"><u>In 2024, The Ultimate Playbook for Facebook Videos to Attract More Viewers</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-file-and-folder-integration-in-windows-1011/"><u>Mastering File & Folder Integration in Windows 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/matchmaking-the-ideal-nvidia-driver-with-entertainment-goals/"><u>Matchmaking The Ideal Nvidia Driver With Entertainment Goals</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/professional-tips-to-diminish-ambient-sound-in-videos-for-2024/"><u>Professional Tips to Diminish Ambient Sound in Videos for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/rectifying-complication-windows-11-plus-nvidia-x0001/"><u>Rectifying Complication: Windows 11 + Nvidia X0001</u></a></li>
<li><a href="https://windows11.techidaily.com/reinventing-tech-windows-leap-from-version-11/"><u>Reinventing Tech: Windows' Leap From Version 11</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-xbox-mic-issues-on-windows-1111-pro/"><u>Resolving Xbox Mic Issues on Windows 11/11 Pro</u></a></li>
<li><a href="https://windows11.techidaily.com/setting-up-a-unique-win11-screenscape-display/"><u>Setting Up a Unique Win11 Screenscape Display</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-windows-11-in-place-update-mastery/"><u>Step-by-Step Windows 11, In-Place Update Mastery</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlining-access-permissions-biometrics-on-w11-domains/"><u>Streamlining Access Permissions: Biometrics on W11, Domains</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-error-0x80072f8f-0x20000-in-windows/"><u>Troubleshooting Error 0X80072f8f - 0X20000 in Windows</u></a></li>
<li><a href="https://extra-hints.techidaily.com/ultimate-iphone-vr-game-list-for-your-next-adventure/"><u>Ultimate iPhone VR Game List for Your Next Adventure</u></a></li>
<li><a href="https://windows11.techidaily.com/unsticking-wows-initialization-on-pcs/"><u>Unsticking WoW's Initialization on PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-the-secrets-to-successful-os-transition-in-virtual-worlds/"><u>Unveiling the Secrets to Successful OS Transition in Virtual Worlds</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11s-search-tweaks-enhancing-your-experience/"><u>Windows 11'S Search Tweaks: Enhancing Your Experience</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>