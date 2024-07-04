---
title: "Windows 11: Incorporating a God Mode Shortcut"
date: 2024-06-25T11:58:08.924Z
updated: 2024-06-26T11:58:08.924Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Windows 11: Incorporating a God Mode Shortcut"
excerpt: "This Article Describes Windows 11: Incorporating a God Mode Shortcut"
keywords: Win11 GodMode,Windows GodShortcut,ModifyWin11,QuickGodModi,AccessWin11God,CreateWin11Short,ShortcutToGodMode
thumbnail: https://thmb.techidaily.com/a27b3a3de27d6b4c9a23aaf5bc90c6e51b30c3f5343bae186756d50b06815cf1.jpg
---

## Windows 11: Incorporating a God Mode Shortcut

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

1. Right-click **God Mode** and select the **New** \> **Key** context menu options again.
2. Input **command** within the subkey’s text box.  
![The God Mode registry key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/god-mode-key.jpg)
3. Double-click on the **(Default)** string for the new command key you’ve added to the registry.
4. Input **explorer** **shell:::{ED7BA470-8E54-465E-825C-99712043E01C}** within the **Data value** box and click **OK**.  
![The Edit String window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/edit-string-window.jpg)
5. Click on the Registry Editor’s **X** button.

 Check out the new **God Mode** option on your context menu for opening Task View. Right-click somewhere on the desktop background image and select **Show more options**. Then select **God Mod** to bring up the **Task View** window. You can open a multitude of Control Panel applets from there.

![A God Mode context menu option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/god-mode-option.jpg)

 If you ever change your mind about having a **God Mode** context menu option, open the Shell key in Registry Editor again. Then right-click on the **God Mode** key you added and select delete. Click **Yes** to erase the **God Mode** key along with its **command** subkey.

![The Delete option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/the-delete-option.jpg)

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

## Make the Most of God Mode on Windows

 Adding God Mode to your desktop’s context menu will enable you to access a plethora of Control Panel applets and tools within a single window in a couple of clicks. That will save you from rummaging through the Control Panel to find certain applets and settings when needed. Plus, you can make more essential Control Panel applets even more accessible by creating shortcuts for them from the Task View window.

 Many users activate God Mode by setting up desktop shortcuts that open the All Tasks window. However, you can instead add a **God Mode** option to the desktop’s context menu in Windows 11\. Then the All Tasks window will be directly accessible on your right-click menu. This is how you can add God Mode to Windows 11’s context menu.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://windows11.techidaily.com/windows-tips-avoiding-discords-auto-start-and-update-checks/"><u>Windows Tips: Avoiding Discord's Auto-Start & Update Checks</u></a></li>
<li><a href="https://windows11.techidaily.com/nexus-controller-detection-woes-heres-how-to-win-them-back/"><u>Nexus Controller Detection Woes? Here's How to Win Them Back</u></a></li>
<li><a href="https://windows11.techidaily.com/avoiding-windows-11-faux-pas-an-experts-guide-to-safe-practices/"><u>Avoiding Windows 11 Faux Pas: An Expert's Guide to Safe Practices</u></a></li>
<li><a href="https://windows11.techidaily.com/sling-verification-sluggishness-top-strategies-for-speedy-updates/"><u>Sling Verification Sluggishness: Top Strategies for Speedy Updates</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-group-policy-editor-navigation-windows-11-style/"><u>Mastering Group Policy Editor Navigation, Windows 11 Style</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-advice-overcoming-printer-error-0xfffffff/"><u>Expert Advice: Overcoming Printer Error 0xFFFFFFF</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-solution-to-cease-iomap64-syscall-freezes-on-windows/"><u>Step-by-Step Solution to Cease IOMap64 Syscall Freezes on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/fix-self-shutdowns-steps-for-windows-11-users/"><u>Fix Self-Shutdowns: Steps for Windows 11 Users</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/updated-in-2024-questions-about-adding-audio-to-photo-you-should-know/"><u>Updated In 2024, Questions About Adding Audio to Photo You Should Know</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-optimizing-techniques-broadcasting-via-obs-to-facebook-for-2024/"><u>[New] Optimizing Techniques  Broadcasting via OBS to Facebook for 2024</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/updated-in-2024-the-filmmakers-guide-to-a-bolder-bass-enhancing-audio-with-filmora/"><u>Updated In 2024, The Filmmakers Guide to a Bolder Bass Enhancing Audio with Filmora</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-a-perfect-guide-to-remove-or-disable-google-smart-lock-on-xiaomi-redmi-k70-pro-by-drfone-android/"><u>In 2024, A Perfect Guide To Remove or Disable Google Smart Lock On Xiaomi Redmi K70 Pro</u></a></li>
<li><a href="https://vp-tips.techidaily.com/ultimate-speedy-pics-viewing-tool/"><u>Ultimate Speedy Pics Viewing Tool</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/new-2024-approved-top-10-free-android-video-editors-with-no-watermark/"><u>New 2024 Approved Top 10 Free Android Video Editors with No Watermark</u></a></li>
<li><a href="https://extra-information.techidaily.com/brilliant-backdrops-using-light-to-enchant-audiences-for-2024/"><u>Brilliant Backdrops  Using Light to Enchant Audiences for 2024</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/avigating-the-best-dates-and-hours-for-youtube-impact-for-2024/"><u>[New] Navigating the Best Dates and Hours for YouTube Impact for 2024</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/in-2024-boosting-visibility-igtv-and-facebook-connection-techniques/"><u>In 2024, Boosting Visibility  IGTV & Facebook Connection Techniques</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>