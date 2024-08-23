---
title: "Reimagining Windows UI: Adding Menus and Subitems"
date: 2024-08-22T21:37:43.977Z
updated: 2024-08-23T21:37:43.977Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Reimagining Windows UI: Adding Menus and Subitems"
excerpt: "This Article Describes Reimagining Windows UI: Adding Menus and Subitems"
keywords: WinUI Enhancement Guide,Menu Revamp in Windows,Submenu Integration Tech,User Interface Redesign,UI Improvement Strategies,Modernizing Windows UI,Adding Menus to UIs
thumbnail: https://thmb.techidaily.com/c64fedaf756cbcf9ac92722c1b2668052e1efc526bd85097cc0c097ddacbbc3a.jpg
---

## Reimagining Windows UI: Adding Menus and Subitems

 Windows 11’s desktop context menu is a place where you can add many software shortcuts even though the platform doesn’t include built-in customization settings for that menu. Many users add shortcuts to that menu with third-party software, but you can manually customize it with Registry Editor.

 If you add many shortcuts to that menu, organizing them into submenus is a good idea. Doing so will enable you to add more shortcuts without greatly extending the length of the classic context menu. This is how you can add new submenus to the Windows 11’s desktop context menu.

## How to Add a Submenu to the Context Menu by Manually Editing the Registry

 You can manually create a context menu submenu that includes any number of software shortcuts with the Registry Editor. For the sake of example, here we’ll create a submenu that includes shortcuts for opening the Notepad and Remote Desktop Connection apps. Then you can add more shortcuts for software on your PC. First, you’ll need to lay the foundation for the submenu as follows:

1. To access the registry app, check out this guide about [how to open Registry Editor](https://www.makeuseof.com/windows-11-open-registry-editor/).
2. Go to a **shell** key by inputting the following location into the Registry Editor’s address bar:  
`Computer\HKEY_CLASSES_ROOT\Directory\Background\shell`
3. Right-click the **shell** key in the left sidebar and select the **New** \> **Key** options for adding a new registry entry.  
![The New > Key options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/new-key-options.jpg)
4. Enter **Menu1** to be the new key’s name.
5. Right-click **Menu1** to select the **New** \> **String Value** options.

1. Input **MUIVerb** for the new string’s name.
2. Repeat step five to add another new string to the **Menu1** key. However, enter **SubCommands** to be this new string’s name.  
![The Menu1 registry key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/the-menu1-key.jpg)
3. Double-click the **MUIVerb** string added to the **Menu1** key.
4. Enter **Apps** in the **Value** box for the **MUIVerb** string, which will be the heading for your new context menu submenu. Or you can input a different submenu heading in the **Value data** box if preferred.  
![The MUIVerb string value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/muiverb-string.jpg)
5. Click **OK** to exit the Edit String window for **MUIVerb**.
6. Next, double-click on the **SubCommand** string inside the **Menu1** key.
7. Input **Notepad; Remote Desktop Connection** inside the **Value** box for the **SubCommands** string and click **OK**.  
![subcommands-string-value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/subcommands-string-value.jpg)

 Now a new **App** submenu will be visible on Windows 11’s classic context menu. However, it won’t include any shortcuts. So, you will need to do some further editing of a different **shell** key to add functionality to the submenu. Edit the registry like this to complete the submenu:

1. Return to the Registry Editor and input this location into its address bar:  
`HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\CommandStore\Shell`
2. Right-click **shell** to select **Key** on the **New** submenu.
3. Input **Notepad** to be the title for this new registry key.
4. Right-click on **Notepad** in Registry Editor’s left sidebar to select **New** \> **Key**.
5. Enter **command** to be the name of the subkey.
6. Double-click **(Default)** in the **Notepad** key.
7. Input **Notepad** into the **Value** box and click **OK**.
8. Double-click the **(Default)** string in the **command** subkey.
9. Enter this Notepad location into the **Value** box and select **OK**:  
`C:\Windows\System32\notepad.exe`  
![The Notepad path value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/the-notepad-path-value.jpg)
10. Repeat steps two to five to create a **Remote Desktop Connection** key with a **command** subkey, as shown in the snapshot directly below. Instead of naming the key Notepad, input **Remote Desktop Connection** for the new key’s title.  
![The Remote Desktop Connection and Notepad keys](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/notepad-and-remote-desktop-connection-keys.jpg)
11. Double-click the **(Default)** string for the **Remote Desktop Connection** key you created.
12. Input **Remote Desktop Connection** into the **Value** box and select **OK**.
13. Select the **command** subkey for the **Remote Desktop Connection** key and double-click its **(Default)** string.
14. Enter the following Remote Desktop Connection app path in the **Value** box and click **OK**:  
`"C:\Windows\System32\mstsc"`

 Now the new context menu submenu is complete. Right-click within an area of the Windows 11 desktop and select **Show more options** to view the secondary classic context menu. Move the cursor over the new **Apps** submenu from which you can select to open Notepad and Remote Desktop Connection.

![The Apps submenu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/the-apps-submenu.jpg)

 You can add more software shortcuts to that submenu. Note that the values you input for the **SubCommands** string must match the names of the registry keys created for the software shortcuts. In the example above, the **Notepad** and **Remote Desktop Connection** registry keys matched values input for the **SubCommands** string.

 You must also input the exact and full paths for whatever software you want the shortcuts to open within the **(Default)** strings of the command subkeys. In the example above, the **(Default)** strings of the **command** subkeys within the **Remote Desktop Connection** and **Notepad** keys include the paths for opening those apps.

 If you ever want to remove the submenu from the context menu, delete the key that created it. To do so, return to the registry location that includes the **Menu1** key. Right-click the **Menu1** key to select **Delete** and **Yes** for confirmation.

![The Delete option for the Menu1 key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/delete-option.jpg)

## How to Add a Submenu to the Context Menu With Easy Context Menu

 Easy Context Menu is a freely available context menu customization desktop app. That software enables you to add custom software shortcut submenus to the right-click menu without [manually editing the registry](https://www.makeuseof.com/tag/what-is-the-windows-registry-editor-and-how-do-i-use-it-makeuseof-explains/).

 You can create a custom software shortcuts submenu with Easy Context Menu like this:

1. Navigate to the [Easy Context Menu](https://www.sordum.org/downloads/?easy-context-menu) download page.
2. Click **Direct Download** on that page to save the ZIP archive for Easy Context Menu.
3. Extract the **ec\_menu** ZIP with a method in this [guide for unzipping ZIP archives](https://www.makeuseof.com/how-to-extract-zip-files-windows-11/) within Windows.  
![The Extract All option for ZIP archives](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/extract-all-option.jpg)
4. Open the extracted folder for Easy Context Menu and double-click the EXE file that runs the software from there.
5. Click the **List Editor** button in Easy Context Menu.

1. Select **Desktop Context Menu** and press the **Add Sub Menu** button.
2. Input **Software Shortcuts** in the **Title** box for the new submenu.  
![The List Editor window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/software-shortcuts-submenu.jpg)
3. Click the **Add New** button with the **Software Shortcuts** submenu selected.
4. Select a program you want to include in the submenu and click **Open**.
5. Repeat the previous two steps to add more programs to the submenu.  
![A program shortcut added to the Software Shortcuts submenu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/program-shortcuts.jpg)
6. Select the checkboxes for the new **Software Shortcuts** submenu and the programs added to it in the List Editor window.
7. Press the **Save Changes** button and close the List Editor window.
8. Select the checkboxes for the **Software Shortcuts** submenu and the program options it includes within the Easy Context Menu window.  
![The Easy Context Menu window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/easy-context-menu-window.jpg)
9. Click **Apply Changes** to add the new submenu.

 Now check out the new **Software Shortcuts** submenu on Windows 11’s classic desktop context menu. That cascading menu will include all the programs you selected to add to it. It will also include program icons, so long as you leave the **Show icon in the Context Menu** checkboxes selected.

![software-shortcuts-submenu2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/software-shortcuts-submenu2.jpg)

 Another advantage of utilizing Easy Context Menu is that it includes options for positing the submenu. You can configure the approximate position of that submenu by selecting one of the three **Show at** options for it within the List Editor window. You can also reposition the submenu or items in it by selecting them and clicking the **Move Up** or **Move Down** buttons.

 Easy Context Menu also includes **Tools**, **System Tools**, and **Turn Off Options** submenus for you to add to the right-click menu. To add those submenus, select the **System Tools**, **Turn Off Options**, and **Tools** checkboxes for the desktop context menu and click **Apply Changes**. You can also deselect some of the checkboxes for those submenus to remove certain shortcuts from them.

![A Tools submenu added with Easy Context Menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/the-tools-submenu.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4726807&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/c14a8df1e1b4d5297e9cb30cb34d5a00/products/copy_copy_power-tools-48.png" border="0">Power Tools add-on for Google Sheets, Lifetime subscription</a>
<!-- affiliate ads end -->
## Organize Your Windows Desktop Context Menu Shortcuts With Submenus

 Adding one or more submenus to Windows 11’s desktop context menu will enable you to organize the software shortcuts added to it.

 You could create multiple submenus on the context menu that include shortcuts for opening different software categories, such as web browsers, media players, productivity apps, etc. Or you can add a new desktop context menu submenu for accessing Windows tools and turn off options with Easy Context Menu.

 If you add many shortcuts to that menu, organizing them into submenus is a good idea. Doing so will enable you to add more shortcuts without greatly extending the length of the classic context menu. This is how you can add new submenus to the Windows 11’s desktop context menu.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-info.techidaily.com/new-chordography-map-your-creative-path-with-iphone/"><u>[New] Chordography  Map Your Creative Path with iPhone</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-in-2024-facebook-live-mastery-making-the-most-of-real-time-sharing/"><u>[New] In 2024, Facebook Live Mastery  Making the Most of Real-Time Sharing</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-joke-jigsaw-puzzles-build-with-kapwingenasian-memes/"><u>[New] Joke Jigsaw Puzzles  Build with Kapwing’enasian Memes</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-exploring-the-hottest-stock-photos-and-their-journeys/"><u>[Updated] Exploring the Hottest Stock Photos & Their Journeys</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/2024-approved-journey-through-time-a-comprehensive-guide-on-scanning-and-storing-old-prints/"><u>2024 Approved  Journey Through Time  A Comprehensive Guide on Scanning and Storing Old Prints</u></a></li>
<li><a href="https://screen-recording.techidaily.com/2024-approved-zooming-into-perfection-a-compreenasional-tutorial-on-audio-recording/"><u>2024 Approved  Zooming Into Perfection  A Compreenasional Tutorial on Audio Recording</u></a></li>
<li><a href="https://extra-resources.techidaily.com/a-simple-guide-changing-your-voice-in-online-battles-pubg-for-2024/"><u>A Simple Guide  Changing Your Voice in Online Battles (PUBG) for 2024</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/digital-documentation-at-its-best-with-ezvide-software/"><u>Digital Documentation at Its Best with EZvide Software</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-device-freeze-addressing-error-0x887a0006-windows/"><u>Fixing Device Freeze: Addressing Error 0X887A0006 Windows</u></a></li>
<li><a href="https://tech-haven.techidaily.com/from-inception-to-revolution-an-insightful-comparison-of-openais-gpt-models-gpt-1-gpt-2-gpt-3-and-gpt-4/"><u>From Inception to Revolution: An Insightful Comparison of OpenAI’s GPT Models (GPT-1, GPT-2, GPT-3 & GPT-4)</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/from-novice-to-pro-an-extensive-guide-to-capturing-top-notch-audio-on-zoom/"><u>From Novice to Pro  An Extensive Guide to Capturing Top-Notch Audio on Zoom</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-overcoming-wrong-character-display/"><u>Guide to Overcoming Wrong Character Display</u></a></li>
<li><a href="https://windows11.techidaily.com/hiding-login-details-deactivating-security-questions-on-windows-11/"><u>Hiding Login Details: Deactivating Security Questions on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-error-code-e84-on-steam-for-windows/"><u>How to Fix the Error Code E84 on Steam for Windows</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-restore-a-bricked-realme-11-5g-back-to-operation-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Restore a Bricked Realme 11 5G Back to Operation | Dr.fone</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-how-can-we-bypass-samsung-galaxy-s23-fe-frp-by-drfone-android/"><u>In 2024, How Can We Bypass Samsung Galaxy S23 FE FRP?</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-how-to-unlock-atandt-apple-iphone-15-pro-with-3-methods-by-drfone-ios/"><u>In 2024, How to Unlock AT&T Apple iPhone 15 Pro with 3 Methods</u></a></li>
<li><a href="https://windows11.techidaily.com/innovative-synergy-windows-enables-iphone-and-ipad-with-desktop-power/"><u>Innovative Synergy: Windows Enables iPhone & iPad with Desktop Power</u></a></li>
<li><a href="https://windows11.techidaily.com/instant-wallpaper-update-the-simple-windows-method/"><u>Instant Wallpaper Update: The Simple Windows Method</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-windows-11s-fast-flip-buttons/"><u>Mastering Windows 11'S Fast Flip Buttons</u></a></li>
<li><a href="https://windows11.techidaily.com/mastery-in-moving-between-focused-and-unfocused-states-within-windows-terminal/"><u>Mastery in Moving Between Focused and Unfocused States Within Windows Terminal</u></a></li>
<li><a href="https://windows11.techidaily.com/mastery-of-access-control-regedit-in-win11/"><u>Mastery of Access Control: RegEdit in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/mastery-over-muted-powershell-scripts-four-tactics-to-counter-error-message/"><u>Mastery Over Muted PowerShell Scripts: Four Tactics to Counter Error Message</u></a></li>
<li><a href="https://tech-revival.techidaily.com/myai-meets-chatgpt-which-social-platform-to-choose/"><u>MyAI Meets ChatGPT: Which Social Platform to Choose?</u></a></li>
<li><a href="https://windows11.techidaily.com/navigate-tasks-like-a-pro-admin-mode-for-task-manager-on-windows-11/"><u>Navigate Tasks Like a Pro: Admin Mode for Task Manager on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/navigate-through-time-windows-11-file-history-essentials/"><u>Navigate Through Time: Windows 11 File History Essentials</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-and-fixing-windows-registry-failsafe/"><u>Navigating and Fixing Windows Registry Failsafe</u></a></li>
<li><a href="https://fox-helps.techidaily.com/new-era-for-mobile-photography-iphone-x-explored/"><u>New Era for Mobile Photography  IPhone X Explored</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/professional-top-10-hd-webcams-and-buyers-advice/"><u>Professional Top 10 HD Webcams & Buyer's Advice</u></a></li>
<li><a href="https://windows11.techidaily.com/reactivating-non-functional-outlook-email-banners/"><u>Reactivating Non-Functional Outlook Email Banners</u></a></li>
<li><a href="https://windows11.techidaily.com/skip-bloatware-embrace-pure-windows-11-experience/"><u>Skip Bloatware: Embrace Pure Windows 11 Experience!</u></a></li>
<li><a href="https://windows11.techidaily.com/solving-the-invalid-system-id-issue-on-windows-11/"><u>Solving the Invalid System ID Issue on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-enforce-local-policies-to-a-specific-user-in-windows-11/"><u>Steps to Enforce Local Policies to a Specific User in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-resolve-microsoft-store-glitch-error-code-0x800704cf/"><u>Steps to Resolve Microsoft Store Glitch (Error Code 0X800704CF)</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-for-repairing-crashing-ccleaner-in-windows-1011/"><u>Strategies for Repairing Crashing CCleaner in Windows 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-for-tracking-storage-spent-on-apps/"><u>Strategies for Tracking Storage Spent on Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-to-fix-windows-11-assistive-application/"><u>Strategies to Fix Windows 11 Assistive Application</u></a></li>
<li><a href="https://windows11.techidaily.com/streamline-presentations-windows-11-remove-pin-lock/"><u>Streamline Presentations: Windows 11, Remove PIN Lock</u></a></li>
<li><a href="https://windows11.techidaily.com/streamline-your-screen-hotkey-based-program-minimization-techniques/"><u>Streamline Your Screen: Hotkey-Based Program Minimization Techniques</u></a></li>
<li><a href="https://win-howtos.techidaily.com/successful-fixes-and-tips-for-overcoming-error-1603-fatal-installation-issue/"><u>Successful Fixes & Tips for Overcoming Error 1603 - Fatal Installation Issue</u></a></li>
<li><a href="https://windows11.techidaily.com/swift-guide-to-identify-your-graphic-model-in-win11/"><u>Swift Guide to Identify Your Graphic Model in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-rockalldll-dll-not-found-on-windows-xpvista/"><u>Tackling 'Rockalldll' DLL Not Found on Windows XP/Vista</u></a></li>
<li><a href="https://windows11.techidaily.com/tailored-guidance-for-choosing-between-nvidia-gamestudio-drivers/"><u>Tailored Guidance for Choosing Between Nvidia Game/Studio Drivers</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/the-leading-edge-in-online-advertising-fb-insights/"><u>The Leading Edge in Online Advertising   FB Insights</u></a></li>
<li><a href="https://windows11.techidaily.com/tweaking-device-settings-on-windows-11-a-step-by-step-guide/"><u>Tweaking Device Settings on Windows 11: A Step-by-Step Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/unhurried-mobile-migration-with-easy-installation-in-windows-11/"><u>Unhurried Mobile Migration with Easy Installation in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-secure-file-transfer-limitations-on-windows-11/"><u>Unlocking Secure File Transfer Limitations on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-breaks-boundaries-with-iosmacwindows-pc-support/"><u>Windows Breaks Boundaries with iOS/Mac/Windows PC Support</u></a></li>
<li><a href="https://windows11.techidaily.com/wintools-strategy-the-ultimate-performance-boost/"><u>WinTools Strategy: The Ultimate Performance Boost</u></a></li>
<li><a href="https://windows11.techidaily.com/zeroing-out-wsl-complete-uninstallation-in-windows-11/"><u>Zeroing Out WSL: Complete Uninstallation in Windows 11</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>