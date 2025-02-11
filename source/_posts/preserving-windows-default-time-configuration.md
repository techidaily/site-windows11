---
title: Preserving Windows' Default Time Configuration
date: 2025-02-09T17:21:04.577Z
updated: 2025-02-11T04:30:20.911Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Preserving Windows' Default Time Configuration
excerpt: This Article Describes Preserving Windows' Default Time Configuration
keywords: Save Windows Time Settings,Keep Windows Clock,Retain Default Windows Time,Preserve Win Time Defaults,Maintain Windows Date & Time,Unaltered Windows Time Setting,Uphold Standard Windows Time
thumbnail: https://thmb.techidaily.com/1b4d426689bd18514a96cb95968cc5a755b1ea7a22bc00e9feef5b8e8bfa78d1.jpg
---

## Preserving Windows' Default Time Configuration

 You’re using your Windows device and notice something strange in the date and time settings. Someone has changed the settings without your knowledge or permission. This makes it difficult to stay on schedule with tasks and activities. In this guide, we’ll show how to stop anonymous users from changing date and time settings on Windows computers.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/X18Dq7rV-xI?si=twFfXIPD0TFmC5EM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How To Prevent Users From Changing the Date and Time on Windows

 There are two ways to prevent users from changing Windows date and time. The first is to use Group Policy Editor, a system administration tool designed to control computer behavior in an organization. While the second way is to use Registry Editor, which allows you to modify Windows registry settings.

 For both methods, you need administrative access to the computer to change it. Once you’ve made the changes, nobody can alter the date and time settings. Let’s look at each method in more detail.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aoMiYpYiFZs?si=qvYvGytDD17fvSXO" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Use the Group Policy Editor

 If your computer is part of an organization and users often change the date and time, use Group Policy Editor to stop it. This will prevent those with limited access to the computer from altering the date and time. However, this method only works for Windows Pro, Enterprise, or Education Editions.

 So, if you have Windows Home Edition, this won’t work. In that case, you must first [activate the Group Policy Editor for Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/). If it seems complicated, skip it and try the next solution instead.

 Follow these steps to prevent users from changing the date and time:

1. Press **Win + R** on your keyboard to open the Run window.
2. Type **gpedit.msc** in the text box and press Enter. This will open the Group Policy Editor window.
3. On the left side of the window, navigate to the following path:  
Computer Configuration > Administrative Templates > System > Locale Services
4. In the right-side pane, double-click on **Disallow user override of locale settings**.  
![Disallow user override of locale settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/disallow-user-override-of-locale-settings.jpg)
5. In the pop-up window, check the **Enabled** radio button.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/YZma8PBO0D8?si=9-qQgGVTuChYd27a" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

6. Then click **Apply** \> **OK** to save the changes.

 This will block anyone from changing the date and time settings on your computer. However, if you have administrative access to the computer, you can still alter the settings.

 If you want to revert to the default settings later, open Group Policy Editor again and change the value of Disallow user override of locale settings back to Not Configured or Disabled. This way, users can change the time and date again.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/PUDdKOsEN74?si=tkZf-KVinjuwmgx9" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Tweak the Registry Editor

 If you’re using Windows Home Edition or have disabled the Group Policy Editor, use the Registry Editor to protect date and time settings. This method is more advanced and has a higher risk of system damage.

 In that case, [back up your Windows registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before changing it. Doing so will restore settings if something goes wrong.

 Follow these steps to stop users from changing the time and date via the registry:

1. [Open the Run command dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/).
2. Type **regedit** in the field and press Enter. This will [open the Registry Editor](https://www.makeuseof.com/windows-11-open-registry-editor/).
3. In the Registry Editor window, navigate to the following path:  
HKEY_CURRENT_USER\Software\Policies\Microsoft\Control Panel\International\
4. If the International folder doesn’t exist, create one. To do that, right-click on Control Panel and select **New** \> **Key**. Name it **International**.
5. Then right-click on **International** and select New > DWORD (32-bit) Value.
6. Name the newly created value **PreventUserOverrides**.
7. Double-click on the **PreventUserOverrides** DWORD value.  
![Use Registry Editor to Prevent Users From Chaning date and time settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/use-registry-editor-to-prevent-users-from-chaning-date-and-time-settings.jpg)
8. In the pop-up window, change the Value data to **1** and click **OK**.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/DCARjc5g5VI?si=9OfovbKBrpoJeXTY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Once you’ve made the changes, close the Registry Editor window and restart your computer.

 To undo this restriction, delete the **PreventUserOverrides** DWORD value from the registry or change the value to **0**. Doing so will enable users to change the time and date again.

## Stop Windows Time and Date Changes

 Now stop unauthorized users from changing the date and time settings on your Windows computer. This keeps your tasks and activities on track. If necessary, you can always undo this restriction.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-cloud.techidaily.com/new-effective-timestamp-integration-in-image-files/"><u>[New] Effective Timestamp Integration in Image Files</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-essential-guide-to-saving-tv-broadcasts-online-for-2024/"><u>[New] Essential Guide to Saving TV Broadcasts Online for 2024</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-top-10-memes-blending-hilarity-and-emotional-depth-on-insta/"><u>[Updated] Top 10 Memes Blending Hilarity and Emotional Depth on Insta</u></a></li>
<li><a href="https://article-posts.techidaily.com/2024-approved-compilation-of-top-5-mkv-apps-for-mac/"><u>2024 Approved Compilation of Top 5 MKV Apps for Mac</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/5-solutions-for-nokia-c12-pro-unlock-without-password-by-drfone-android/"><u>5 Solutions For Nokia C12 Pro Unlock Without Password</u></a></li>
<li><a href="https://windows11.techidaily.com/combat-plan-against-windows-error-0xc00ce556/"><u>Combat Plan Against Window's Error 0xC00CE556</u></a></li>
<li><a href="https://facebook.techidaily.com/creating-a-cloaked-space-for-online-dialogues/"><u>Creating a Cloaked Space for Online Dialogues</u></a></li>
<li><a href="https://windows11.techidaily.com/cut-the-cord-joining-dualshock-to-pc/"><u>Cut the Cord: Joining DualShock to PC</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-how-to-unlock-apple-iphone-15-withwithout-sim-card-by-drfone-ios/"><u>In 2024, How to Unlock Apple iPhone 15 with/without SIM Card</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-windows-11-menu-erase-show-more-options/"><u>Mastering Windows 11 Menu: Erase Show More Options</u></a></li>
<li><a href="https://windows11.techidaily.com/proven-file-sync-software-the-most-trusted-windows-picks/"><u>Proven File Sync Software: The Most Trusted Windows Picks</u></a></li>
<li><a href="https://win-dash.techidaily.com/1722968149394-quick-guide-to-downloading-your-zebra-gk420d-driver-no-hassle-just-success/"><u>Quick Guide to Downloading Your Zebra GK420D Driver - No Hassle, Just Success!</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-tips-for-syncing-two-windows-displays/"><u>Quick Tips for Syncing Two Windows Displays</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/solution-ptfe-or-rubber-with-specific-resistance-to-acids-such-as-epdm-ethylene-propylene-diene-monomer-would-be-suitable-liners/"><u>Solution: PTFE or Rubber with Specific Resistance to Acids, Such as EPDM (Ethylene Propylene Diene Monomer), Would Be Suitable Liners.</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-repair-windows-event-viewer-in-windows-11/"><u>Steps to Repair Windows Event Viewer in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/tailoring-aesthetics-for-windows-terminal/"><u>Tailoring Aesthetics for Windows Terminal</u></a></li>
<li><a href="https://windows11.techidaily.com/tutorial-enabling-or-disabling-wi-fi-cost-meter-in-windows-11/"><u>Tutorial: Enabling or Disabling Wi-Fi Cost Meter in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-windows-access-your-outlook-preview/"><u>Unlocking Windows: Access Your Outlook Preview</u></a></li>
<li><a href="https://some-approaches.techidaily.com/wmvaiff-online-movavi/"><u>WMV/Aiff를 무료로 Online 상대 전역 변환: Movavi 소스가 제공</u></a></li>
</ul></div>

