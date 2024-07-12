---
title: "Boost Text Entry: Learning From TypingAid"
date: 2024-07-11T21:21:03.894Z
updated: 2024-07-12T21:21:03.894Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Boost Text Entry: Learning From TypingAid"
excerpt: "This Article Describes Boost Text Entry: Learning From TypingAid"
keywords: Boost Typing,Quick Input,Efficient Entry,Enhanced Keyboard,Speedy Typing,Accurate Text,Faster Data Entry
thumbnail: https://thmb.techidaily.com/964056d5a42fd554adb9e457ea6c862e5065495ad6b360af575e17501ef981e0.png
---

## Boost Text Entry: Learning From TypingAid

 Are you looking for ways to type faster? TypingAid is a clever and nearly fully automated AutoHotkey script that provides word suggestions as you type.

 Typing "Nebuchadnezzar" with TypingAid may only take four or five keystrokes - and, as a bonus, will be typo-free. Here's how you can use TypingAid as your typing assistant.

## What Is TypingAid for Windows?

 You can [use AutoHotkey to make app-specific hotkeys](https://www.makeuseof.com/autohotkey-app-specific-hotkeys/) that change what the same key combinations "do" depending on the active app. But it's also possible to tap its GUI functionality to, for example,[make your own quick note-taking app with AutoHotkey](https://www.makeuseof.com/windows-autohotkey-note-taking-app/) .

 Out of anything you can do with it, there's one project not worth pursuing: using AutoHotKey to "map" misspelled words to their correct versions. Why spend the time on such an endeavor when there's TypingAid?

 TypingAid is an AutoHotKey script that compares what you're typing to a database of words and suggests matches. This way, not only can you eliminate typos, but also type much faster.

 Like the "predictive text" feature on phones, TypingAid lets you half-type words and choose their "complete versions" from a pop-up menu.

 We should note that we've already covered the usefulness of predictive text solutions in our article on [various hacks to help you type faster](https://www.makeuseof.com/hacks-to-type-faster/) , so, make sure to check that out, too.

 What's best is that TypingAid "learns" new words and adds them to its database after you type them X times (the number is configurable). Thus, the more you use it, the better it becomes at recommending terms you use based on your vocabulary and writing style.

## How to Download & Install TypingAid

 Download the script/app from [TypingAid's official Github page](https://github.com/ManiacDC/TypingAid) . By default, it comes in a compressed archive. Extract it in any folder you like, and run the executable among the rest of the files to use TypingAid.

![TypingAid GitHub Page](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/typingaid-github-page.jpg)

 Note that TypingAid is also available in its original AutoHotkey script format. If you download this version, you'll also need to have AutoHotkey installed to use it. You'll find that at [AutoHotkey's official site](https://www.AutoHotkey.com/) .

![AutoHotkey Official Site](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/autohotkey-official-site.jpg)

 With AutoHotkey installed, extract the archive with the AHK version of TypingAid. In this case, instead of an executable, the file from which you can launch the app is**TypingAid.ahk** .

![TypingAid Exe and AHK Versions](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/typingaid-exe-and-ahk-versions.jpg)

 You can empower TypingAid to offer suggestions from the get-go instead of waiting for it to populate its database from scratch with the words you're writing. For that, though, you'll need a wordlist.

 Wordlists are what enables most predictive text solutions to recognize words and phrases and offer suggestions on how to proceed. As their name states, they're just lists of words, usually stored in a typical text file—one per line or separated by commas.

 You can make a wordlist from scratch with your favorite text-editing app, like Notepad. TypingAid automates this process, adding any words you type over X times to its wordlist.

 Still, it's best to use an existing wordlist with popular terms to jump-start TypingAid.

 You can find many wordlists on [TypingAid's GitHub page](https://github.com/ManiacDC/TypingAid) . Choose the one you prefer, and save it into the same folder where you've extracted TypingAid's main script/app. Rename the file to**Wordlist.txt** for TypingAid to recognize it and import its contents.

Then, run TypingAid.

## How to Configure TypingAid

 TypingAid will be idle in the Windows tray after you run it and spring to life once you begin typing in any window. However, it's best to spend a few minutes setting it up to your preferences before you start using it. Right-click on its Windows tray icon and select**Settings** .

![TypingAid Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/typingaid-settings.jpg)

Let's see the essential settings worth tweaking in TypingAid.

### 1\. General Settings

 On the**General Settings** page, you can tweak TypingAid's "behavior".

![TypingAid Settings General](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/typingaid-settings-general.jpg)

* If you turn**Learn new words as you type** to off, TypingAid will only offer suggestions that already exist in the loaded Wordlist. Leave the option turned on to have TypingAid learn new words that you type.
* **Minimum length of word to learn** restricts which new words TypingAid can "learn", based on their number of characters. If you leave it at the predefined value of**5** , it won't, for example, "learn" the word "fuse", no matter how many times you type it. It will only "learn" words with at least five letters.
* **Add to wordlist after X times** defines how many times you must type the same unknown word for TypingAid to add it to its Wordlist.
* Look at the checkboxes under**Auto Complete Keys** and enable the ones you want to use for choosing one of TypingAid's suggestions. This writer likes using the**Tab** ,**Number Keys** ,**Enter** , and**Single Click** .
* If TypingAid can't "send" text to some apps, change the**Send Method** with which it "pushes" text to the active window.
* By changing**Type space after autocomplete** to On, TypingAid will also add a "space" character after any word it sends to an app so that you can immediately start typing the next one.

### 2\. Wordlist Box

 The options on the**Wordlist Box** page affect how TypingAid presents its suggestions.

![TypingAid Settings Wordlist Box](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/typingaid-settings-wordlist-box.jpg)

* Change the number under**Maximum number of results** to show to the number of suggestions you'd like to see.
* **Show wordlist after X characters** defines how many characters you'll have to type for TypingAid to start showing suggestions.
* It's best if you leave**Show learned words first** to On, as it will ensure the words TypingAid learned from you will appear before the words that already existed in its generic Wordlist.
* The rest of the options affect the appearance of the suggestion box that pops up as you're typing. You can tweak them to change where the box appears (**List appears X pixels below cursor**), its font, its opacity, and so on. You can leave them as they are since their effects are primarily aesthetic.

### 3\. Programs

 The**Programs** page lets you choose the apps and windows where TypingAid will be active.

![TypingAid Settings Programs](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/typingaid-settings-programs.jpg)

 There are separate fields for defining where TypingAid will be either enabled or disabled.

![TypingAid Settings Programs Selecting an App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/typingaid-settings-programs-selecting-an-app.jpg)

 It's easy to include or exclude any app or window by clicking on**Edit** next to the appropriate enabled or disabled field, and selecting one of the active windows from the pull-down menu, or typing its name yourself.

### 4\. Advanced

 We suggest you skip this section, except for the rare case where you want to customize TypingAid's**Terminating Characters** . If that term sounds alien, that's precisely why most people won't have to tweak anything here!

![TypingAid Settings Advanced](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/typingaid-settings-advanced.jpg)

 In other words, if you need the options here, you'll also know how to tweak them. If not, leave them as they are.

## Putting TypingAid Into Action

 With everything set up, you can immediately start using TypingAid to boost your typing speed in any app.

 Try entering some text in Notepad, Microsoft Word, your favorite browser, etc. After two or three characters (depending on how you've configured TypingAid), you'll see TypingAid's suggestions box pop up next to your cursor.

![TypingAid Active in Word](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/typingaid-active-in-word.jpg)

 You can press one of the**Auto Complete Keys** (like Tab or Enter) to choose the pre-selected word and have it replace the characters you've typed, just like your smartphone's autocomplete.

 Or, if you're also using the**Number (Auto Complete) Keys** , press a number from the top row of your keyboard to directly select that word from TypingAid's suggestion list without having to click on it with your mouse.

## TypingAid: The Mind-Reading Typing Assistant for Windows

 A predictive text solution like TypingAid can dramatically reduce the time spent typing. It can help you create or edit documents faster and with fewer errors.

 Additionally, by learning the words you use the most and taking notes on their frequency, TypingAid can adapt to your writing style as you use it. The more you use it, the more intuitive and personalized its suggestions will become.

 What's not to like about this free way to write faster, better, and more effortlessly?

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
<li><a href="https://windows11.techidaily.com/addressing-frozen-overlays-restoring-function-to-discord-ui/"><u>Addressing Frozen Overlays: Restoring Function to Discord UI</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-windows-11-secrets-with-devhome-insights/"><u>Unlocking Windows 11 Secrets with DevHome Insights</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-streamline-your-content-twitter-video-integration-for-2024/"><u>[New] Streamline Your Content  Twitter Video Integration for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/uniting-gmail-and-outlook-windows-setup-walkthrough/"><u>Uniting Gmail and Outlook: Windows Setup Walkthrough</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-update-halted-quick-solutions-for-a-perfect-installation/"><u>Windows Update Halted: Quick Solutions for a Perfect Installation</u></a></li>
<li><a href="https://review-topics.techidaily.com/identify-malfunctioning-your-hardware-drivers-with-windows-device-manager-in-windows-11107-by-drivereasy-guide/"><u>Identify malfunctioning your hardware drivers with Windows Device Manager in Windows 11/10/7</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-remove-a-previously-synced-google-account-from-your-samsung-galaxy-a05-by-drfone-android/"><u>In 2024, How to Remove a Previously Synced Google Account from Your Samsung Galaxy A05</u></a></li>
<li><a href="https://windows11.techidaily.com/a-guide-to-understanding-windows-program-files-format/"><u>A Guide to Understanding Windows' Program Files Format</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/new-2024-approved-dailymotion-video-converter-fast-free-and-easy-online/"><u>New 2024 Approved Dailymotion Video Converter - Fast, Free, and Easy Online</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-in-2024-unleash-the-power-of-your-mi-11s-screen-recording-features/"><u>[New] In 2024, Unleash the Power of Your Mi 11'S Screen Recording Features</u></a></li>
<li><a href="https://windows11.techidaily.com/augmented-folder-actions-power-up-your-file-management/"><u>Augmented Folder Actions: Power Up Your File Management</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-password-creation-companion-for-windows-users/"><u>The Ultimate Password Creation Companion for Windows Users</u></a></li>
<li><a href="https://windows11.techidaily.com/turning-on-hyper-v-simplified-your-win11-how-to/"><u>Turning On Hyper-V Simplified - Your Win11 How-To</u></a></li>
<li><a href="https://windows11.techidaily.com/1719377597268-legacy-software-understanding/"><u>Legacy Software Understanding:</u></a></li>
<li><a href="https://windows11.techidaily.com/streamline-creative-processes-with-these-8-windows-best-apps/"><u>Streamline Creative Processes With These 8 Window's Best Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-for-correcting-incompatible-software-with-windows-operations/"><u>Strategies for Correcting Incompatible Software with Windows Operations</u></a></li>
<li><a href="https://windows11.techidaily.com/shaping-windows-11-square-it-off/"><u>Shaping Windows 11: Square It Off</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/speed-up-your-system-with-latest-nvidia-driver/"><u>Speed Up Your System with Latest Nvidia Driver</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/ed-in-2024-free-youtube-earning-predictors/"><u>[Updated] In 2024, Free YouTube Earning Predictors</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-manual-reverting-windows-to-a-previous-state/"><u>Step-by-Step Manual: Reverting Windows to a Previous State</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-for-addressing-undetectable-disks/"><u>Strategies for Addressing Undetectable Disks</u></a></li>
<li><a href="https://windows11.techidaily.com/ultimate-bundle-premier-cost-free-windows-11-assistants/"><u>Ultimate Bundle: Premier Cost-Free Windows 11 Assistants</u></a></li>
<li><a href="https://windows11.techidaily.com/baffling-backup-concealed-control-center-settings/"><u>Baffling Backup: Concealed Control Center Settings</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/2024-approved-elite-mac-gif-recorders-top-picks-list/"><u>2024 Approved  Elite Mac GIF Recorders  Top Picks List</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-in-2024-capture-the-essence-your-free-screen-recording-solution-on-mac-and-pc/"><u>[Updated] In 2024, Capture the Essence - Your FREE Screen Recording Solution on Mac & PC</u></a></li>
<li><a href="https://windows11.techidaily.com/win11-desktop-from-chaotic-to-customized-in-minutes/"><u>Win11 Desktop: From Chaotic to Customized, in Minutes</u></a></li>
<li><a href="https://windows11.techidaily.com/tips-for-reducing-browsing-impact-on-system-performance/"><u>Tips for Reducing Browsing Impact on System Performance</u></a></li>
<li><a href="https://windows11.techidaily.com/the-uncharted-territory-windows-11-and-the-future-of-ai/"><u>The Uncharted Territory: Windows 11 and the Future of AI</u></a></li>
<li><a href="https://windows11.techidaily.com/win11-caption-troubleshooting-made-simple/"><u>Win11 Caption Troubleshooting Made Simple</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/bringing-youtube-home-to-your-instagram-story-for-2024/"><u>Bringing YouTube Home to Your Instagram Story for 2024</u></a></li>
<li><a href="https://facebook.techidaily.com/take-control-prevent-facebooks-oversee-usage/"><u>Take Control: Prevent Facebook’s Oversee Usage</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/top-3-sites-to-find-free-motorola-unlock-codes-to-unlock-your-motorola-phone-by-drfone-android/"><u>Top 3 Sites to Find Free Motorola Unlock Codes to Unlock Your Motorola Phone</u></a></li>
<li><a href="https://windows11.techidaily.com/are-file-thumbnails-not-showing-up-in-windows-11-heres-how-to-fix-it/"><u>Are File Thumbnails Not Showing Up in Windows 11? Here's How to Fix It</u></a></li>
<li><a href="https://windows11.techidaily.com/a-beginners-guide-to-managing-windows-11-wins/"><u>A Beginner's Guide to Managing Windows 11 Wins</u></a></li>
<li><a href="https://windows11.techidaily.com/boost-command-line-capabilities-in-latest-windows-releases/"><u>Boost Command-Line Capabilities in Latest Windows Releases</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-pioneering-portable-vrs-google-cardboard-versus-samsungs-tech/"><u>In 2024, Pioneering Portable VRs  Google Cardboard Versus Samsung's Tech</u></a></li>
</ul></div>
