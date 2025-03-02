---
title: How to Show or Hide the “Dim Display After” Option in the Power Options Menu on Windows
date: 2025-03-01T09:37:04.748Z
updated: 2025-03-01T17:13:32.804Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Show or Hide the “Dim Display After” Option in the Power Options Menu on Windows
excerpt: This Article Describes How to Show or Hide the “Dim Display After” Option in the Power Options Menu on Windows
keywords: Dim Display Control Windows,Hide/Show Display Option,Power Options Adjustments,Windows Display Settings,Change Display Mode Windows,Manage Screen Visibility Windows,Optimize Power Menu Windows
thumbnail: https://thmb.techidaily.com/344ccd42970473c822ce3d8647d1f132f07ed11b189d66bfa12739452e5e4fb4.jpg
---

## How to Show or Hide the “Dim Display After” Option in the Power Options Menu on Windows

 There are times when you need to step away from your PC, and if you’re gone long enough, the screen will automatically dim. Windows does this to preserve your battery, and you can adjust when your display should darken in the Power Options menu by editing the **Dim display after** option.

 If for some reason you can’t see the **Dim display after** option in the Power Options menu, or it’s there and you want to remove it, you can use PowerShell or the Registry Editor to show or hide it. Here’s how.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## How to Show or Hide the “Dim Display After” Option Using PowerShell

 First, launch Windows PowerShell. There are many [ways to open PowerShell on Windows](https://www.makeuseof.com/windows-open-command-prompt-powershell/), but the easiest method is to press **Win + S** to open Windows Search. Then, enter **powershell** in the search box and click on **Windows PowerShell** when it appears in the search results.

![windows powershell in the windows search results](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/windows-powershell-search.jpg)

 In PowerShell, enter the following command to show the **Dim Display after** option in the Power Options menu:

powercfg -attributes SUB_VIDEO 17aaa29b-8b43-4b94-aafe-35f64daaf1ee -ATTRIB_HIDE

 To hide it, enter the following command:

powercfg -attributes SUB_VIDEO 17aaa29b-8b43-4b94-aafe-35f64daaf1ee +ATTRIB_HIDE

 After entering the command you want, hit the **Enter** key on your keyboard for PowerShell to execute it. Afterward, the **Dim display after** option should appear or disappear accordingly in the Power Options menu.

## How to Show or Hide the “Dim display after” Option Using the Registry Editor

 Considering how vital the [Windows Registry](https://www.makeuseof.com/tag/what-is-the-windows-registry-editor-and-how-do-i-use-it-makeuseof-explains/) is for the smooth operation of Windows, you might want to [back up the registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before you edit it. Afterward, open the Registry Editor by pressing **Win + R**, typing **regedit** in the text box, and clicking **OK**.

![regedit](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/regedit.jpg)

 Click **Yes** to bypass the UAC prompt.

 In the address bar of the Registry Editor, copy and paste the following text into it:

HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\7516b95f-f776-4464-8c53-06167f40cc99\17aaa29b-8b43-4b94-aafe-35f64daaf1ee

 On the right panel, double-click the **Attributes** entry to open it up for editing.

![the attributes entry in the windows registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/regedit-dim-display-after-attributes-entry.jpg)

 Then, in the **Value data** text box, enter **1** to hide **Dim display after** in the Power Options menu or **2** to show it.

![modifying the attributes dword in the windows registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/win-attributes-dword.jpg)

 Now you can open the Power Options menu (see [how to open the power options on Windows 10](https://www.makeuseof.com/windows-10-open-power-options/)) and check under **Display** to see if the **Dim display after** option is there or not.

## Controlling the “Dim Display After” Option in the Power Options Menu

 Now that you know how to show or hide **Dim display after**, you know what to do when you can’t find it in the Power Options menu or need to remove it. We recommend keeping it hidden and then bringing it up whenever you need it. This will make sure that no one messes with this important display setting when you’ve set it up perfectly.

<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>

<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://some-guidance.techidaily.com/new-unlocking-spotifys-advertising-opportunities-a-roadmap/"><u>[New] Unlocking Spotify’s Advertising Opportunities A Roadmap</u></a></li>
<li><a href="https://article-posts.techidaily.com/updated-harnessing-the-power-of-quality-photography-without-a-price-tag-for-2024/"><u>[Updated] Harnessing the Power of Quality Photography Without a Price Tag for 2024</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-ranking-reign-supreme-with-these-11-video-seo-techniques-on-youtube/"><u>2024 Approved Ranking Reign Supreme with These 11 Video SEO Techniques on YouTube</u></a></li>
<li><a href="https://techtrends.techidaily.com/dvd-in-windows-10-tv/"><u>DVD をファイナライズする手順 in Windows 10 - TV, 他プレーヤーでの再生可能</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-the-lost-renderer-phenomenon-in-ow2/"><u>Fixing the 'Lost Renderer' Phenomenon in OW2</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/harnessing-2024-innovative-approaches-to-facebook-advertising/"><u>Harnessing 2024 Innovative Approaches to Facebook Advertising</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-convert-cr2-images-to-jpgs-on-windows/"><u>How to Convert CR2 Images to JPGs on Windows</u></a></li>
<li><a href="https://fake-location.techidaily.com/life360-learn-how-everything-works-on-honor-x8b-drfone-by-drfone-virtual-android/"><u>Life360 Learn How Everything Works On Honor X8b | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-windows-11-unveiling-rarely-used-functions/"><u>Mastering Windows 11: Unveiling Rarely Used Functions</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-admin-restricted-setup-issues-in-windows/"><u>Overcoming Admin-Restricted Setup Issues in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-chrome-profile-issues-for-windows-users/"><u>Overcoming Chrome Profile Issues for Windows Users</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-write-restrictions-in-steam-libraries-on-windows-11/"><u>Overcoming Write Restrictions in Steam Libraries on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-razer-device-functionality-in-windows-11/"><u>Restoring Razer Device Functionality in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-guide-to-supercharging-your-windows-start-menu/"><u>The Ultimate Guide to Supercharging Your Window's Start Menu</u></a></li>
<li><a href="https://win-able.techidaily.com/troubleshooting-tips-for-persistent-kinects-and-freezes-in-genshin-impact-on-pc/"><u>Troubleshooting Tips for Persistent Kinects and Freezes in Genshin Impact on PC</u></a></li>
<li><a href="https://win-answers.techidaily.com/ultimate-guide-to-resolving-nba-2k24-error-code-727e66ac/"><u>Ultimate Guide to Resolving NBA 2K24 Error Code 727E66aC</u></a></li>
<li><a href="https://win-howtos.techidaily.com/winning-the-battle-against-unsuccessful-windows-patches-solutions-proven-effective/"><u>Winning the Battle Against Unsuccessful Windows Patches: Solutions Proven Effective</u></a></li>
</ul></div>

