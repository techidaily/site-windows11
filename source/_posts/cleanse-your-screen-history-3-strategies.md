---
title: Cleanse Your Screen History - 3 Strategies
date: 2024-07-11T22:25:04.545Z
updated: 2024-07-12T22:25:04.545Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Cleanse Your Screen History - 3 Strategies
excerpt: This Article Describes Cleanse Your Screen History - 3 Strategies
keywords: Clear Screen Past,Remove History Data,Erase Screen Logs,Wipe Screenscape,Screen Clean-Up Guide,Hide Screen History,History Purge Tips
thumbnail: https://thmb.techidaily.com/ced9cab3bb4f4b670e0a461fa0277071d0fe6cc512c46ece52a065d147ecc37a.jpg
---

## Cleanse Your Screen History - 3 Strategies

 When you change the wallpaper on your device, Windows stores a thumbnail of the recently used image in the “wallpaper history” section. Usually, this section contains around five images.

 You might want to clear your wallpaper history for privacy purposes. For example, clearing wallpaper history prevents others from seeing the private images you’ve previously used as wallpapers. In this article, we’ll check out how to clear the Windows wallpaper history.

## How to View Your Wallpaper History on Windows

 To view the five most recent pictures you’ve used as a background, simply follow these steps:

1. Press **Win + I** to open the system settings.
2. Click the **Personalization** option.
3. Click the **Background** drop-down menu and select **Picture**. This should display the five pictures you’ve previously used as wallpapers.

![Viewing wallpaper history on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/viewing-wallpaper-history-on-windows.jpg)

 If there's anything here you don't want people to see, it's time to clean out the wallpaper history.

## 1\. How to Clear the Wallpaper History via the Registry Editor

![A person using a Windows device on a desk](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/A-person-using-a-Windows-device-on-a-desk.jpg)

 The Registry Editor is a fantastic tool that allows you to configure some PC settings or troubleshoot system issues. But before you edit the Registry keys, always ensure to [back up the Registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) first. This will ensure that you have something to revert back to if something goes wrong.

 Now, let’s explore how you can clear your wallpaper history using the Registry Editor:

1. Type **Registry Editor** in the Start menu search bar.
2. Right-click on the **Best match** result and select **Run as administrator**.
3. Copy and paste the following command into the address bar:

Computer\HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Explorer\Wallpapers

 You should see the following five background history paths on the right-hand side:

* BackgroundHistoryPath0
* BackgroundHistoryPath1
* BackgroundHistoryPath2
* BackgroundHistoryPath3
* BackgroundHistoryPath4

![Clicking the BackgroundHistoryPath4 value in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/clicking-the-backgroundhistorypath4-value-in-the-registry-editor.jpg)

 In this case, **Path0** represents the first image, while **Path4** represents the fifth image in the "wallpaper history" section.

 If you’d like to remove the first image from your wallpaper history, right-click on the **BackgroundHistoryPath0** option and select **Delete**. From there, apply the same steps to delete the other images from the "wallpaper history" section.

 Want to delete all the images simultaneously? Click on the **BackgroundHistoryPath0** option, press **Shift**, and then click on **BackgroundHistoryPath4** (this will highlight all the options). From there, press the **Delete** button.

 Finally, close the Registry Editor and restart your PC to save these changes.

## 2\. Clear Wallpaper History By Using a Registry File

![A person typing commands on a laptop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/A-person-typing-commands-on-a-laptop.jpg)

 Editing Registry keys can often be a quite tedious task. If you're looking for an easy way out, then [create a Registry file](https://www.makeuseof.com/windows-registry-file-guide/).

 Wondering how this works? A Registry file allows you to edit Registry keys with just a few clicks. In fact, you won't even have to open the Registry Editor.

 Now, let’s explore how you can create a Registry file that helps you clear your wallpaper history:

1. Type **Notepad** in the Start menu search bar and select the **Best match**.
2. Next, type the following command:

Windows Registry Editor Version 5.00 [HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Explorer\Wallpapers]"BackgroundHistoryPath0"=-"BackgroundHistoryPath1"=-"BackgroundHistoryPath2"=-"BackgroundHistoryPath3"=-"BackgroundHistoryPath4"=-

![A Registry file for clearing wallpaper history](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/a-registry-file-for-clearing-wallpaper-history.jpg)

 Now, navigate to the **File** tab and select the **Save As** option. Next, select the folder in which you'd like to save the file. From there, type **ClearMyWallpaperHistory.reg** in the **File name** section

 To use the Registry file, simply double-click on it. This should automatically clear your wallpaper history.

## 3\. Overwrite the Previous Wallpaper History

 Struggling to clear your wallpaper history? Overwriting the Windows wallpaper history could help. To do that, you'd have to use five new different pictures—one at a time—as your background.

 In this case, this will only show your most recently used pictures. That way, you can indirectly "clear" any sensitive images from the wallpaper history and only display what you're comfortable with.

 Here’s how to overwrite your wallpaper history:

1. Press **Win + I** to open the system settings. Alternatively, check out [the different ways to access the Windows system settings](https://www.makeuseof.com/windows-ways-to-open-system-settings/).
2. Click the **Personalization** option.
3. Click the **Background** drop-down menu and select **Picture**.
4. Scroll down and click the **Browse** button. Finally, select a new image.

![Clicking the Browse button in the Background settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/clicking-the-browse-button-in-the-background-settings.jpg)

 Repeat this process five times. From there, you should start seeing different images in the "wallpaper history" section.

## Your Previous Wallpapers Are Nowhere to Be Found

 Windows allows you to personalize your device to your liking. But then the system often keeps track of the changes you make on your PC. Fortunately, you can easily prevent others from seeing the changes you make on your device. For example, you can remove your wallpaper history using any of the methods we’ve covered.


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
<li><a href="https://windows11.techidaily.com/directing-system-thermal-output-with-customization/"><u>Directing System Thermal Output with Customization</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-2024-approved-prime-pc-idle-gaming-selections/"><u>[New] 2024 Approved  Prime PC Idle Gaming Selections</u></a></li>
<li><a href="https://windows11.techidaily.com/create-your-own-windows-speech-recognition-app-with-autohotkey-and-whisper/"><u>Create Your Own Window's Speech Recognition App with AutoHotkey and Whisper</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-the-file-damage-enigma-winning-over-error-0x80070570-on-windows-11/"><u>Deciphering the File Damage Enigma - Winning Over Error 0X80070570 on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/delving-into-what-windows-11s-new-updates-signify-for-users/"><u>Delving Into What Windows 11'S New Updates Signify For Users</u></a></li>
<li><a href="https://windows11.techidaily.com/customizing-graphics-output-dpi-adjustment-guide/"><u>Customizing Graphics Output: DPI Adjustment Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/clearing-the-past-updating-decrepit-windows-cards/"><u>Clearing the Past: Updating Decrepit Windows Cards</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/updated-make-your-instagram-feed-pop-with-stop-motion-animation/"><u>Updated Make Your Instagram Feed Pop with Stop Motion Animation</u></a></li>
<li><a href="https://windows11.techidaily.com/defensive-operations-mastering-windows-unauthorized-prevention/"><u>Defensive Operations: Mastering Windows Unauthorized Prevention</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/why-does-the-pokemon-go-battle-league-not-available-on-honor-90-pro-drfone-by-drfone-virtual-android/"><u>Why does the pokemon go battle league not available On Honor 90 Pro | Dr.fone</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/new-2024-approved-free-animation-software-roundup-windows-and-mac-compatible/"><u>New 2024 Approved Free Animation Software Roundup Windows and Mac Compatible</u></a></li>
<li><a href="https://windows11.techidaily.com/clearing-up-the-blocked-app-notification-issue/"><u>Clearing Up the Blocked App Notification Issue</u></a></li>
<li><a href="https://windows11.techidaily.com/dealing-with-filehistoryfaults-in-windows-os/"><u>Dealing with FileHistoryFaults in Windows OS</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-in-2024-efficiently-transmit-via-obs-on-fb-live/"><u>[Updated] In 2024, Efficiently Transmit via OBS on FB Live</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/new-news-beats-unplugged-top-15-background-music-selections-for-2024/"><u>New News Beats Unplugged Top 15 Background Music Selections for 2024</u></a></li>
<li><a href="https://extra-resources.techidaily.com/unlock-your-pcs-potential-exciting-new-windows-10-games/"><u>Unlock Your PC’s Potential  Exciting New Windows 10 Games</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-and-rectifying-the-pink-screen-dilemma/"><u>Decoding and Rectifying the Pink Screen Dilemma</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/fantasy-villas-with-oriental-elegance-mc-edition/"><u>Fantasy Villas with Oriental Elegance, MC Edition</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/the-one-stop-shop-for-podcast-platforms-and-directories-for-2024/"><u>The One-Stop Shop for Podcast Platforms and Directories for 2024</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/2024-approved-free-meeting-tools-ranked-your-ultimate-video-call-companion/"><u>2024 Approved  Free Meeting Tools Ranked - Your Ultimate Video Call Companion</u></a></li>
<li><a href="https://windows11.techidaily.com/conquering-parsing-setback-code-0xc00ce556/"><u>Conquering Parsing Setback: Code 0xC00CE556</u></a></li>
<li><a href="https://windows11.techidaily.com/compact-guide-best-windows-forecasting-tools/"><u>Compact Guide: Best Windows Forecasting Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/conquer-words-best-writing-software-for-windows-users/"><u>Conquer Words: Best Writing Software for Windows Users</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-drives-c-vs-d-explanation/"><u>Deciphering Drives: C: Vs D: Explanation</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/1716465373192-closing-with-panache-free-youtubes-1-six/"><u>Closing with Panache  Free YouTube's #1 Six!</u></a></li>
<li><a href="https://audio-editing.techidaily.com/auditory-landmarks-pinpointing-button-induced-sounds-in-software-for-2024/"><u>Auditory Landmarks Pinpointing Button-Induced Sounds in Software for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/command-line-conjuring-windows-new-feature/"><u>Command Line Conjuring: Windows' New Feature</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-boosting-video-success-tips-from-top-50plus-quotes-on-tiktok/"><u>[New] Boosting Video Success  Tips From Top 50+ Quotes on TikTok</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/updated-in-2024-how-to-convert-a-gif-to-a-video-for-instagram/"><u>Updated In 2024, How to Convert a GIF to a Video for Instagram</u></a></li>
<li><a href="https://windows11.techidaily.com/demystifying-the-advantages-of-microsofts-copilot-key-for-windows-11/"><u>Demystifying the Advantages of Microsoft's Copilot Key for Windows 11</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/how-to-bypass-frp-on-infinix-note-30-vip-by-drfone-android/"><u>How to Bypass FRP on Infinix Note 30 VIP?</u></a></li>
<li><a href="https://windows11.techidaily.com/digital-dilemma-deciphered-7-strategies-to-reopen-browsers-in-win-os/"><u>Digital Dilemma Deciphered: 7 Strategies to Reopen Browsers in WIN OS</u></a></li>
<li><a href="https://windows11.techidaily.com/combining-audioscapes-and-visuals-snipping-tool-guide-max-156/"><u>Combining Audioscapes & Visuals: Snipping Tool Guide (Max 156)</u></a></li>
<li><a href="https://windows11.techidaily.com/conquering-idle-computing-with-auto-sleep-in-w10w11/"><u>Conquering Idle Computing with Auto Sleep in W10/W11</u></a></li>
<li><a href="https://windows11.techidaily.com/crafting-an-efficient-menu-choice-for-regular-system-checks-on-win11plus11/"><u>Crafting an Efficient Menu Choice for Regular System Checks on Win11+11</u></a></li>
<li><a href="https://windows11.techidaily.com/diagnosing-partially-functioning-windows-earphones/"><u>Diagnosing Partially Functioning Windows Earphones</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-microsofts-window-file-format-cab-for-ease-of-use/"><u>Deciphering Microsoft's Window File Format (CAB) for Ease of Use</u></a></li>
<li><a href="https://windows11.techidaily.com/dazzling-holiday-windows-a-celebration-of-joy-and-light/"><u>Dazzling Holiday Windows: A Celebration of Joy & Light</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/mastering-ppt-presentation-in-google-meet-mobile-and-laptop-for-2024/"><u>Mastering PPT Presentation in Google Meet (Mobile & Laptop) for 2024</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-2024-approved-tiktok-shadowban-how-to-get-unshadowbanned-on-tiktok/"><u>[New] 2024 Approved  TikTok Shadowban  How to Get Unshadowbanned on Tiktok</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-track-realme-gt-3-location-by-number-drfone-by-drfone-virtual-android/"><u>In 2024, How to Track Realme GT 3 Location by Number | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/command-your-way-through-windows-11-nircmd-tips-and-tricks/"><u>Command Your Way Through Windows 11: NirCmd Tips & Tricks</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-unlock-samsung-phone-password-without-factory-reset-by-drfone-android/"><u>In 2024, How to Unlock Samsung Phone Password Without Factory Reset?</u></a></li>
</ul></div>
