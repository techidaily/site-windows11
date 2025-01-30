---
title: Accessing Stealthed Elements in Windows 11 UI
date: 2025-01-29T07:21:44.199Z
updated: 2025-01-30T04:57:55.550Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Accessing Stealthed Elements in Windows 11 UI
excerpt: This Article Describes Accessing Stealthed Elements in Windows 11 UI
keywords: Windows UI Stealth Access,Stealth Elements Window,Win11 UI Stealthy Extractions,Elusive Elements UWP,Hidden UI Windows Find,Stealthed UI Element Locate,Silent Elements In Windows UI
thumbnail: https://thmb.techidaily.com/0177669a9f7e47198243a9fecb2a2f8d7897c9576df374da55c9c20dfb4332d6.jpg
---

## Accessing Stealthed Elements in Windows 11 UI

 The system tray, which is part of the Taskbar and shows the apps you use frequently, among other things, can become overcrowded.

 If that happens, you can remove a couple of app icons, as well as the hidden icons menu, to make it less cluttered. And if you can’t find the app icons you need or the hidden icons menu is missing, you can add those too.

## How to Show or Hide System Tray Icons on Windows 11

 To show more icons in the system tray, you need to access the Taskbar's settings by pressing **Win + I**, selecting **Personalization** on the left side menu, and then clicking **Taskbar** in the right panel.

![Go to Taskbar Settings in the Personalization Tab of Windows Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/6-go-to-taskbar-settings-in-the-personalization-tab-of-windows-settings-app.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/U_aNKnMTPjo?si=Og_mEt7NP3Fbsg2n" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 In Taskbar settings, scroll down and expand the **Other system tray icons** section. Find the icon you want to show (its toggle will be set to **Off** if it isn’t in the system tray) and click on the toggle on its right to set it to the **On** position.

![you can turn system tray icons on and off in the Taskbar settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/system-tray-icons-windows-11.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/lxv4NM-89CU?si=Uj5rOkhrwZ_6QIuW" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If you want to remove the system tray icon, simply set the toggle to **Off**.

 Another way to remove icons from the system tray is to place them in the hidden icons menu. This is the menu that appears when you click the **up caret** icon in the system tray. When the menu is opened, the icon becomes a **down caret**.

![the hidden icons menu on Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/hidden-icons-menu-windows-11.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/XS1nQCe95LU?si=A2dhdFkSAI61_nKA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 To remove an icon from the system tray and place it into the hidden icons menu, click and drag it into the **up caret**. And when you expand the hidden icons menu, you will see that the icon is inside.

 When you remove system tray icons from the settings, they will not appear in the hidden icons menu but will be removed completely.

 To add the icon back in the system tray, click and drag it from the hidden icons menu and then place it in the system tray.

## How to Show or Hide the Hidden Icon Menu

 As mentioned earlier, the hidden icon menu is what appears when you click the **up caret** in the system tray. You can also hide and show this menu as you please.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/ZLb1ViO4WR8?si=g_aiHGNCd7eAvmDM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Using the Settings App

 If you can't see the hidden icon menu, you can show it from the Taskbar settings as well. To get there, right-click an empty part of the Taskbar and select **Taskbar settings**.

![opening Taskbar settings by right clicking an empty part of the Taskbar](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/opening-taskbar-settings.jpg)

 Scroll down until you reach the **Other system tray icons** section and expand it. To reveal the hidden icon menu, set the toggle next to the **Hidden menu icon** option to **On**. To hide it, set the toggle to **Off**.

### Using the Registry Editor

 If you’re not familiar with the Registry Editor, we recommend that you read our guide on [what the Windows Registry is](https://www.makeuseof.com/tag/what-is-the-windows-registry-editor-and-how-do-i-use-it-makeuseof-explains/) before continuing. It’s crucial that you know what you’re working with before moving forward. Also, be sure to [make a backup of the Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) while you're at it.

 With that out of the way, you can open the Registry Editor by pressing **Win + R**, entering **regedit** in the text box, and then clicking on **OK**. In the UAC prompt, click **Yes** to launch the tool.

 For more methods to launch the Registry Editor, please check out our guide on [ways to open the Registry Editor on Windows 11](https://www.makeuseof.com/windows-11-open-registry-editor/).

 Afterward, copy and paste the following path into the address bar of the Registry Editor and hit the **Enter** key:

HKEY_CURRENT_USER\Software\Classes\Local Settings\Software\Microsoft\Windows\CurrentVersion\TrayNotify

 Next, double-click the **SystemTrayChevronVisibility** value in the right panel.

![the SystemTrayChevronVisibility value in the Windows Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/systemtraychevronvisibility-value-regedit-windows.jpg)

 To show the hidden icon menu, set the **Value data** text box to **1** and click **OK**.

![setting the SystemTrayChevronVisibility value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/systemtraychevronvisibility-value-data.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/OZQJUTr44rA?si=ADA0nD1VnXjR_sH0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 And to hide the hidden icon menu set the **Value data** text box to **0** and click **OK**.

## Control the Icons that Appear in the System Tray on Windows 11

 Whether you want to add icons or remove them from the system tray, the process is simple. Just go to the Taskbar settings and turn them on or off as needed. You can also hide or show the hidden icon menu in the process.

 And if you want to show or hide the clock and date in the system tray, you can do that too.

 If that happens, you can remove a couple of app icons, as well as the hidden icons menu, to make it less cluttered. And if you can’t find the app icons you need or the hidden icons menu is missing, you can add those too.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://article-files.techidaily.com/new-2024-approved-mastering-iphone-x-lens-capabilities-a-guide/"><u>[New] 2024 Approved Mastering iPhone X Lens Capabilities A Guide</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-in-2024-the-path-to-autoplay-configuring-youtube-content-for-uninterrupted-streaming/"><u>[New] In 2024, The Path to Autoplay Configuring Youtube Content for Uninterrupted Streaming</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ed-2024-approved-superior-earners-on-social-media-platform/"><u>[Updated] 2024 Approved Superior Earners on Social Media Platform</u></a></li>
<li><a href="https://extra-tips.techidaily.com/updated-architecting-top-quality-canon-chrono-films/"><u>[Updated] Architecting Top Quality Canon Chrono Films</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-in-2024-idle-geniuses-top-12-pc-classics/"><u>[Updated] In 2024, Idle Geniuses Top 12 PC Classics</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/2024-approved-mastering-macs-screenshots-best-free-software-compared/"><u>2024 Approved Mastering Mac's Screenshots Best FREE Software Compared</u></a></li>
<li><a href="https://win-web.techidaily.com/effective-strategies-to-mitigate-risks-of-static-electricity-insights-from-yl-computing-and-software-solutions/"><u>Effective Strategies to Mitigate Risks of Static Electricity: Insights From YL Computing & Software Solutions</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/financially-friendly-furry-cam-review/"><u>Financially Friendly Furry Cam Review</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-bypassing-do-not-have-permission-windows-errors/"><u>Guide to Bypassing 'Do Not Have Permission' Windows Errors</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-recover-from-failed-discord-windows-updates/"><u>Guide to Recover From Failed Discord Windows Updates</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-resolve-valorants-perpetual-loading-problem-for-smooth-gameplay/"><u>How to Resolve Valorant's Perpetual Loading Problem for Smooth Gameplay</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-language-switches-using-keyboard-shortcuts-on-windows-11/"><u>Mastering Language Switches: Using Keyboard Shortcuts on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/mastery-of-multitasking-reviving-non-operational-keys-in-windows-os/"><u>Mastery of Multitasking: Reviving Non-Operational Keys in Windows OS</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-the-directive-not-empty-hurdle-insights-to-eradicate-error-0x80070091/"><u>Overcoming the Directive Not Empty Hurdle: Insights to Eradicate Error 0X80070091</u></a></li>
<li><a href="https://windows11.techidaily.com/restore-missing-bluetooth-top-9-fixes-for-windows-11-users/"><u>Restore Missing Bluetooth: Top 9 Fixes for Windows 11 Users</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlining-windows-11-browsing-key-techniques-unveiled/"><u>Streamlining Windows 11 Browsing: Key Techniques Unveiled</u></a></li>
<li><a href="https://windows11.techidaily.com/unleash-peak-performance-tuning-amd-graphics-on-windows/"><u>Unleash Peak Performance: Tuning AMD Graphics on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/unlock-global-dialogues-utilizing-hotkey-tricks-in-windows-language-switching/"><u>Unlock Global Dialogues: Utilizing Hotkey Tricks in Windows Language Switching</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-the-power-of-painting-ms-paint-in-windows-11/"><u>Unlocking the Power of Painting: MS Paint in Windows 11</u></a></li>
</ul></div>

