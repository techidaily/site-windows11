---
title: Essential Steps to Locate GPO in Windows OS
date: 2024-11-19T18:21:59.568Z
updated: 2024-11-24T23:00:00.327Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Essential Steps to Locate GPO in Windows OS
excerpt: This Article Describes Essential Steps to Locate GPO in Windows OS
keywords: Find GPO Windows,Windows GPOP Search,Navigate GPO Windows,GPO Locator Windows,Identify Window's GPO,Access GPO in OS,Windows GPO Settings
thumbnail: https://thmb.techidaily.com/e68430bcb106e10e6ed671e16682f01d022f0799c626556c343ddc595fa9cde5.jpg
---

## Essential Steps to Locate GPO in Windows OS

 Changing a group policy is something that many Windows users will have to do at some point in their life. However, knowing the path to a particular setting in the Local Group Policy Editor (LGPE) is not so simple, considering the sheer scale of the folders and subfolders within the tool.

 In this guide, we're going to show you three ways to search for the group policies you need so you don't get lost.

## 1\. Search Using the Local Group Policy Editor's Filter Option

 Press **Win + S** to bring up Windows Search, search for **edit group policy**, and click on **Edit group policy** in the search results. This will launch the LGPE.

 Only the Pro and Enterprise editions of Windows come with the LGPE pre-installed, but there is a way you can [access the LGPE on Home editions](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/).

 In the left pane, right-click the **Administrative Templates** folder (it's the only folder that allows you to search this way), and click **Filter On** to enable filtering. Right-click the folder again, and this time, select **Filter Options**.

![the menu that shows up when you right-click Administrative Templates in the Loca Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/06/lgpe-search-filter-option.jpg)

 In the Filter Options dialog box, make sure to check the **Enable Keyword Filters** checkbox. Next, in the text box next to **Filter for word(s)**, enter the search terms for the policy or, if you know it, the exact name of the policy.

![the Filter Options dialog box with the Enable Keywords and filter text box part showing](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/06/lgpe-search-filter-options-search-phrase-windows.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Q_69vX9wnRE?si=FtLxkpRhPORqcMeE&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 In the dropdown next to that filter text box, you can choose the following options:

* **Any**: The policy you’re searching for contains one or more of the words entered in the filter text box.
* **All**: The policy you’re searching for contains each word entered in the filter text box.
* **Exact**: The policy you're searching for contains the exact phrase entered in the filter text box.

 Next, check the **Enable Requirement Filters** checkbox and click the **Select All** button (this means you want to search for the policy on all platforms). Then, click **OK**.

![the Filter Options dialog box showing the requirements section](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/06/lgpe-search-filter-option-requirements-filters.jpg)

 Back in the LGPE, you should start to see the folders and policies decrease in number since others have been filtered out. To quickly find the policy you were searching for, click **All Settings**.

![All Settings selected in the Local Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/06/lgpe-search-filter-results-windows.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/hXIq2G0nShk?si=5Z4Fwv7ZB6oKWsdd&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 While editing, keep in mind that changing the right [group policies can make your PC better](https://www.makeuseof.com/tag/12-ways-windows-group-policy-can-make-pc-better/), or, if you tweak the wrong one, make it worse.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/MPoakxUNf9o?si=S-ppSqzHzN9VrxC7&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Search Using the Group Policy Website

 Besides using filters in the LGPE, you can also use the [Group Policy Search](https://gpsearch.azurewebsites.net/) website. While on the site, click the **filter icon** in the top left corner and uncheck all the products you don’t want to include in the search.

![filtering out products on the Group Policy Search website](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/06/gps-website-filters.jpg)

 Click on the search box at the top, enter the search terms for the policy, and hit the **Enter** key. If you want to do an exact search, be sure to put the search string within quotes, like “disable context menu,” for example.

![searching for a group policy on the Group Policy Search website](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/06/gps-website-searching-policy.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aRMCbJxLuwE?si=E5sfJvoqkv1qCMWz&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 The search policy will appear in the second column, so click on it to reveal more information about it in a pop-up. You will see where to find the policy in the LGPE directly under the heading.

![the search results on the Group Policy Search website](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/06/gps-website-searching-policy-results.jpg)

 Where it says **Key**, you can see where to find the setting in the Registry Editor.

## 3\. Search Using the Group Policy Settings Reference

 If you prefer something offline and a little easier to access compared to searching with the LGPE's filters and the Group Policy Search website, Microsoft has a document you can use. So, download the [Group Policy Settings Reference](https://www.microsoft.com/en-us/download/details.aspx?id=25250) sheet and open it in Excel.

 To search for a policy, click on the **filter icon** next to the **Policy Setting Name** heading in the **C** column. In the text box that says **Search**, type in search terms for the policy you want to find, and then hit the **Enter** key.

![searching the group policy reference sheet](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/06/group-policy-reference-sheet-text-filter.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/6KXVWj6Ar1M?si=Cd_jktmoN3e9OzH3&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 The policies that match the search terms will appear in column **C**. You can find the location of the policy in column **E** under the **Policy Path** heading.

![the results of searching for a group policy in the reference sheet](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/06/group-policy-reference-sheet-policy-path.jpg)

 That’s the folder you need to look at in the LGPE to find the policy that you need to edit.

## Find the Group Policy You Need on Windows

 Now you should be able to find the group policies you need to make your PC better. We know how overwhelming it can be to use the Local Group Policy Editor, but with these tools, it should become a little easier. And if your edits don't take effect right away, there’s a way for you to manually refresh the LGPE to apply the settings immediately.

 In this guide, we're going to show you three ways to search for the group policies you need so you don't get lost.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-tips.techidaily.com/hannel-titling-101-the-quest-for-an-original-label-for-2024/"><u>[New] Channel Titling 101 The Quest for an Original Label for 2024</u></a></li>
<li><a href="https://fox-helps.techidaily.com/updated-cultivating-a-thoughtful-approach-to-youtube-feedback/"><u>[Updated] Cultivating a Thoughtful Approach to YouTube Feedback</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-in-2024-social-network-showdown-tiktok-vs-snap/"><u>[Updated] In 2024, Social Network Showdown TikTok Vs Snap</u></a></li>
<li><a href="https://windows11.techidaily.com/gateway-to-gaming-glory-using-dosbox-x-for-pc-classics/"><u>Gateway to Gaming Glory: Using DOSBox-X for PC Classics</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-fix-the-0x0000004e-error-in-windows-10-and-11/"><u>How to Fix the 0X0000004E Error in Windows 10 and 11</u></a></li>
<li><a href="https://iphone-transfer.techidaily.com/in-2024-4-ways-to-transfer-contacts-from-apple-iphone-11-pro-max-to-iphone-quickly-drfone-by-drfone-transfer-from-ios/"><u>In 2024, 4 Ways to Transfer Contacts from Apple iPhone 11 Pro Max to iPhone Quickly | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-everything-you-need-to-know-about-lock-screen-settings-on-your-google-pixel-8-pro-by-drfone-android/"><u>In 2024, Everything You Need to Know about Lock Screen Settings on your Google Pixel 8 Pro</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-mirror-your-poco-f5-5g-screen-to-pc-with-chromecast-drfone-by-drfone-android/"><u>In 2024, How to Mirror Your Poco F5 5G Screen to PC with Chromecast | Dr.fone</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-will-pokemon-go-ban-the-account-if-you-use-pgsharp-on-realme-note-50-drfone-by-drfone-virtual-android/"><u>In 2024, Will Pokémon Go Ban the Account if You Use PGSharp On Realme Note 50 | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/master-linux-without-wsl/"><u>Master Linux without WSL</u></a></li>
<li><a href="https://ai-live-streaming.techidaily.com/overcoming-hurdles-ensuring-a-smooth-launch-of-battlefield-4-on-your-pc/"><u>Overcoming Hurdles: Ensuring a Smooth Launch of Battlefield 4 on Your PC</u></a></li>
<li><a href="https://windows11.techidaily.com/reclaiming-control-from-a-wildly-wandering-mouse/"><u>Reclaiming Control From a Wildly Wandering Mouse</u></a></li>
<li><a href="https://windows11.techidaily.com/remedying-spontaneous-command-triggers-in-os/"><u>Remedying Spontaneous Command Triggers in OS</u></a></li>
<li><a href="https://windows11.techidaily.com/sayonara-to-sluggish-keys-top-tricks-for-win-11s-faster-typing/"><u>Sayonara to Sluggish Keys: Top Tricks for Win 11'S Faster Typing</u></a></li>
<li><a href="https://windows11.techidaily.com/securing-your-virtual-world-steps-for-epic-save-safety/"><u>Securing Your Virtual World: Steps for Epic Save Safety</u></a></li>
<li><a href="https://windows11.techidaily.com/simplified-gpo-analysis-via-gpresult-command/"><u>Simplified GPO Analysis via GPResult Command</u></a></li>
<li><a href="https://discover-excellent.techidaily.com/unlock-audio-tracks-in-movies-with-these-three-simple-techniques/"><u>Unlock Audio Tracks in Movies with These Three Simple Techniques</u></a></li>
</ul></div>

