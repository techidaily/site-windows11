---
title: Bestow Magical Menus on Your PC
date: 2025-01-25T03:31:01.741Z
updated: 2025-01-30T05:11:57.632Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Bestow Magical Menus on Your PC
excerpt: This Article Describes Bestow Magical Menus on Your PC
keywords: Enchanted Dining Lists,Spellbound Cuisine Plans,Wizardry Food Choices,Mystic Menu Creation,Arcane Meal Options,Sorcerer's Feast Selections,Potion-Prepared Menus
thumbnail: https://thmb.techidaily.com/a68c5c5018f608284d7af133f2911830741f898253edd18111f294ce2b839027.jpg
---

## Bestow Magical Menus on Your PC

 God Mode enables you to access hundreds of Control Panel applets from a single All Tasks window. That’s a handy thing to activate in Windows 11 for accessing Control Panel settings and creating shortcuts that open them.

 Many users activate God Mode by setting up desktop shortcuts that open the All Tasks window. However, you can instead add a **God Mode** option to the desktop’s context menu in Windows 11\. Then the All Tasks window will be directly accessible on your right-click menu. This is how you can add God Mode to Windows 11’s context menu.

## How to Add God Mode to the Context Menu by Manually Editing the Registry

 You can add God Mode to Windows 11’s desktop context menu by manually tweaking the registry. The tweaking required is relatively simple to apply and involves adding a couple of new registry entries to the Shell key. Follow these steps to manually add God Mode to Windows 11’s context menu:

1. Open the Registry Editor (see [how to open the Registry Editor](https://www.makeuseof.com/windows-11-open-registry-editor/) for instructions).
2. Click in the address bar at the top of Registry Editor to delete the current key location.
3. Input this Shell key path in the address bar and hit **Enter**:  
`Computer\HKEY_CLASSES_ROOT\DesktopBackground\Shell\`
4. Right-click on **Shell** in Registry Editor’s navigation sidebar to select **New** and **Key**.  
![The New > Key options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/new-key-options.jpg)
5. Type **God Mode** in the key’s text box.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/9hsPbiic0O8?si=58mZ2Cu6wicQfsUP" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

1. Right-click **God Mode** and select the **New** \> **Key** context menu options again.
2. Input **command** within the subkey’s text box.  
![The God Mode registry key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/god-mode-key.jpg)
3. Double-click on the **(Default)** string for the new command key you’ve added to the registry.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/vQbNyknjJJ8?si=RGVIEWLdPbvRC_r6" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

4. Input **explorer** **shell:::{ED7BA470-8E54-465E-825C-99712043E01C}** within the **Data value** box and click **OK**.  
![The Edit String window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/edit-string-window.jpg)
5. Click on the Registry Editor’s **X** button.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/sn2STvYRVb8?si=Z-XhJJ1Mc-Em5Kqy" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Check out the new **God Mode** option on your context menu for opening Task View. Right-click somewhere on the desktop background image and select **Show more options**. Then select **God Mod** to bring up the **Task View** window. You can open a multitude of Control Panel applets from there.

![A God Mode context menu option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/god-mode-option.jpg)

 If you ever change your mind about having a **God Mode** context menu option, open the Shell key in Registry Editor again. Then right-click on the **God Mode** key you added and select delete. Click **Yes** to erase the **God Mode** key along with its **command** subkey.

![The Delete option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/the-delete-option.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/SDUPd69Qfls?si=uIGZG-riskwmVZYg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Add God Mode to the Context Menu With Right-Click Extender

 The manual registry tweak method is straightforward, but you can add God Mode to the context menu with third-party software instead if preferred. Right-Click Extender is customization software that includes an option for adding God Mode to the context menu. This is how you can add God Mode to your context menu with Right-Click Extender:

1. Open this [Right-Click Extender](https://www.softpedia.com/get/Tweak/System-Tweak/Right-Click-Extender.shtml) download page.
2. Click on the **Download** and **Secure Download (US)** options and download the file.
3. Extract the Right-Click Extender archive by following the instructions within this guide to [unzipping ZIP files in Windows](https://www.makeuseof.com/unzip-files-windows-10/).  
![The Extract Compressed (Zipped) Folders window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/extract-compressed-zip-folder.jpg)
4. Open the extracted Right-Click Extender directory and its Right-Click Extender v2 subfolder.
5. Double-click the Right-Click Extender v2 application file.
6. Click on the **Desktop** tab in Right-Click Extender.
7. Select the **All Tasks (GodMode)** setting and its Icon checkbox.  
![The Right-Click Extender v2 window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/the-all-tasks-setting.jpg)
8. Press the green **Apply** button.

 Now you’ll see a new **God Mode** option on Windows 11’s classic context menu. This option will also have an icon by it. Click on **God Mode** to view the list of Control Panel applets.

## How to Create Control Panel Shortcuts From God Mode's All Tasks Window

 The Task View window the God Mode context menu option opens makes hundreds of Control Panel applets more accessible. You can open whatever Control Panel settings you need from that window. However, the list of applets shown in that window is quite long.

 Task View makes it easy to create desktop shortcuts for opening the Control Panel applets you need to access more regularly. To do so, left-click an applet or utility in the Task View window, drag it onto the desktop, and release the mouse button. Then you can click on the desktop shortcut to open its Control Panel applet whenever needed.

![The All Tasks (God Mode) window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/the-all-tasks-window.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/465CTOm8om0?si=63RxowNMCFA4fPUa" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Make the Most of God Mode on Windows

 Adding God Mode to your desktop’s context menu will enable you to access a plethora of Control Panel applets and tools within a single window in a couple of clicks. That will save you from rummaging through the Control Panel to find certain applets and settings when needed. Plus, you can make more essential Control Panel applets even more accessible by creating shortcuts for them from the Task View window.

 Many users activate God Mode by setting up desktop shortcuts that open the All Tasks window. However, you can instead add a **God Mode** option to the desktop’s context menu in Windows 11\. Then the All Tasks window will be directly accessible on your right-click menu. This is how you can add God Mode to Windows 11’s context menu.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-direct.techidaily.com/updated-2024-approved-crafting-immersive-vr-experiences-with-adobe-premieres-360-editing-features/"><u>[Updated] 2024 Approved Crafting Immersive VR Experiences with Adobe Premiere's 360° Editing Features</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-explore-the-world-of-video-calls-hangouts-for-android/"><u>[Updated] Explore the World of Video Calls Hangouts for Android</u></a></li>
<li><a href="https://vp-tips.techidaily.com/easy-and-safe-methods-for-transferring-pictures-from-computer-to-ios-device-with-windows-1110/"><u>Easy and Safe Methods for Transferring Pictures From Computer to iOS Device with Windows 11/10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/fix-your-screen-mirroring-problems-when-miracast-is-unavailable-via-graphics-card/"><u>Fix Your Screen Mirroring Problems When Miracast Is Unavailable via Graphics Card</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-through-the-signature-verification-failure-of-windows-1011/"><u>Guide Through the Signature Verification Failure of Windows 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/hide-your-wireless-signal-windows-techniques/"><u>Hide Your Wireless Signal: Windows Techniques</u></a></li>
<li><a href="https://win-solutions.techidaily.com/how-to-stop-your-civilization-vi-install-from-freezing-up-proven-fixes-inside/"><u>How To Stop Your Civilization VI Install From Freezing Up - Proven Fixes Inside!</u></a></li>
<li><a href="https://screen-recording.techidaily.com/in-2024-az-capture-in-depth-app-analysis-and-reviews/"><u>In 2024, AZ Capture In-Depth App Analysis & Reviews</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-realme-12-5g-mirror-screen-to-pc-drfone-by-drfone-android/"><u>In 2024, How Realme 12 5G Mirror Screen to PC? | Dr.fone</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/in-2024-live-streaming-and-video-editing-with-vlc/"><u>In 2024, Live Streaming & Video Editing with VLC</u></a></li>
<li><a href="https://fake-location.techidaily.com/ispoofer-is-not-working-on-oneplus-open-fixed-drfone-by-drfone-virtual-android/"><u>iSpoofer is not working On OnePlus Open? Fixed | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/preventing-psycho-stress-keeping-your-ps4-controller-tethered-to-windows/"><u>Preventing Psycho-Stress: Keeping Your PS4 Controller Tethered to Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/secure-your-system-save-big-keys-fans-black-friday-treat-for-windows-11/"><u>Secure Your System, Save Big - Keys Fan's Black Friday Treat for Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-for-cooling-computers-running-hot-w11/"><u>Steps for Cooling Computers Running Hot W11</u></a></li>
<li><a href="https://windows11.techidaily.com/tips-for-a-shimmering-window-title-bar-in-win11/"><u>Tips for A Shimmering Window Title Bar in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-a-non-operational-media-player-in-windows-11/"><u>Troubleshooting a Non-Operational Media Player in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-disappearing-windows-screen/"><u>Troubleshooting Disappearing Windows Screen</u></a></li>
</ul></div>

