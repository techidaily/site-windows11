---
title: "Gateway to Gaming Glory: Using DOSBox-X for PC Classics"
date: 2024-10-20T19:31:24.205Z
updated: 2024-10-24T16:24:22.116Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Gateway to Gaming Glory: Using DOSBox-X for PC Classics"
excerpt: "This Article Describes Gateway to Gaming Glory: Using DOSBox-X for PC Classics"
keywords: Gateway Classic Games,Gaming Retro Fun,Old PC Games,Classic Gaming Box,DOSBox-PC Games,Xbox Emulator,Virtual Gameplay Past
thumbnail: https://thmb.techidaily.com/9530a6a7ae2d76ba480cbada332a623fd47509bd2903fa4cfebcaa0c3ca3de95.jpg
---

## Gateway to Gaming Glory: Using DOSBox-X for PC Classics

 If there's one thing abundant today, that's digital entertainment. You can purchase thousands of titles at most popular digital storefronts and find even more completely free. What's the point of being stuck in the past?

 Still, many older games are worth your time, for they're not "relics" but "classics". Titles like Syndicate and the original X-Com look and sound crude compared to today's games. Still, their addictive gameplay can give a lesson even to most modern triple-A titles. And the only way to play them is with software like DOSBox-X.

## What Is DOSBox-X?

 DOSBox-X is a fork of the popular DOSBox app that enables a modern PC to run software made for older PCs. As its name states, it's primarily designed for Microsoft's ancient Disk Operating System, or DOS for short.

 Unlike the "vanilla" DOSBox, DOSBox-X comes with baked-in emulation for hardware like 3dfx's Voodoo 3D accelerators and various popular audio cards. Thanks to this, you can even install older versions of Windows inside its virtual environment.

 For this article, though, we'll stick to classic DOS games.

## How to Download and Install DOSBox-X

 DOSBox-X is free and available on Windows, Macs, and Linux. In this guide, we'll be using its Windows version.

 Although we'll be using DOSBox-X's Windows 7+ version, the other ones work similarly (more or less). So, you can follow along even if you're on a different OS. Still, expect some variations on DOSBox-X's installation and how you'll manage folders, paths, and "ROMs" (AKA: games).

 Start by downloading the app from [DOSBox-X's official site](https://dosbox-x.com/), then install it or extract it to a folder.

![DOSBox-X executable in folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/dosbox-x-executable-in-folder.jpg)

 Depending on the version you've downloaded, and if you installed or extracted it, you'll either find a shortcut to the DOSBox-X app in the **Windows Start menu**/your **Desktop**, or you'll have to visit its folder with your favorite file manager and double-click **dosbox-x.exe** to launch it.

 Keep that in mind, but don't launch the app yet - we first have to do some folder juggling.

## Setting Up Your Storage for DOSBox-X

 Unlike other emulators, DOSBox and its fork we're using, DOSBox-X, emulate a "proper" DOS environment, so you can't simply "load ROMs" into it. Thus, you'll have to allocate some storage to it.

 This is easier than it sounds, for it's as simple as creating two folders.

* The first will be DOSBox-X's "working directory" (think of it as the equivalent of "your current Windows installation").
* The second one will be your primary emulated storage, where you'll place all the classic software you want to access from within DOSBox-X.

 For convenience's sake, we suggest you create a folder with a name like "DOS" or "DOSgames" inside the directory where you keep ROMs for other emulators or the disk/partition/folder where you install your modern games.

![DOS ROMs Folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/dos-roms-folder.jpg)

 Click in your file manager's "path" field/bar, and **copy the full path** to the folder you created to the Clipboard. Now's the time to **run DOSBox-X**, and the first thing you'll see won't be the app but a requester for the folder it should use. "Tell it" (paste with **CTRL** \+ **V**) to use the folder you created in the previous step.

![DOSBox-X Working Directory](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/dosbox-x-working-directory.jpg)

 Return to your file manager and create another folder inside the previous one. We'll configure DOSBox-X to "see" this folder as its primary storage.

 You can give it a name like **C** since, in Microsoft's OSes, that was, is, and probably will remain the letter usually mapped to a PC's "system drive". However, we believe it's better to name it something like **DriveC**, since it will make more sense if you forget about its existence and happen to run into it in the future.

![DOSBox-X Creating DriveC Folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/dosbox-x-creating-drivec-folder.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135370/19272" target="_top" id="2135370">
  <img src="//a.impactradius-go.com/display-ad/19272-2135370" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135370/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Don't close your file manager yet; now is a good time to "prepare" your games. If you have them in compressed archives, extract your games into individual folders within the **C**/**DriveC** folder.

![DOSBox-X DriveC Game Folders](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/dosbox-x-drivec-game-folders.jpg)

 With almost all file-related tasks behind us, it's time to configure DOSBox-X for some retro gaming.

## How to Configure DOSBox-X for the Best Experience

 DOSBox-X has lots of settings to tweak, so let's get it set up.

### 1\. Setting Up the Directory

 Turn your attention to DOSBox-X's window. Choose its **Configuration tool** from the **Main** menu entry (or press **F11** \+ **C** on your keyboard).

![DOSBox-X Configuration Editor Menu Entry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/dosbox-x-configuration-editor-menu-entry.jpg)

 Instead of manually mounting the folder you created every time you run DOSBox-X, let's have it always available automatically. For that, we'll have to do some classic AutoExec.BAT editing. Thus, choose the last option in the **Configuration Tool**'s panel, **AUTOEXEC.BAT**.

![DOSBox-X Configuration Tool AutoExec BAT](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/dosbox-x-configuration-tool-autoexec-bat.jpg)

 You'll see the currently empty DOSBox-X's **AutoExec**.

 Type **mount** in the first line, press **space** once, and then type **c**, which will be the letter of your primary drive inside DOSBox-X's virtual environment. Press **space** again, and **type the full path** to the folder you've created for use as your virtual C drive.

 If you've copied its path to the **Clipboard** from your file manager, you'll find that you can't paste it, as usual, using the **CTRL** \+ **V** keyboard combination. Instead, use the **Paste Clipboard** button.

![DOSBox-X Configuration Tool Editing AutoExec](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/dosbox-x-configuration-tool-editing-autoexec.jpg)

 Press **Enter** and type **c:** in the line underneath. That's how you "change the active drive" inside a DOS environment.

 By including this command in DOSBox-X's **AutoExec**, its virtual environment will "change" the active drive to the storage folder you've mounted in the line directly above. If you don't do that, DOSBox-X will show you its internal "Z" drive every time you launch it, and you'll have to switch to your actual storage manually.

![DOSBox-X Configuration Tool Adding Drive Letter to AutoExec](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/dosbox-x-configuration-tool-adding-drive-letter-to-autoexec.jpg)

 Click **OK** to accept the changes and return to DOSBox-X's **Configuration Tool** panel. Choose **Render** to configure the way DOSBox-X shows graphics.

![DOSBox-X Configuration Tool Render Entry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/dosbox-x-configuration-tool-render-entry.jpg)

 To learn more about all available options, click DOSBox's **Help** button.

![DOSBox-X Configuration Tool Calling For Help](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/dosbox-x-configuration-tool-calling-for-help.jpg)

 DOSBox's **Help** offers information about all its configuration options, but for now, turn your attention to those under **aspect**.

### 2\. Setting Up the Aspect Ratio

 For this guide, we'll go for **true**, which keeps the original graphics' **4:3** proportions, but scales them to fit the entire display, adding black bars on the sides of the screen. Check the aspect-related information to see if you'd prefer another approach.

 Click **Close** to exit DOSBox-X's Help file.

![DOSBox-X Configuration Tool Help Aspect Info](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/dosbox-x-configuration-tool-help-aspect-info.jpg)

<!-- affiliate ads begin -->
<span id="1977020">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1977020.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1977020">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1977020.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1977020%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1977020/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Click on the button with the **three dots** on the right of the **Aspect** line, and enable the graphics aspect you'd like to use. Then, click **OK** to accept and enable the setting.

![DOSBox-X Configuration Tool Configuring Render Aspect](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/dosbox-x-configuration-tool-configuring-render-aspect.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2006960/19272" target="_top" id="2006960">
  <img src="//a.impactradius-go.com/display-ad/19272-2006960" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2006960/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Click on **Save** to save all changes. On the new panel that shows up, choose **Use primary config file** and then click on **Save & Restart**.

![DOSBox-X Configuration Tool Choosing Config File and Restarting App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/dosbox-x-configuration-tool-choosing-config-file-and-restarting-app.jpg)

## Launching Your Retro-Favorites With DOSBox-X

 DOSBox-X is easier if you're familiar with DOS since it works precisely like a DOS-era PC. If you aren't, and interacting with your PC using commands is something new for you, it would be best to check our [beginners guide to the Windows Command Prompt](https://www.makeuseof.com/tag/a-beginners-guide-to-the-windows-command-line/).

 If that sounds like too much work for playing a handful of games, here's a quick recap of the most important commands that can get you up and running in mere minutes:

* You can see a listing of all folders on the "current level" of the storage using the command **dir**.
* You can "enter" a folder using the command **cd FolderName** (for example, **cd duke3d**).
* You can "exit" a folder and return "one level up" in your storage using the command **cd ..**.
* To find all executables in a folder, use the commands **dir \*.exe** and **dir \*.bat**.
* To launch one of those executables, **type its full filename** and press **Enter**.
* You can also use the Tab key to **auto-complete** paths and filenames. If the auto-completed one isn't what you're seeking, press **Tab** again to "cycle" through all entries matching what you've typed.

![DOSBox-X Dir Virtual C Drive](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/dosbox-x-dir-virtual-c-drive.jpg)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137216/26400" target="_top" id="2137216">
  <img src="//a.impactradius-go.com/display-ad/26400-2137216" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137216/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Let's say you want to launch the classic shareware version of id's genre-defining Doom that you already have in your storage in a folder with the game's name.

 Type **cd doom** to "enter" the game's folder.

![DOSBox-X CD Doom](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/dosbox-x-cd-doom.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1972693/19272" target="_top" id="1972693">
  <img src="//a.impactradius-go.com/display-ad/19272-1972693" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1972693/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Type **dir \*.bat** to check for any runnable batch files in the folder. You'll see two, **IAFIX.BAT** and **RUN.BAT**.

![DOSBox-X Dir Bat Doom](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/dosbox-x-dir-bat-doom.jpg)

<!-- affiliate ads begin -->
<a href="https://sentrypc.7eer.net/c/5597632/398455/3022" target="_top" id="398455">
  <img src="//a.impactradius-go.com/display-ad/3022-398455" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/398455/3022" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 As you can probably guess from its name, the second one is what you need to launch the game. So, type **run.bat** and press **Enter**.

![DOSBox-X Doom Selecting Audio System](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/dosbox-x-doom-selecting-audio-system.jpg)

<!-- affiliate ads begin -->
<a href="https://jalbum-affiliate-program.sjv.io/c/5597632/1838960/17916" target="_top" id="1838960">
  <img src="//a.impactradius-go.com/display-ad/17916-1838960" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://jalbum-affiliate-program.sjv.io/i/5597632/1838960/17916" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Like all software from that era, Doom can't auto-detect the audio system used by your (virtual) PC. DOSBox-X is configured by default to emulate a classic **SoundBlaster 16** card by Creative, so choose that entry by pressing **2**.

 Next step, enjoy blasting some demons in Doom!

![DOSBox-X Doom Running in Window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/dosbox-x-doom-running-in-window.jpg)

 If manually juggling games in DOSBox-X seems like a hassle, maybe it would be worth checking out a front-end like Launchbox. We saw in the past how you can [import MS-DOS games into Launchbox](https://www.makeuseof.com/how-to-import-ms-dos-games-launchbox/), and after the front-end's initial setup, playing a game will be as easy as selecting it from its menu.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137201/26400" target="_top" id="2137201">
  <img src="//a.impactradius-go.com/display-ad/26400-2137201" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137201/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## DOS in a Box

 Thanks to DOSBox-X, you can have the best DOS-era computers had to offer on a window on your desktop and a collection of hundreds of the best games in a folder that will take less than 1% of your actual PC's total storage.

 Despite your PC being officially incompatible with such old software, with DOSBox-X, enjoying your retro-favorites in all their pixelated glory will be only one or two commands away!

 Still, many older games are worth your time, for they're not "relics" but "classics". Titles like Syndicate and the original X-Com look and sound crude compared to today's games. Still, their addictive gameplay can give a lesson even to most modern triple-A titles. And the only way to play them is with software like DOSBox-X.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://digital-screen-recording.techidaily.com/new-in-2024-getting-started-with-iphone-speech-recordings/"><u>[New] In 2024, Getting Started with iPhone Speech Recordings</u></a></li>
<li><a href="https://article-files.techidaily.com/updated-in-2024-comprehensive-srt-format-conversion-guide/"><u>[Updated] In 2024, Comprehensive SRT Format Conversion Guide</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-popularitys-palette-ig-story-filter-guide/"><u>[Updated] Popularity's Palette IG Story Filter Guide</u></a></li>
<li><a href="https://fox-direct.techidaily.com/2024-approved-scalable-skills-for-versatile-gif-production-techniques/"><u>2024 Approved Scalable Skills for Versatile GIF Production Techniques</u></a></li>
<li><a href="https://windows11.techidaily.com/identifying-ip-and-mac-via-windows-powershell/"><u>Identifying IP & MAC via Windows PowerShell</u></a></li>
<li><a href="https://fox-links.techidaily.com/immersive-storytelling-harnessing-top-10-text-innovations-in-videos/"><u>Immersive Storytelling Harnessing Top 10 Text Innovations in Videos</u></a></li>
<li><a href="https://fox-info.techidaily.com/in-2024-the-serenity-of-silence-premier-asmr-talents/"><u>In 2024, The Serenity of Silence Premier ASMR Talents</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlining-your-experience-fixes-for-common-rainmeter-issues/"><u>Streamlining Your Experience: Fixes for Common Rainmeter Issues</u></a></li>
<li><a href="https://windows11.techidaily.com/understanding-ftdibussys-impact-on-windows-memory-reliability/"><u>Understanding ftdibus.sys: Impact on Windows Memory Reliability</u></a></li>
<li><a href="https://screen-capture.techidaily.com/unleash-your-inner-tech-wizard-xbox-one-snapshot-secrets-revealed/"><u>Unleash Your Inner Tech Wizard Xbox One Snapshot Secrets Revealed</u></a></li>
<li><a href="https://windows11.techidaily.com/windows-esd-mastery-achieving-conversion-to-iso-format/"><u>Windows ESD Mastery: Achieving Conversion to ISO Format</u></a></li>
</ul></div>

