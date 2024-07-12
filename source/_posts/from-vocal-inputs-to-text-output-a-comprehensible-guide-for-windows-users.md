---
title: "From Vocal Inputs to Text Output: A Comprehensible Guide for Windows Users"
date: 2024-07-11T22:03:36.889Z
updated: 2024-07-12T22:03:36.889Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes From Vocal Inputs to Text Output: A Comprehensible Guide for Windows Users"
excerpt: "This Article Describes From Vocal Inputs to Text Output: A Comprehensible Guide for Windows Users"
keywords: Windows Voice-to-Text,Text Conversion Tips,Easy Text Output Windows,Voice Inputs to Text Guide,Windows Speech To Text,Text Synthesis for Windows,Simplified Windows Text Guide
thumbnail: https://thmb.techidaily.com/f75585e4daf78953dd0ce1cfd0b26209fab1e9c588003fe7de564148a8e3e23c.jpg
---

## From Vocal Inputs to Text Output: A Comprehensible Guide for Windows Users

 OpenAI's Whisper is a new AI-powered solution that can turn your voice into text. Best of all, it comes at zero cost.

 However, there's a catch: it's more challenging to install and use than your average Windows utility. Especially if you want to use your Nvidia GPU's Tensor Cores to give it a nice boost.

 Don't fret, though. That's why we're here! Read on to find out how to install and use it, but also, if you own one, to have Whisper take advantage of your Nvidia GPU.

## What Is OpenAI's Whisper?

 ChatGPT is all the rage nowadays, and we already saw [how you can use ChatGPT by OpenAI](https://www.makeuseof.com/how-to-use-chatgpt-by-openai/) . And yet, it's not the only interesting project by OpenAI.

 Powered by deep learning and neural networks, Whisper is a natural language processing system that can "understand" speech and transcribe it into text. But it's also its own thing, sitting at a spot right among all similar solutions:

* Whisper is an AI solution "trained" on natural language. So, it's better at understanding "normal" human speech than older solutions.
* Whisper doesn't come with an interface, nor can it record audio. It can only take existing audio files and output text files.
* Since it's good at "making sense of language", Whisper also has the superpower of automatic translation in a single step.
* Whisper is not an online service and can work entirely offline.
* If you have a relatively modern Nvidia GPU (GTX970 or newer), Whisper can run in "hardware accelerated mode" to boost its speed.
* There's no requirement to register, purchase a license, or buy a subscription.

## Why Are AMD GPUs Not Supported?

 For GPUs to be useful for more than graphics, they'd have to act as fully programmable processors. That's why Nvidia created CUDA, officially deemed "a parallel computing platform and programming model". To learn more about CUDA and related hardware ("CUDA cores"), read our article on [what are CUDA cores and how they improve PC gaming](https://www.makeuseof.com/tag/what-are-cuda-cores-pc-gaming/) .

 CUDA is proprietary Nvidia technology, only compatible with Nvidia GPUs. The closest alternatives for AMD's hardware are OpenCL and Radeon Compute Platform. To learn more about how each company's solutions compare, check our article on [AMD Compute Units vs. Nvidia CUDA Cores](https://www.makeuseof.com/compute-units-vs-cuda-cores-whats-the-difference/) .

 Compared to the alternatives, CUDA is considered more mature, performant, and easier to use. Thus, most developers only target CUDA, which, in turn, means that their software only takes advantage of the hardware features on Nvidia GPUs. And that includes Whisper.

## How to Download and Install Whisper

 Unfortunately, Whisper is not a standalone app you can download, install, and run. It relies on other software, which must also be installed.

 For Windows, to keep this guide simple, we'll use Chocolatey extensively for installing most of the necessary software parts. Check our guide on [the quickest way to install Windows software](https://www.makeuseof.com/tag/quickest-way-install-windows-software-command-prompt/) for more info on Chocolatey.

 For Linux and Macs, the installation process (excluding the Windows path variable, and easy-to-use batch files we'll create) should be similar.

1. To install and use Whisper, you must have**Python** and its**PIP** tool installed and added to the Windows "Path" variable. For info on that, check our article on [how to install Python PIP on Windows, Mac, and Linux](https://www.makeuseof.com/tag/install-pip-for-python/) .
2. Install**FFMPEG** through Chocolatey with this command:  
`choco install ffmpeg`  
 Also, install its Python version with:  
`pip3 install python-ffmpeg`  
![pip install python ffmpeg](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/pip-install-python-ffmpeg.jpg)
3. Finally, install Whisper from its Github page with:  
`pip3 install git+https://github.com/openai/whisper.git`

## Getting Whisper's CUDA-Enabled Version

 Although Whisper doesn't use Nvidia GPUs, the**torch** package it relies on offers a CUDA-accelerated version. Using this instead of the "plain" version can help Whisper complete its transcriptions much faster with the help of your Nvidia GPU.

To have Whisper use the CUDA cores of your Nvidia GPU:

1. If you already have the "vanilla" version of torch installed, uninstall and purge remnants of it with:  
`pip3 uninstall torch`  
 Once it's done, follow it up with:  
`pip cache purge`
2. Install torch's CUDA-enabled version with:  
`pip3 install torch torchvision torchaudio --extra-index-url https://download.pytorch.org/whl/cu117`  
![pip3 install torch torchvision torchaudio](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/pip3-install-torch-torchvision-torchaudio.jpg)
3. To check if Whisper can use your Nvidia GPU, use:  
`whisper --help | findstr -i pytorch`  
 You should see**(default: cuda)** instead of**(default: cpu)** .

## What to Do if Torch Fails to Install

 If you encounter the "no version found" errorwhile installing torch, you may need to install an older version of Python parallel to your current one.

Use this command to do that:

`choco install python --version OLDER_VERSION --side-by-side`

Replace "OLDER\_VERSION" with a version, like 3.10.

![choco install python alternate version](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/choco-install-python-alternate-version.jpg)

 Then, use the path of the secondary version for all "generic" Whisper commands (e.g., "c:\\Python310\\Scripts\\pip.exe" rather than just "pip").

## How to Record Your Voice

 You can use any sound-recording app to turn your voice into a WAV or MP3 file. Windows includes such an app—for more info on that, see [how to use the Windows 10 Voice Recorder app](https://www.makeuseof.com/how-to-use-the-windows-10-voice-recorder-app/) .

 For a more full-featured option, try**Audacity** . Learn how to do it with our guide on [how to use Audacity to record audio on Windows and Mac](https://www.makeuseof.com/how-to-use-audacity-to-record-audio/) .

![Recording voice with Audacity](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/recording-voice-with-audacity.jpg)

## How to Start Transcribing With Whisper

 Although Whisper doesn't come with a user-friendly GUI, its use is ultra-simple.

 Let's say we have the file**LatestNote.mp3** which contains speech in Greek, in folder**c:\\MyAudioFiles** , and want to translate it to English and transcribe it into a text file.

1. We begin by running**Command Prompt** or**PowerShell** .
2. We "change directory" where the audio file is stored with this command:  
`cd C:\MyAudioFiles`
3. We unleash Whisper on the file with:  
`whisper --model base --language gr --task translate LatestNote.mp3`  
![Whisper translate gr](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/whisper-translate-gr.jpg)

 Once processed, the text file (named "LatestNote.mp3.txt") will appear in the same folder. Open it in a text editor like**Notepad** to view the translated text.

 We used a translation example because English transcription is even more straightforward: you only have to "lose" the "--language" and "-task" flags. Thus, for plain transcription, the above command would be:

`whisper --model base LatestNote.mp3`

 The "model" flag is required because Whisper uses one out of various options. Let's expand on them to help you choose the best for your needs.

### Which Model to Choose?

 Whisper offers various language models. The larger the model, the more improved its accuracy, but also the higher its hardware requirements. They are:

1. Tiny.
2. Base.
3. Small.
4. Medium.
5. Large.

 Most native English speakers should be fine with the**tiny** or**base** models. Non-native English speakers may see better results with larger models, like**small** and**medium** .

 Note, though, that the medium and large models require over 8GBs of VRAM (that is, "your GPU's memory").

![whisper model small](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/whisper-model-small.jpg)

 To select one of them, specify the model after the "--model" switch in the command:

`whisper --model tiny/small/medium/large [file]`

For example:

`whisper --model small My_Voice_Note.mp3`

## How to Streamline Your Transcription

 Having to type the whole Whisper command every time you want to transcribe some audio can quickly get boring. Let's make a globally accessible batch file to streamline the process.

1. Run**Windows Explorer** and visit your C: drive.
2. Create a folder for your scripts, and copy its path to the Clipboard.
3. In the Windows Start menu, search for "path" and select**Edit the system environment variables** .  
![Windows Start Edit The System Environment Variables](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/windows-start-edit-the-system-environment-variables.jpg)
4. Find the**Path** variable under**User variables for YOUR\_USERNAME** . Double-click on it to edit it. Click on**New** , and paste the path to your scripts folder. Click on**OK** to accept the changes.  
![Environment Variables User Account Path](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/environment-variables-user-account-path.jpg)
5. Return to your scripts folder in Windows Explorer. Create a new batch file there named "wht.bat". "Inside" it, place this command:  
`whisper --model tiny --language en %1`  
![Creating WHT Batch File](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/creating-wht-batch-file.jpg)
6. Create two more batch files, "whs" and "whm".
7. Place this inside the first script:  
`whisper --model small --language en %1`
8. Place this inside the second:  
`whisper --model medium --language en %1`

 Congratulations, you now have three scripts for easily using Whisper's tiny, small, and medium models with your audio files! To transcribe any audio file to text:

1. Locate the file with**Windows File Explorer** .
2. **Right-click** on an empty spot and choose**Open in Terminal** .
3. Type this command, replacing "wht" with "whs" or "whm" to use the small or medium language models:  
`wht YOUR_AUDIO_FILE.mp3`

## Typing at the Speed of Sound With Whisper

 Even the quickest touch-typists can't match the speed at which we speak. However, until recently, talking instead of typing wasn't optimal for creating documents.

 Most voice-to-text solutions produced mediocre results. You could find a few solutions worth trying, but they were complicated to use, or costly. Thankfully, Whisper changed all that.

 After the steps above, you should be ready to transcribe or translate your voice with high accuracy, using only a single command.


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
<li><a href="https://windows11.techidaily.com/step-by-step-guide-to-switching-notepad-to-dark-theme-in-windows-11/"><u>Step-by-Step Guide to Switching Notepad to Dark Theme in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/solutions-for-rearranged-characters-in-windows-os/"><u>Solutions for Rearranged Characters in Windows OS</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-social-media-savvy-crafting-your-best-self-with-top-tips-for-bios/"><u>[New] Social Media Savvy  Crafting Your Best Self with Top Tips for Bios</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-through-common-windo-errors-quickly/"><u>Navigating Through Common Windo Errors, Quickly</u></a></li>
<li><a href="https://windows11.techidaily.com/remedying-directx-download-problems-in-os/"><u>Remedying DirectX Download Problems in OS</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-fix-guide-to-restore-windows-11-troubleshooters/"><u>Quick FIX Guide to Restore Windows 11 Troubleshooters</u></a></li>
<li><a href="https://location-fake.techidaily.com/5-hassle-free-solutions-to-fake-location-on-find-my-friends-of-honor-magic-5-lite-drfone-by-drfone-virtual-android/"><u>5 Hassle-Free Solutions to Fake Location on Find My Friends Of Honor Magic 5 Lite | Dr.fone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-the-best-android-sim-unlock-code-generators-unlock-your-oneplus-11r-phone-hassle-free-by-drfone-android/"><u>In 2024, The Best Android SIM Unlock Code Generators Unlock Your OnePlus 11R Phone Hassle-Free</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-systems-peak-performance-limits/"><u>Unveiling System's Peak Performance Limits</u></a></li>
<li><a href="https://fox-helps.techidaily.com/new-owning-your-sound-instagrams-ip-framework-for-2024/"><u>[New] Owning Your Sound  Instagram's IP Framework for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/securely-store-and-view-onedrive-data-locally/"><u>Securely Store and View OneDrive Data Locally</u></a></li>
<li><a href="https://windows11.techidaily.com/preserving-calculator-precedence-on-windows-systems/"><u>Preserving Calculator Precedence on Windows Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-docx-to-pdf-migration-for-windows-users/"><u>Step-by-Step DOCX to PDF Migration for Windows Users</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/unveiling-the-mystery-of-facebooks-status-video-downloads/"><u>Unveiling the Mystery of Facebook's Status Video Downloads</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/best-3-tecno-spark-20c-emulator-for-mac-to-run-your-wanted-android-apps-drfone-by-drfone-android/"><u>Best 3 Tecno Spark 20C Emulator for Mac to Run Your Wanted Android Apps | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/procedures-to-enable-or-disable-windows-build-service/"><u>Procedures to Enable or Disable Windows Build Service</u></a></li>
<li><a href="https://windows11.techidaily.com/remedy-for-unsupported-audio-device-windowss/"><u>Remedy for Unsupported Audio Device Windowss</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ed-overcome-the-invisibility-of-short-videos-for-2024/"><u>[Updated] Overcome  The Invisibility of Short Videos for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/the-ultimate-guide-to-github-desktop-on-windows-11-os/"><u>The Ultimate Guide to GitHub Desktop on Windows 11 OS</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-in-2024-final-cut-pros-top-10-vfx-power-players/"><u>[New] In 2024, Final Cut Pro’s Top 10 VFX Power Players</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/updated-in-2024-the-ultimate-list-of-free-video-compressors-for-windows-10-2023-edition/"><u>Updated In 2024, The Ultimate List of Free Video Compressors for Windows 10 (2023 Edition)</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-how-to-bypass-iphone-7-plus-passcode-easily-video-inside-by-drfone-ios/"><u>In 2024, How to Bypass iPhone 7 Plus Passcode Easily Video Inside</u></a></li>
<li><a href="https://windows11.techidaily.com/transform-your-word-docs-seamlessly-into-pdfs-using-windows-11/"><u>Transform Your Word Docs Seamlessly Into PDFs Using Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-the-mystery-of-windows-blue-screen-error-0x8007007e/"><u>Unraveling the Mystery of Windows Blue Screen Error: 0X8007007E</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-top-5-tracking-apps-to-track-poco-m6-pro-4g-without-them-knowing-drfone-by-drfone-virtual-android/"><u>In 2024, Top 5 Tracking Apps to Track Poco M6 Pro 4G without Them Knowing | Dr.fone</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-tips-for-embedding-time-stamps-in-youtube-clips/"><u>2024 Approved  Tips for Embedding Time Stamps in YouTube Clips</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-2024-approved-in-depth-look-at-camstudios-capturing-capabilities/"><u>[Updated] 2024 Approved  In-Depth Look at CamStudio's Capturing Capabilities</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-data-from-oneplus-11-5g-to-samsung-phone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Data from OnePlus 11 5G to Samsung Phone | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/strategies-for-winmedia-error-resolution/"><u>Strategies for WinMedia Error Resolution</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-2024-approved-quickshot-flipslow-mpeg/"><u>[Updated] 2024 Approved  QuickShot FlipSlow MPEG</u></a></li>
<li><a href="https://windows11.techidaily.com/uncovering-digital-shadows-sid-extraction-in-win11/"><u>Uncovering Digital Shadows: SID Extraction in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-code-0xc0000142-on-windows-devices/"><u>Tackling Code 0XC0000142 on Windows Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/top-windows-techniques-for-enjoying-high-definition-adventures-with-scummvm/"><u>Top Windows Techniques for Enjoying High-Definition Adventures with ScummVM</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-device-synergy-with-google-nearby-sharing/"><u>Unlocking Device Synergy with Google Nearby Sharing</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-in-2024-maintaining-a-continuous-snapchat-connection/"><u>[New] In 2024, Maintaining a Continuous Snapchat Connection</u></a></li>
<li><a href="https://windows11.techidaily.com/quiet-windows-11-feedback-and-hints/"><u>Quiet Windows 11 Feedback and Hints</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-recurrent-enter-to-bios-in-windows-boot-cycle/"><u>Overcoming Recurrent Enter To BIOS in Windows Boot Cycle</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-chromes-erroneous-threat-detection-a-guide/"><u>Navigating Chrome's Erroneous Threat Detection: A Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/securing-smooth-operation-fix-frozen-epic-games-launcher/"><u>Securing Smooth Operation: Fix Frozen Epic Games Launcher</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/updated-hot-hits-huddle-the-must-have-tiktok-rap-playlists-of-2021/"><u>[Updated] Hot Hits Huddle  The Must-Have TikTok Rap Playlists of 2021</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-windows-credentials-error-loop/"><u>Overcoming Windows Credentials Error Loop</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-win-ethernet-no-internet-error/"><u>Resolving Win Ethernet No Internet Error</u></a></li>
<li><a href="https://windows11.techidaily.com/rectifying-thx-not-working-in-windows-setup/"><u>Rectifying THX Not Working in Windows Setup</u></a></li>
<li><a href="https://windows11.techidaily.com/unblocking-your-windowed-discord-interface-in-windows/"><u>Unblocking Your Windowed Discord Interface in Windows</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/in-2024-discover-expressive-humming-track/"><u>In 2024, Discover Expressive Humming Track</u></a></li>
<li><a href="https://windows11.techidaily.com/solving-ipad-image-import-issues-in-windows-1111-pro/"><u>Solving iPad Image Import Issues in Windows 11/11 Pro</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-the-beginners-blueprint-steering-clear-of-the-8-most-regrettable-youtubing-mistakes/"><u>[New] The Beginner's Blueprint  Steering Clear of the 8 Most Regrettable YouTubing Mistakes</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/in-2024-decoding-revenue-from-a-million-watches-on-youtube/"><u>In 2024, Decoding Revenue From A Million Watches on YouTube</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/video-resolution-essentials-a-beginners-guide-to-hd-pixels-for-2024/"><u>Video Resolution Essentials A Beginners Guide to HD Pixels for 2024</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-2024-approved-essential-techniques-for-vimeo-video-submission-from-mmc/"><u>[New] 2024 Approved  Essential Techniques for Vimeo Video Submission From MMC</u></a></li>
<li><a href="https://screen-capture.techidaily.com/capturing-your-macbook-pro-screens-a-step-by-step-tutorial-for-2024/"><u>Capturing Your MacBook Pro Screens  A Step-by-Step Tutorial for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/unlocking-windows-history-for-lately-used-pages/"><u>Unlocking Windows History for Lately Used Pages</u></a></li>
<li><a href="https://extra-hints.techidaily.com/2024-approved-bridging-the-gap-between-individual-images-using-picshot/"><u>2024 Approved  Bridging the Gap Between Individual Images Using Picshot</u></a></li>
</ul></div>
