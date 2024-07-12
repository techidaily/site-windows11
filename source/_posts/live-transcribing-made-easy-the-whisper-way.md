---
title: Live Transcribing Made Easy - The Whisper Way
date: 2024-07-11T21:34:03.344Z
updated: 2024-07-12T21:34:03.344Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Live Transcribing Made Easy - The Whisper Way
excerpt: This Article Describes Live Transcribing Made Easy - The Whisper Way
keywords: Easy Live Transcription,Simplify Transcribing,Audio to Text Service,Quick Transcribe Method,Streamlined Transcription,Effortless Whispering,Simple Speech-to-Text
thumbnail: https://thmb.techidaily.com/f411804b07d8feb5757ac6a37c514ffad28202840ac720d56c6054350be2fb61.jpg
---

## Live Transcribing Made Easy - The Whisper Way

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
<li><a href="https://smart-video-creator.techidaily.com/updated-in-2024-moviemaster-for-macos/"><u>Updated In 2024, MovieMaster for macOS</u></a></li>
<li><a href="https://windows11.techidaily.com/get-your-pcs-virtual-machine-game-strong-with-hyper-v/"><u>Get Your PC's Virtual Machine Game Strong with Hyper-V</u></a></li>
<li><a href="https://windows11.techidaily.com/initiating-contact-accessing-windows-printer-administration-tools/"><u>Initiating Contact: Accessing Windows' Printer Administration Tools</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/new-top-web-based-audio-visualizers-for-videos-for-2024/"><u>New Top Web-Based Audio Visualizers for Videos for 2024</u></a></li>
<li><a href="https://ios-location-track.techidaily.com/in-2024-solutions-to-spy-on-apple-iphone-15-plus-with-and-without-jailbreak-drfone-by-drfone-virtual-ios/"><u>In 2024, Solutions to Spy on Apple iPhone 15 Plus with and without jailbreak | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/notepaddarksettingsinstructionswin1011/"><u>NotepadDarkSettingsInstructionsWin10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/fixes-for-stumbling-windows-discord-search-bar/"><u>Fixes for Stumbling Windows Discord Search Bar</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-deactivated-system-cooler-protocol-on-pcs/"><u>Overcoming Deactivated System Cooler Protocol on PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/rectifying-code-0x0001-failures-for-nvidia-ge-in-w10w11/"><u>Rectifying Code 0X0001 Failures for Nvidia GE in W10/W11</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-windows-store-error-code-0x80073cf3/"><u>Overcoming Windows Store Error Code 0X80073CF3</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-reducing-obs-streaming-bitrate/"><u>[New] Reducing OBS Streaming Bitrate</u></a></li>
<li><a href="https://windows11.techidaily.com/revitalize-memory-integrity-for-secure-systems-on-win11/"><u>Revitalize Memory Integrity for Secure Systems on Win11</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/pokemon-go-error-12-failed-to-detect-location-on-tecno-camon-20-drfone-by-drfone-virtual-android/"><u>Pokemon Go Error 12 Failed to Detect Location On Tecno Camon 20? | Dr.fone</u></a></li>
<li><a href="https://fox-links.techidaily.com/updated-maximize-your-workflow-with-efficient-use-of-macs-preview-tool/"><u>[Updated] Maximize Your Workflow with Efficient Use of Mac's Preview Tool</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/updated-2024-approved-championing-quiet-calls-how-to-silence-zoom-audio-quickly-and-easily/"><u>Updated 2024 Approved Championing Quiet Calls How to Silence Zoom Audio Quickly and Easily</u></a></li>
<li><a href="https://windows11.techidaily.com/sidestep-windows-11-surveillance-measures/"><u>Sidestep Windows 11 Surveillance Measures</u></a></li>
<li><a href="https://windows11.techidaily.com/sculpting-digital-art-the-most-impressive-new-additions-to-paint/"><u>Sculpting Digital Art: The Most Impressive New Additions to Paint</u></a></li>
<li><a href="https://iphone-transfer.techidaily.com/in-2024-how-to-transfer-everything-from-apple-iphone-12-pro-max-to-iphone-8x11-drfone-by-drfone-transfer-from-ios/"><u>In 2024, How to Transfer Everything from Apple iPhone 12 Pro Max to iPhone 8/X/11 | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-guide-configure-time-zones-on-windows-manually/"><u>Quick Guide: Configure Time Zones on Windows Manually</u></a></li>
<li><a href="https://windows11.techidaily.com/perfect-notetaking-companions-the-7-finest-for-pen-tech/"><u>Perfect Notetaking Companions: The 7 Finest for Pen Tech</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-unlocking-the-potential-effective-use-of-split-screen-on-facebook/"><u>[New] Unlocking the Potential  Effective Use of Split-Screen on Facebook</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-geforce-x0001-error-on-w10w11-systems/"><u>Overcoming GeForce X0001 Error on W10/W11 Systems</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/in-2024-shake-it-off-8-excellent-free-video-stabilizers-to-try-this-year/"><u>In 2024, Shake It Off 8 Excellent Free Video Stabilizers to Try This Year</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/cutting-edge-openings-at-no-cost-the-best-youtube-intro-makers/"><u>Cutting-Edge Openings at No Cost  The Best YouTube Intro Makers</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/updated-a-deeper-dive-into-youtube-seo-and-keywords/"><u>[Updated] A Deeper Dive Into YouTube SEO and Keywords</u></a></li>
<li><a href="https://windows11.techidaily.com/remedying-unresponsive-printers-in-windows-11-environment/"><u>Remedying Unresponsive Printers in Windows 11 Environment</u></a></li>
<li><a href="https://windows11.techidaily.com/recovering-database-connections-resolving-malwarebytes-service-issues/"><u>Recovering Database Connections: Resolving Malwarebytes Service Issues</u></a></li>
<li><a href="https://windows11.techidaily.com/redirect-to-file-explorer-using-the-onedrive-shortcut/"><u>Redirect to File Explorer Using the OneDrive Shortcut</u></a></li>
<li><a href="https://extra-hints.techidaily.com/choosing-the-right-medium-audio-vs-video-based-platforms-for-2024/"><u>Choosing the Right Medium  Audio vs Video-Based Platforms for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/reversing-camera-apps-loss-of-recorded-images/"><u>Reversing Camera App's Loss of Recorded Images</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-2024-approved-android-dominance-top-10-moba-games-showcase/"><u>[Updated] 2024 Approved  Android Dominance  Top 10 MOBA Games Showcase</u></a></li>
<li><a href="https://windows11.techidaily.com/fixing-flawed-setups-a-guide-to-windows-package-woes/"><u>Fixing Flawed Setups: A Guide to Windows Package Woes</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-stuck-context-menus-a-quick-guide-to-solutions/"><u>Overcoming Stuck Context Menus: A Quick Guide to Solutions</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-guide-to-solving-disk-errors-uninitialized-scenarios/"><u>Quick Guide to Solving Disk Errors: Uninitialized Scenarios</u></a></li>
<li><a href="https://extra-information.techidaily.com/2024-approved-astonishing-assessment-and-alternative-choices/"><u>2024 Approved  Astonishing Assessment & Alternative Choices</u></a></li>
<li><a href="https://fox-glue.techidaily.com/updated-2024-approved-assessing-daily-video-consumption-in-gb-units/"><u>[Updated] 2024 Approved  Assessing Daily Video Consumption in GB Units</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-sweep-through-your-contacts-with-speed-and-skill-for-2024/"><u>[New] Sweep Through Your Contacts with Speed and Skill for 2024</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/updated-the-best-virtualdub-alternatives-for-video-post-production/"><u>Updated The Best VirtualDub Alternatives for Video Post-Production</u></a></li>
<li><a href="https://windows11.techidaily.com/insights-on-how-to-utilize-execution-nicknames/"><u>Insights on How to Utilize Execution Nicknames</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-unlocking-the-process-of-saving-whatsapp-dialogues/"><u>[Updated] Unlocking the Process of Saving WhatsApp Dialogues</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/in-2024-voice-transformation-powerhouses-a-deep-dive-into-25-leading-apps-and-their-capabilities/"><u>In 2024, Voice Transformation Powerhouses A Deep Dive Into 25 Leading Apps and Their Capabilities</u></a></li>
<li><a href="https://windows11.techidaily.com/smart-task-management-microsofts-ai-copilot-for-windows-11-enhances-workflow/"><u>Smart Task Management: Microsoft's AI Copilot for Windows 11 Enhances Workflow</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/flip-monitor-settings-for-optimal-view/"><u>Flip Monitor Settings for Optimal View</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/2024-approved-goovision-9000-ultimate-os-snapshotter/"><u>2024 Approved  GooVision 9000  Ultimate OS Snapshotter</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-through-boot-sector-problems-on-pc/"><u>Navigating Through Boot Sector Problems on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-solution-to-cease-iomap64-syscall-freezes-on-windows/"><u>Step-by-Step Solution to Cease IOMap64 Syscall Freezes on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-enabling-or-disabling-wi-fi-cost-tracking-in-windows-11/"><u>Guide: Enabling or Disabling Wi-Fi Cost Tracking in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/optimizing-powershell-access-control-settings/"><u>Optimizing PowerShell Access Control Settings</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-latest-guide-how-to-bypass-itel-p40plus-frp-without-computer-by-drfone-android/"><u>In 2024, Latest Guide How To Bypass Itel P40+ FRP Without Computer</u></a></li>
<li><a href="https://windows11.techidaily.com/optimize-windows-steam-streams-stopping-zero-rate-issues/"><u>Optimize Windows Steam Streams: Stopping Zero-Rate Issues</u></a></li>
<li><a href="https://network-issues.techidaily.com/1719974685281-effortless-graphics-enhancement-for-intels-g3000-win11/"><u>Effortless Graphics Enhancement for Intel's G3000 Win11.</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/2024-approved-vimeo-end-screen-how-to-add-end-screen-to-video-on-vimeo/"><u>2024 Approved  Vimeo End Screen  How to Add End Screen to Video on Vimeo?</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-5-techniques-to-transfer-data-from-vivo-v29e-to-iphone-15141312-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 5 Techniques to Transfer Data from Vivo V29e to iPhone 15/14/13/12 | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-mend-the-pairing-glitch-fixing-connection-issues-in-win-11/"><u>How to Mend the Pairing Glitch: Fixing Connection Issues in Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/methods-for-lowering-tiworkerexe-process-resource-use/"><u>Methods for Lowering TiWorker.exe Process Resource Use</u></a></li>
<li><a href="https://windows11.techidaily.com/exclusive-guide-to-forgotten-windows-11-themes/"><u>Exclusive Guide to Forgotten Windows 11 Themes</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-multi-screen-brightness-best-tools-to-light-up-your-windows-monitors/"><u>Navigating Multi-Screen Brightness: Best Tools to Light Up Your Windows Monitors</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/top-10-free-plugins-for-final-cut-pro-x-for-2024/"><u>Top 10 Free Plugins for Final Cut Pro X for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-disable-the-built-in-laptop-keyboard-in-windows/"><u>How to Disable the Built-In Laptop Keyboard in Windows</u></a></li>
</ul></div>
