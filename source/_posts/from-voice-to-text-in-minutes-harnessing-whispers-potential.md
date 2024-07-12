---
title: "From Voice to Text in Minutes: Harnessing Whisper's Potential"
date: 2024-07-11T21:48:48.226Z
updated: 2024-07-12T21:48:48.226Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes From Voice to Text in Minutes: Harnessing Whisper's Potential"
excerpt: "This Article Describes From Voice to Text in Minutes: Harnessing Whisper's Potential"
keywords: Quick Text Conversion,Voice-to-Text Services,Whisper AI Technology,Speech Recognition Advances,Text Output Instantaneously,Real-Time Speech Processing,Audio to Written Translation
thumbnail: https://thmb.techidaily.com/fff656b551e024a92bec77f08e34169fdbb7972daf3e003aecf76e9fd40fed20.jpg
---

## From Voice to Text in Minutes: Harnessing Whisper's Potential

 The very same people behind ChatGPT have created another AI-based tool you can use today to boost your productivity. We're referring to Whisper, a voice-to-text solution that eclipsed all similar solutions that came before it.

 You can use Whisper in your programs or the command line. And yet, that defeats its very purpose: typing without a keyboard. If you need to type to use it, why use it to avoid typing? Thankfully, you can now use Whisper through a desktop GUI. Even better, it can also transcribe your voice almost in real time. Let's see how you can type with your voice using Whisper Desktop.

## What Is OpenAI's Whisper?

 OpenAI's Whisper is an Automatic Speech Recognition system (ASR for short) or, to put it simply, is a solution for converting spoken language into text.

 However, unlike older dictation and transcription systems, Whisper is an AI solution trained on over 680,000 hours of speech in various languages. Whisper offers unparalleled accuracy and, quite impressively, not only is it multilingual, but it can also translate between languages.

 More importantly, it's free and available as open source. Thanks to that, many developers have forked its code into their own projects or created apps that rely on it, like Whisper Desktop.

 If you'd prefer the "vanilla" version of Whisper and the versatility of the terminal instead of clunky GUIs, check our article on [how to turn your voice into text with OpenAI's Whisper for Windows](https://www.makeuseof.com/dictate-documents-openai-whisper/).

## Are Whisper and Whisper Desktop the Same?

 Despite its official-sounding name, Whisper Desktop is a third-party GUI for Whisper, made for everyone who'd prefer to click buttons instead of typing commands.

 Whisper Desktop is a standalone solution that doesn't rely on an existing Whisper installation. As a bonus, it uses an alternative, optimized version of Whisper, so it should perform better than the standalone version.

 You're on the other end of the spectrum, and instead of seeking an easier way to use Whisper than the terminal you're seeking ways to implement it in your own solutions? Rejoice, for [OpenAI has opened access to ChatGPT and Whisper APIs](https://www.makeuseof.com/what-chatgpt-and-whisper-apis-means-for-businesses/).

## Download & Install Whisper Desktop

 Although Whisper Desktop is easier to use than the standalone Whisper, its installation is more convoluted than repeatedly clicking Next in a wizard.

1. Visit [Whisper Desktop's official Github page](https://github.com/Const-me/Whisper). Look on the right, and click on the latest version under **Releases**.  
![Whisper Desktop Github Releases Link](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/whisper-desktop-github-releases-link.jpg)
2. Under **Assets**, click **WhisperDesktop.zip** and download it to your PC.  
![Whisper Desktop Github Download Link](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/whisper-desktop-github-download-link.jpg)
3. Extract the downloaded archive to a folder and use your file manager to visit it. Inside you will find the Whisper Desktop application. Double-click on it to run it.  
![Whisper Desktop App in File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/whisper-desktop-app-in-file-explorer.jpg)
4. You also need a Whisper language model in **GCML** binary format. Whisper Desktop will provide you with two links for acquiring one. Skip the second link for generating your own model since it's a more complicated process. Click on **Hugging Face** to open that page in your default browser, from where you can download a ready-to-use file.  
![Whisper Desktop Language Model Links](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/whisper-desktop-language-model-links.jpg)
5. The version of Whisper Desktop we used while writing this article provided a link to an obsolete repository at Hugging Face. If you meet the same problem, notice a link to a **new location**. Click on it to visit the new repository.  
![Hugging Face Whisper Models New Location](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/hugging-face-whisper-models-new-location.jpg)
6. Click on the link that will take you to the available **models**.  
![Hugging Face Available Models Link](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/hugging-face-available-models-link.jpg)
7. From that list, click on either the **ggml-medium.bin** or **ggml-medium.en.bin**, depending on if you want multilingual or English-only support in Whisper.  
![Hugging Face Whisper Medium Model Link](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/hugging-face-whisper-medium-model-link.jpg)
8. Finally, you should have reached your destination. Notice the line stating that this file is stored with Git LFS and is too big to display, but you can still download it. Click on **download** to do precisely that.  
![Hugging Face Whisper Medium Model Download Link](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/hugging-face-whisper-medium-model-download-link.jpg)
9. When the file completes downloading, use your favorite file manager (File Explorer will do) to move the downloaded language model file into the same folder as Whisper Desktop.  
![Whisper Medium Model Placed in Whisper Desktop Folder in File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/whisper-medium-model-placed-in-whisper-desktop-folder-in-file-explorer.jpg)

## Transcribing With Whisper Desktop

 Transcribing with Whisper Desktop is easy, but you may still need one or two clicks to use the app.

 Rerun Whisper Desktop. Does it (still) miss the correct path to your downloaded language model? Click on the **button with the three dots** on the right of the field and manually select the file you downloaded from Hugging Face.

 From this spot, you can also use the drop-down menu next to **Model Implementation** to choose if you want to run Whisper on your GPU (**GPU**), on both the CPU and GPU (**Hybrid**), or only on the CPU (**Reference**).

![Whisper Desktop Selecting Model Implementation](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/whisper-desktop-selecting-model-implementation.jpg)

 The **Advanced** button leads to more options that affect how Whisper will run on your hardware. However, since the button clearly states they are advanced, we suggest you only tweak them if you are troubleshooting or know what you are doing. Setting the wrong options values here can impose a performance penalty or render the app unusable.

 Click on OK to move to the app's main interface.

![Whisper Desktop Advanced Options Changing Graphics Adapter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/whisper-desktop-advanced-options-changing-graphics-adapter.jpg)

 If you already have a recording of your voice you want to turn into written text, click on **Transcribe File** and select it. Still, we will use Whisper Desktop for live transcription for this article.

 The options offered are straightforward. You can select the **language** Whisper will use, choose if you want to **translate** between languages and enable the app's **Debug Console**.

 Most English-speaking users can safely skip those options and only ensure the correct audio input is selected from the pull-down menu next to **Capture Device**.

 Make sure **Save to text file** and **Append to that file** are enabled to have Whisper Desktop save its output to a file without overwriting its content. Use the **button with the three dots** on the right of the file's path field to define said text file.

![Whisper Desktop Saving And Appending to Text File](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/whisper-desktop-saving-and-appending-to-text-file.jpg)

 Click on **Capture** to begin transcribing your speech to text.

 Whisper Desktop will show you three indicators for when it detects voice activity, when it's actively transcribing, and when the process is stalled.

 You can keep talking for as long as you like, and you should occasionally see the two first indicators flashing while the app turns your voice into text. Click **Stop** when done.

![Whisper Desktop Active Voice Transcribing](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/whisper-desktop-active-voice-transcribing.jpg)

 The text file you selected should open in your default text editor, containing in written form everything you said until you clicked **Stop**.

![Transcribed Text With Whisper Desktop in Typora](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/transcribed-text-with-whisper-desktop-in-typora.jpg)

 We should note that you can also do the opposite of what we saw here: convert any text to speech. This way you can listen to anything as if it were a podcast instead of tiring your eyes squinting at screens. For more info on that, check our article on [some of the best free online tools to download text-to-speech as MP3 audio](https://www.makeuseof.com/tag/download-text-to-speech-as-mp3-audio/).

## Whisper Desktop Voice-Typing Tips

 Although Whisper Desktop can be a lifesaver, enabling you to write with your voice much quicker than you could type, it's far from perfect.

 During our testing, we found that it may occasionally stutter, skip some words, fail to transcribe until you manually stop and restart the process, or get stuck in a loop and keep re-transcribing the same phrase repeatedly.

 We believe those are temporary glitches that will be fixed since the standalone Whisper doesn't exhibit the same issues.

 Apart from those minor bumps, turning your voice to text should be effortless with Whisper Desktop. Still, during our tests, we found that it can perform even better if...

1. Instead of uttering only two or three words and then pausing, Whisper can understand you better if you go on longer. Try to at least give it an entire sentence at a time.
2. For the same reason, avoid repeatedly starting and stopping the transcription process.
3. Whenever you realize you made a mistake, ignore it and keep going. Loading and unloading the language model seems to be the most time-consuming part of the process with the current state of Whisper and our available hardware. So, it's quicker to keep talking and then edit out your mistakes afterward.
4. As with the standalone version of Whisper, it's best to use the optimal language model for your available hardware. You can use up to the **medium** model if your GPU has 8GB of VRAM. For less VRAM, go for the smaller models. Only choose the slightly more accurate but also much more demanding **large** model if you use a GPU with 16GB of VRAM or more.
5. Remember that the larger the language model, the slower the transcription process. Don't go for a model larger than needed. You'll probably find Whisper Desktop can already "understand you" most of the time with the medium or smaller models, with only one or two errors per paragraph.

## Are You Still Typing? Use Your Voice With Whisper

 Despite requiring some time to set up, as you will see when you try it, Whisper Desktop performs much better than most alternatives, with much higher accuracy and better speed.

 After you start using it to type with your voice, your keyboard may look like a relic from ancient times long gone.

 You can use Whisper in your programs or the command line. And yet, that defeats its very purpose: typing without a keyboard. If you need to type to use it, why use it to avoid typing? Thankfully, you can now use Whisper through a desktop GUI. Even better, it can also transcribe your voice almost in real time. Let's see how you can type with your voice using Whisper Desktop.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://ios-unlock.techidaily.com/in-2024-how-to-remove-and-reset-face-id-on-apple-iphone-14-pro-max-by-drfone-ios/"><u>In 2024, How to Remove and Reset Face ID on Apple iPhone 14 Pro Max</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-from-novice-to-content-creator-your-youtube-journey-begins/"><u>2024 Approved  From Novice to Content Creator  Your YouTube Journey Begins</u></a></li>
<li><a href="https://windows11.techidaily.com/effortlessly-upgrading-windows-11-in-place/"><u>Effortlessly Upgrading Windows 11 in Place</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-2024-approved-create-engaging-videos-with-these-top-split-screen-apps/"><u>Updated 2024 Approved Create Engaging Videos with These Top Split Screen Apps</u></a></li>
<li><a href="https://review-topics.techidaily.com/play-mov-movies-on-htc-u23-is-it-possible-by-aiseesoft-video-converter-play-mov-on-android/"><u>Play MOV movies on HTC U23, is it possible?</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/new-universal-ledger-of-podcast-navigation-points-and-directories/"><u>New Universal Ledger of Podcast Navigation Points and Directories</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-skype-call-chronicles-20plus-strategies-for-savvy-windowsmac-users/"><u>[Updated] Skype Call Chronicles  20+ Strategies for Savvy Windows/Mac Users</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/2024-approved-youtubes-forgotten-footage-watching-deleted-content-made-easy/"><u>2024 Approved  Youtube's Forgotten Footage  Watching Deleted Content Made Easy</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-2024-approved-framebyframe-faceoff/"><u>[New] 2024 Approved  FrameByFrame Faceoff</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-in-2024-vlc-guide-setting-up-screen-recordings/"><u>[Updated] In 2024, VLC Guide  Setting Up Screen Recordings</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-missed-files-in-steam-and-windows-11/"><u>Overcoming Missed Files in Steam & Windows 11</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-data-after-switching-from-oppo-find-x6-to-latest-samsung-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Data After Switching From Oppo Find X6 to Latest Samsung | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/convenience-at-a-click-discover-how-to-enable-gestures-on-edge-windows-11/"><u>Convenience at a Click: Discover How to Enable Gestures on Edge (Windows 11)</u></a></li>
<li><a href="https://windows11.techidaily.com/curing-unable-to-retrieve-settings-issue-with-geforce-experience-on-windows-11/"><u>Curing Unable to Retrieve Settings Issue with GeForce Experience on Windows 11</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-three-ways-to-sim-unlock-samsung-galaxy-a15-5g-by-drfone-android/"><u>In 2024, Three Ways to Sim Unlock Samsung Galaxy A15 5G</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-remove-a-previously-synced-google-account-from-your-realme-c51-by-drfone-android/"><u>How to Remove a Previously Synced Google Account from Your Realme C51</u></a></li>
<li><a href="https://windows11.techidaily.com/exploring-windows-11s-admin-tools/"><u>Exploring Windows 11'S Admin Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-windows-11s-insufficient-uninstall-rights/"><u>Fixing Windows 11'S Insufficient Uninstall Rights</u></a></li>
<li><a href="https://windows11.techidaily.com/improve-file-selection-techniques-activating-windows-11-boxes/"><u>Improve File Selection Techniques: Activating Windows 11 Boxes</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-the-nuances-of-widget-alerts-in-windows/"><u>Navigating the Nuances of Widget Alerts in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-xc0f1103f-flaw-with-nvidias-windows-software/"><u>Overcoming XC0F1103F Flaw with Nvidia's Windows Software</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-in-2024-navigating-video-uploads-on-social-platforms/"><u>[Updated] In 2024, Navigating Video Uploads on Social Platforms</u></a></li>
<li><a href="https://windows11.techidaily.com/power-preservation-pitfalls-the-reality-of-modern-standby/"><u>Power Preservation Pitfalls: The Reality of Modern Standby</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-best-10-blu-ray-players-of-2024/"><u>[New] Best 10 Blu-Ray Players of 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-icon-positioning-in-windows/"><u>Mastering Icon Positioning in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/mending-the-absence-of-dxgidll-in-new-os-windows-11/"><u>Mending the Absence of Dxgi.dll in New OS, Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-windows-unplayable-file-challenge/"><u>Addressing Windows' Unplayable File Challenge</u></a></li>
<li><a href="https://windows11.techidaily.com/maximizing-command-control-on-windows-with-sudo/"><u>Maximizing Command Control on Windows with Sudo</u></a></li>
<li><a href="https://windows11.techidaily.com/customizing-user-experience-through-gpos-in-windows-11-and-11/"><u>Customizing User Experience Through GPOs in Windows 11 & 11</u></a></li>
<li><a href="https://windows11.techidaily.com/expert-tips-to-revive-winget-in-windows-profiles/"><u>Expert Tips to Revive Winget in Windows Profiles</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/n-2024-step-by-step-approach-to-crafting-youtube-intros/"><u>[New] In 2024, Step-by-Step Approach to Crafting YouTube Intros</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-epochal-passphrase-problem-in-windows-os/"><u>Deciphering “Epochal Passphrase Problem in Windows OS”</u></a></li>
<li><a href="https://windows11.techidaily.com/get-to-safety-six-steps-to-entering-safe-mode-in-windows-11/"><u>Get to Safety: Six Steps to Entering Safe Mode in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-reinvigorate-the-essential-wsreset-process/"><u>How to Reinvigorate the Essential WSReset Process</u></a></li>
<li><a href="https://windows11.techidaily.com/harness-window-11-a-productivity-playbook/"><u>Harness Window 11: A Productivity Playbook</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-update-iphone-13-pro-without-losing-any-data-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How to Update iPhone 13 Pro without Losing Any Data? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/extend-the-time-windows-11-spends-in-shutdown-with-ongoing-jobs/"><u>Extend the Time Windows 11 Spends in Shutdown with Ongoing Jobs</u></a></li>
<li><a href="https://windows11.techidaily.com/elevate-windows-steam-performance-preventing-zero-speed-slowdowns/"><u>Elevate Windows Steam Performance: Preventing Zero-Speed Slowdowns</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/updated-2024-approved-eclectic-sound-selection-on-youtube/"><u>Updated 2024 Approved Eclectic Sound Selection on YouTube</u></a></li>
<li><a href="https://windows11.techidaily.com/changing-network-address-translation-types-simplified-for-wins-oses/"><u>Changing Network Address Translation Types Simplified for Wins OSes</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-the-reality-of-now-vrs-evolution-and-challenges/"><u>In 2024, The Reality of Now  VR's Evolution and Challenges</u></a></li>
<li><a href="https://windows11.techidaily.com/methods-to-correct-the-internal-error-on-windows-1111-pro/"><u>Methods to Correct the Internal Error on Windows 11/11 Pro</u></a></li>
<li><a href="https://windows11.techidaily.com/immediate-action-to-freeze-damaged-windows-pins/"><u>Immediate Action to Freeze-Damaged Windows PINs</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-in-2024-from-recordings-to-live-an-obs-guide-to-youtube-and-twitch-streaming/"><u>[New] In 2024, From Recordings to Live  An OBS Guide to YouTube and Twitch Streaming</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/new-in-2024-mute-media-magic-a-how-to-guide-for-quieting-soundtracks-in-mov-files-across-operating-systems/"><u>New In 2024, Mute Media Magic A How-To Guide for Quieting Soundtracks in MOV Files Across Operating Systems</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-2024-approved-unravel-the-mystery-of-accessing-your-watchlist-on-facebook/"><u>[New] 2024 Approved  Unravel the Mystery of Accessing Your Watchlist on Facebook</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-fake-gps-on-huawei-nova-y71-for-mobile-legends-drfone-by-drfone-virtual-android/"><u>How To Fake GPS On Huawei Nova Y71 For Mobile Legends? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-remove-the-show-more-options-entry-from-the-context-menu-on-windows-11/"><u>How to Remove the Show More Options Entry From the Context Menu on Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/clearing-pathways-to-successful-office-activation/"><u>Clearing Pathways to Successful Office Activation</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-the-windows-lsa-disablement-warning/"><u>Bypassing the Windows LSA Disablement Warning</u></a></li>
<li><a href="https://windows11.techidaily.com/preventing-dual-device-names-on-your-windows-network/"><u>Preventing Dual Device Names on Your Windows Network</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-windows-11-multi-display-setup/"><u>Navigating Windows 11 Multi-Display Setup</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-windows-11s-network-failure-0x800704b3/"><u>Navigating Windows 11'S Network Failure 0X800704B3</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-a-comparison-of-best-linux-screenshare-utilities-for-2024/"><u>[New] A Comparison of Best Linux Screenshare Utilities for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/microsoft-words-silent-mode-fix-for-pc-users/"><u>Microsoft Word's Silent Mode Fix for PC Users</u></a></li>
</ul></div>
