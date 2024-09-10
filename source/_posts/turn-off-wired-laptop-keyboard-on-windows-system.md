---
title: Turn Off Wired Laptop Keyboard on Windows System
date: 2024-09-09T12:01:38.022Z
updated: 2024-09-10T12:01:38.022Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Turn Off Wired Laptop Keyboard on Windows System
excerpt: This Article Describes Turn Off Wired Laptop Keyboard on Windows System
keywords: Disable Win Keyboard,Turnoff PC Keys,Halt Wired Keyboard,Mute Notebook Input,Stop Windows Keyboard,Shut Down Laptop Cables,Inactive PC Keys
thumbnail: https://thmb.techidaily.com/6b1891992681f1be8b20a193547f611a2de266588bbed170087f473de1cb604a.jpg
---

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2123512/26400" target="_top" id="2123512">
  <img src="//a.impactradius-go.com/display-ad/26400-2123512" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2123512/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Turn Off Wired Laptop Keyboard on Windows System

 Sometimes you don't want your laptop's keyboard to take inputs. This is usually because you're plugging in an external keyboard, either because the built-in one is broken or you just want a larger typing space with a full-sized keyboard.

 However, since the keyboard is an integral part of your portable computer, disabling its primary input method is a little tricky. Here, we show you how to temporarily and permanently disable the laptop keyboard on Windows 10 and 11\.

## How to Find Your Laptop Keyboard in Device Manager

 Whether you want to disable your laptop keyboard temporarily or permanently, you will need to uninstall the input device from Device Manager.

 For this, you’ll need to identify the integrated keyboard in Device Manager. Since Device Manager will list all the recognized keyboards, including external keyboards, here’s how you can identify your laptop keyboard from the list.

 To identify the built-in keyboard in Device Manager:

1. Press **Win + R** to open **Run**.
2. Type **devmgmt.msc** and click **OK** to open Device Manager.
3. In Device Manager, expand the **Keyboards** section.  
![device manager keyboards 1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/07/device-manager-keyboards-1.jpg)
4. Right-click on the first keyboard entry **(HID/Standard)** and select **Properties**.
<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136617/26400" target="_top" id="2136617">
  <img src="//a.impactradius-go.com/display-ad/26400-2136617" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136617/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
5. In the **General** tab, check the **Location** section. If it says **Location 1** or **Plugged into keyboard port**, it is likely your laptop’s internal keyboard.
6. Bluetooth and USB keyboards will show **On Bluetooth Low Energy** and **On US Input Device**, respectively as its location.

 If you don't find your keyboard listed, make sure you have [set Device Manager to show hidden devices.](https://www.makeuseof.com/view-hidden-devices-in-windows/)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118318/7443" target="_top" id="2118318">
  <img src="//a.impactradius-go.com/display-ad/7443-2118318" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118318/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Disable the Laptop Keyboard Temporarily

 To disable your laptop’s keyboard temporarily:

1. Right-click on all the **HID** and **PS/2 Keyboard** entries with the **Properties Location** set to **Location 1** or **Plugged into keyboard.**  
![uninstall keyboard device device manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/07/uninstall-keyboard-device-device-manager.jpg)
2. Next, select **Uninstall Device** from the context menu.
3. Click **Yes** to confirm the action.
4. That’s it. You have disabled your laptop’s internal keyboard successfully.

 That said, this is a temporary solution. As soon as you restart your system, Windows will look for the connected but unrecognized devices and install the necessary drivers to make them functional.

## How to Disable Your Laptop Keyboard Permanently

![disable ps 2 port 18042prt command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/07/disable-ps-2-port-18042prt-command-prompt.jpg)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2123511/26400" target="_top" id="2123511">
  <img src="//a.impactradius-go.com/display-ad/26400-2123511" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2123511/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 If you want to disable your laptop keyboard permanently, you can disable your laptop’s built-in keyboard driver PS/2 i8042prt service using the Command Prompt. We'll use the sc command-line utility to configure the service and set its start parameter to disabled.

 To disable the laptop keyboard permanently:

1. Press the **Win key** and type **cmd** in the Windows search bar.
2. Right-click on **Command Prompt** and select **Run as Administrator**. Click **Yes** when the UAC prompt appears.
3. In the Command Prompt window, type the following command and press Enter:  
`sc config i8042prt start= disabled`
4. When the success message appears, close the Command Prompt, and restart your PC. After the restart, your laptop keyboard will stop registering any inputs.

 Note that, for this to work, you will need to uninstall your keyboard from Device Manager as shown above and restart your PC.

 If you change your mind and want to re-enable the keyboard, you can use the following command in an [elevated Command Prompt](https://www.makeuseof.com/windows-11-open-command-prompt/).

`sc config i8042prt start= auto`

 Once you see the success message, restart your PC to apply the changes.

## Disable the Built-in Keyboard Using an Incompatible Driver

 Another quirky solution to disable a built-in keyboard is to install an incompatible driver for the input device. Here's how to do it.

1. Open Device Manager and expand the **Keyboard** section.
2. Right-click on your laptop keyboard device and select **Update driver**.  
![Update the Relevant Keyboard Driver in Windows Device Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/5-update-the-relevant-keyboard-driver-in-windows-device-manager.jpg)
3. Select **Browse my computer for drivers**.  
<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134228/18498" target="_top" id="2134228">
  <img src="//a.impactradius-go.com/display-ad/18498-2134228" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134228/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![update driver search automatically for drivers device manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/update-driver-search-automatically-for-drivers-device-manager.jpg)
4. Next, select **Let me pick from a list of available drivers on my computer**.  
![update driver keyboard pick from list of available drivers device manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/update-driver-keyboard-pick-from-list-of-available-drivers-device-manager.jpg)
5. Uncheck the **Show compatible hardware** option.
6. Select a random manufacturer under the **Manufacturer** column.  
![install incompatible keyboard driver windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/install-incompatible-keyboard-driver0windows.jpg)
7. Click **Next**. Click **Yes** if an **Update Driver Warning** dialog appears.
8. Once installed, close Device Manager and reboot your computer.

 After the restart, your laptop keyboard will stop working. If you need to install the correct driver again to enable the keyboard, right-click on the keyboard device and select **Update driver**. Next, select **Search automatically for drivers**. Windows will look for a compatible driver and install it.

![update driver search automatically for drivers device manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/update-driver-search-automatically-for-drivers-device-manager.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123749/7443" target="_top" id="2123749">
  <img src="//a.impactradius-go.com/display-ad/7443-2123749" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123749/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Alternatively, select **Browse my computer for drivers** in the Update Drivers dialogue. Next, select **Let me pick from a list of available drivers on my computer**. Make sure the **Show compatible hardware** option is enabled. Select an **HID Keyboard Device** driver from the list and click **Next**.

![install compatible hardware driver keyboard device manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/install-compatible-hardware-driver-keyboard-device-manager.jpg)

 Wait for the driver to install. Once done, reboot your computer, and the keyboard will start working again.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115916/19272" target="_top" id="2115916">
  <img src="//a.impactradius-go.com/display-ad/19272-2115916" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115916/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Disable Your Laptop Keyboard Permanently on Windows

 The built-in chiclet keyboard on your laptop is the primary input method available, so there is no way to disable it with a single click. Also, you wouldn’t want to disable your keyboard accidentally. If you determine your keyboard to have gone rogue and typing on its own, you can permanently disable it using the Command Prompt and Device Manager.

 That said, apart from the hardware issues, your laptop keyboard can act up for many other reasons. To fix your keyboard, check for pending driver updates, use the built-in troubleshooter, or simply disable the individual keys.

 Sometimes you don't want your laptop's keyboard to take inputs. This is usually because you're plugging in an external keyboard, either because the built-in one is broken or you just want a larger typing space with a full-sized keyboard.

 However, since the keyboard is an integral part of your portable computer, disabling its primary input method is a little tricky. Here, we show you how to temporarily and permanently disable the laptop keyboard on Windows 10 and 11\.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://vp-tips.techidaily.com/new-enhancing-productivity-business-growth-via-virtual-reality/"><u>[New] Enhancing Productivity Business Growth via Virtual Reality</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-greatest-action-packed-gaming-escapades-top-10/"><u>[Updated] Greatest Action-Packed Gaming Escapades (Top 10)</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-unsealing-the-secret-permanently-ditch-youtube-shorts/"><u>[Updated] Unsealing the Secret Permanently Ditch YouTube Shorts</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/all-about-factory-reset-what-is-it-and-what-it-does-to-your-realme-11-5g-drfone-by-drfone-reset-android-reset-android/"><u>All About Factory Reset, What Is It and What It Does to Your Realme 11 5G? | Dr.fone</u></a></li>
<li><a href="https://tech-haven.techidaily.com/choosing-your-sidekick-how-github-copilot-stands-up-to-chatgpt-in-code-development/"><u>Choosing Your Sidekick: How GitHub Copilot Stands Up to ChatGPT in Code Development</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-notepad-tools-winning-for-pen-tablets/"><u>Essential Notepad Tools: Winning For Pen-Tablets</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-steps-to-reopen-battlenet-on-windows-desktop/"><u>Essential Steps to Reopen Battle.net on Windows Desktop</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-inaccessible-files-in-windows-os/"><u>Fixing Inaccessible Files in Windows OS</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-silent-xbox-console-windows-techniques/"><u>Fixing Silent Xbox Console: Windows Techniques</u></a></li>
<li><a href="https://windows11.techidaily.com/guidelines-for-overcoming-installer-hurdles-in-windows-environments/"><u>Guidelines for Overcoming Installer Hurdles in Windows Environments</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-hardware-problems-were-detected-error-in-the-windows-memory-diagnostic-tool/"><u>How to Fix the Hardware Problems Were Detected Error in the Windows Memory Diagnostic Tool</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-hide-a-zip-archive-within-an-image-file-in-windows-10-and-11/"><u>How to Hide a ZIP Archive Within an Image File in Windows 10 & 11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-mend-interruptexception-crash-on-pcs-running-windows-1011/"><u>How to Mend INTERRUPT_EXCEPTION Crash on PCs Running Windows 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-regain-control-over-faulty-anydesk-service/"><u>How To Regain Control Over Faulty AnyDesk Service</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-rescue-lost-music-from-note-30i-by-fonelab-android-recover-music/"><u>How to Rescue Lost Music from Note 30i</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-use-device-manager-to-reinstall-your-drivers-in-windows-10-and-7-by-drivereasy-guide/"><u>How to use Device Manager to reinstall your drivers in Windows 10 and 7</u></a></li>
<li><a href="https://extra-hints.techidaily.com/in-2024-avoid-virtual-reality-queasiness-5-useful-tips/"><u>In 2024, Avoid Virtual Reality Queasiness 5 Useful Tips</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/24-cutting-edge-techniques-for-powerful-youtube-thumbnail-designs/"><u>In 2024, Cutting-Edge Techniques for Powerful YouTube Thumbnail Designs</u></a></li>
<li><a href="https://blog-min.techidaily.com/in-2024-how-to-teleport-your-gps-location-on-vivo-y78plus-t1-edition-drfone-by-drfone-virtual-android/"><u>In 2024, How To Teleport Your GPS Location On Vivo Y78+ (T1) Edition? | Dr.fone</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-the-most-useful-tips-for-pokemon-go-ultra-league-on-vivo-v29-drfone-by-drfone-virtual-android/"><u>In 2024, The Most Useful Tips for Pokemon Go Ultra League On Vivo V29 | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/key-ways-to-confirm-windows-11-is-running/"><u>Key Ways to Confirm Windows 11 Is Running</u></a></li>
<li><a href="https://windows11.techidaily.com/master-your-windows-workspace-5-folder-tips-revealed/"><u>Master Your Windows Workspace: 5 Folder Tips Revealed</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-achievement-integration-in-vintage-games-using-retroarch/"><u>Mastering Achievement Integration in Vintage Games Using Retroarch</u></a></li>
<li><a href="https://win-forum.techidaily.com/mastering-digital-interaction-on-popular-platforms-like-facebook-twitter-instagram-youtube/"><u>Mastering Digital Interaction on Popular Platforms Like Facebook, Twitter, Instagram, Youtube</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-visual-note-taking-with-obsidian-paint/"><u>Mastering Visual Note-Taking with Obsidian Paint</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-windows-storage-management/"><u>Mastering Windows Storage Management</u></a></li>
<li><a href="https://windows11.techidaily.com/maximizing-space-in-windows-without-data-loss/"><u>Maximizing Space in Windows Without Data Loss</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-windows-system-crashes-fixing-c0000022-fatalities/"><u>Navigating Windows System Crashes: Fixing C0000022 Fatalities</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-windows-lock-and-unlock-function-fn-key-steps/"><u>Navigating Windows: Lock and Unlock Function (Fn) Key Steps</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-fix-restoring-itunes-functionality-in-windows/"><u>Quick Fix: Restoring iTunes Functionality in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-remedies-for-windows-nine-solutions-to-revive-your-non-responsive-keyboard-shortcuts/"><u>Quick Remedies for Windows: Nine Solutions to Revive Your Non-Responsive Keyboard Shortcuts</u></a></li>
<li><a href="https://windows11.techidaily.com/redirecting-and-reinstating-windows-1011s-ms-store/"><u>Redirecting and Reinstating Windows 10/11'S MS Store</u></a></li>
<li><a href="https://windows11.techidaily.com/reinstating-typical-sort-and-group-features-on-files/"><u>Reinstating Typical Sort and Group Features on Files</u></a></li>
<li><a href="https://windows11.techidaily.com/rejuvenating-stalled-adobe-ps-on-win/"><u>Rejuvenating Stalled Adobe PS on Win</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-windows-needs-old-pass-troubleshooting-tips/"><u>Resolving Windows Needs Old Pass: Troubleshooting Tips</u></a></li>
<li><a href="https://windows11.techidaily.com/reversing-unable-to-open-share-issue-in-windows/"><u>Reversing Unable to Open Share Issue in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/revising-windows-1011-login-limit-settings-post-failed-sign-ins/"><u>Revising Windows 10/11 Login Limit Settings Post-Failed Sign-Ins</u></a></li>
<li><a href="https://windows11.techidaily.com/seamless-connectivity-on-pcs-winnet-steps-to-verify/"><u>Seamless Connectivity on PCs: WinNet Steps to Verify</u></a></li>
<li><a href="https://windows11.techidaily.com/securely-delete-your-files-at-the-click-windows-11s-desktop-trash-tutorial/"><u>Securely Delete Your Files at the Click: Windows 11'S Desktop Trash Tutorial</u></a></li>
<li><a href="https://windows11.techidaily.com/slumber-procedures-for-windows-devices/"><u>Slumber Procedures for Windows Devices</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/techniques-for-ensuring-strong-layer-bonds-in-your-3d-prints/"><u>Techniques for Ensuring Strong Layer Bonds in Your 3D Prints</u></a></li>
<li><a href="https://windows11.techidaily.com/the-art-of-image-rotation-on-your-windows-11-pc/"><u>The Art of Image Rotation on Your Windows 11 PC</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/top-12-ultimate-tycoon-adventures-for-unbeatable-engagement-for-2024/"><u>Top 12 Ultimate Tycoon Adventures for Unbeatable Engagement for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/unleashing-the-full-potential-of-win-for-ps1-gaming-duckstations-insight/"><u>Unleashing the Full Potential of WIN for PS1 Gaming - Duckstation's Insight</u></a></li>
<li><a href="https://windows11.techidaily.com/unlock-the-full-potential-of-your-computers-booting-process-with-configurations/"><u>Unlock the Full Potential of Your Computer's Booting Process with Configurations</u></a></li>
<li><a href="https://change-location.techidaily.com/why-does-the-pokemon-go-battle-league-not-available-on-samsung-galaxy-f14-5g-drfone-by-drfone-virtual-android/"><u>Why does the pokemon go battle league not available On Samsung Galaxy F14 5G | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-11s-aesthetic-edge-maximizing-backdrop-impact/"><u>Windows 11'S Aesthetic Edge: Maximizing Backdrop Impact</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-whisperer-learning-to-activate-the-hidden-character-tracker/"><u>Windows Whisperer: Learning to Activate the Hidden Character Tracker</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>