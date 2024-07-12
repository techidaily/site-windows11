---
title: From Spoken Voice to Textual Output in Seconds - Whisper's Guide
date: 2024-07-11T21:17:05.884Z
updated: 2024-07-12T21:17:05.884Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes From Spoken Voice to Textual Output in Seconds - Whisper's Guide
excerpt: This Article Describes From Spoken Voice to Textual Output in Seconds - Whisper's Guide
keywords: Speech-to-Text Technology,Instant Text Conversion,Voice-To-Text Solutions,Quick Audio Transcription,Real-Time Speech Output,Whisper's Voice Guide,Seconds to Text Guide
thumbnail: https://thmb.techidaily.com/a0961ee471b397828689bb0499e11bd310468db6e686996103528a8e584f7f95.jpg
---

## From Spoken Voice to Textual Output in Seconds - Whisper's Guide

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
<li><a href="https://windows11.techidaily.com/the-hidden-dangers-in-bot-made-win-11-codes/"><u>The Hidden Dangers in Bot-Made Win 11 Codes</u></a></li>
<li><a href="https://windows11.techidaily.com/tips-for-resolving-unresponsiveness-in-your-windows-downloads-hub/"><u>Tips for Resolving Unresponsiveness in Your Windows Downloads Hub</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-windows-11s-registry-a-guide-to-its-components/"><u>Unveiling Windows 11'S Registry: A Guide to Its Components</u></a></li>
<li><a href="https://windows11.techidaily.com/bring-forth-the-forgotten-floppy-drive-sdds-in-winos/"><u>Bring Forth the Forgotten Floppy Drive, SDDs in WinOS</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/2024-approved-breakneck-buzzers-youtubes-hottest-topics-amassing-views-overnight-by-24/"><u>2024 Approved  Breakneck Buzzers  YouTube's Hottest Topics Amassing Views Overnight by '24</u></a></li>
<li><a href="https://windows11.techidaily.com/a-practical-guide-to-running-ping-efficiently-on-pcs/"><u>A Practical Guide to Running Ping Efficiently on PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/upgrade-your-win11s-connectivity-with-these-high-priority-solutions/"><u>Upgrade Your Win11's Connectivity with These High-Priority Solutions</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-for-no-sound-when-screencasting-with-powerpoint/"><u>Troubleshooting for No Sound when Screencasting with PowerPoint</u></a></li>
<li><a href="https://windows11.techidaily.com/techniques-to-disconnect-untrusted-users-from-windows-11/"><u>Techniques to Disconnect Untrusted Users From Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/unfolding-wxpxo11-dilemnas-fixes-for-non-openable-folders-after-double-clicks/"><u>Unfolding WXP/XO11 Dilemnas: Fixes for Non-Openable Folders After Double-Clicks</u></a></li>
<li><a href="https://windows11.techidaily.com/taskbar-timeline-microsofts-ui-evolution/"><u>Taskbar Timeline: Microsoft's UI Evolution</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-2024-approved-instagram-qanda-beyond-basic-usage/"><u>[New] 2024 Approved  Instagram Q&A  Beyond Basic Usage</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-printer-busy-errors-on-pcs/"><u>Troubleshooting Printer Busy Errors on PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-failed-zip-file-extraction-in-windows-11/"><u>Troubleshooting Failed: Zip File Extraction in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/swift-recovery-overcoming-black-screen-issues-in-wins/"><u>Swift Recovery: Overcoming Black-Screen Issues in Wins</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-9-mind-blowing-tricks-to-hatch-eggs-in-pokemon-go-without-walking-on-vivo-t2-pro-5g-drfone-by-drfone-virtual-android/"><u>In 2024, 9 Mind-Blowing Tricks to Hatch Eggs in Pokemon Go Without Walking On Vivo T2 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-2024-approved-shrink-your-videos-the-best-free-compression-tools-for-windows-10/"><u>Updated 2024 Approved Shrink Your Videos The Best Free Compression Tools for Windows 10</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-the-stalled-windows-system-insight/"><u>Troubleshooting the Stalled Windows System Insight</u></a></li>
<li><a href="https://windows11.techidaily.com/the-essential-techniques-boosting-your-virtual-memory-in-windows-11/"><u>The Essential Techniques: Boosting Your Virtual Memory in Windows 11</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/2024-approved-a-step-by-step-approach-to-generating-income-with-trailers/"><u>2024 Approved  A Step-by-Step Approach to Generating Income with Trailers</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-error-0x00000709-in-windows/"><u>Addressing Error 0X00000709 in Windows</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-inventory-management/"><u>[New] Inventory Management</u></a></li>
<li><a href="https://article-posts.techidaily.com/2024-approved-mastering-character-voice-modification-techniques-in-free-fire-no-cost/"><u>2024 Approved  Mastering Character Voice Modification Techniques in Free Fire (No Cost!)</u></a></li>
<li><a href="https://windows11.techidaily.com/bridging-the-gap-activating-linux-support-in-windows/"><u>Bridging the Gap: Activating Linux Support in Windows</u></a></li>
<li><a href="https://extra-skills.techidaily.com/pure-serenity-in-the-air-top-asmr-microphones-at-low-costs-for-2024/"><u>Pure Serenity in the Air - Top ASMR Microphones at Low Costs for 2024</u></a></li>
<li><a href="https://howto.techidaily.com/android-screen-stuck-general-honor-play-40c-partly-screen-unresponsive-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Android Screen Stuck General Honor Play 40C Partly Screen Unresponsive | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/advanced-file-sorting-empowering-checkbox-selection-in-win11/"><u>Advanced File Sorting: Empowering Checkbox Selection in Win11</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/n-2024-maximizing-mobile-smartphones-and-youtube-success/"><u>[New] In 2024, Maximizing Mobile  Smartphones & YouTube Success</u></a></li>
<li><a href="https://facebook.techidaily.com/online-morality-correct-to-ban-trump-but-not-permanently/"><u>Online Morality: Correct to Ban Trump but Not Permanently</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-erase-private-data-from-iphone-se-drfone-by-drfone-ios-full-data-eraser-ios-full-data-eraser/"><u>How To Erase Private Data From iPhone SE | Dr.fone</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-honor-90-gt-get-deleted-pictures-back-with-ease-and-safety-by-fonelab-android-recover-pictures/"><u>How to Honor 90 GT Get Deleted Pictures Back with Ease and Safety?</u></a></li>
<li><a href="https://windows11.techidaily.com/verify-the-validity-three-ways-to-check-windows-11/"><u>Verify the Validity: Three Ways to Check Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/stepwise-strategy-for-full-removal-of-wsl-on-windows-11/"><u>Stepwise Strategy for Full Removal of WSL on Windows 11</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-unveiling-the-leaders-in-online-engagement/"><u>[Updated] Unveiling the Leaders in Online Engagement</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/mac-audio-setup-101-using-audacity-for-sound-recording-for-2024/"><u>Mac Audio Setup 101 - Using Audacity for Sound Recording for 2024</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/2024-approved-top-8-best-screen-recorders-with-no-lag/"><u>2024 Approved  Top 8 Best Screen Recorders with No Lag</u></a></li>
<li><a href="https://some-tips.techidaily.com/tailoring-humor-personalize-with-kinemaster-for-2024/"><u>Tailoring Humor  Personalize with KineMaster for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/the-shortcut-pathways-for-windows-starters/"><u>The Shortcut Pathways for Windows Starters</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/2024-approved-x-recorder-your-companion-for-high-quality-pc-recording/"><u>2024 Approved  X-Recorder  Your Companion for High-Quality PC Recording</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/in-2024-top-15-augmented-reality-games-like-pokemon-go-to-play-on-apple-iphone-8-plus-drfone-by-drfone-virtual-ios/"><u>In 2024, Top 15 Augmented Reality Games Like Pokémon GO To Play On Apple iPhone 8 Plus | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/win11-strategy-enhancing-hard-drive-performance/"><u>Win11 Strategy: Enhancing Hard Drive Performance</u></a></li>
</ul></div>
