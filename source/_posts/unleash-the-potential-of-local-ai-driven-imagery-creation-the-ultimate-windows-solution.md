---
title: "Unleash the Potential of Local AI-Driven Imagery Creation: The Ultimate Windows Solution"
date: 2024-08-31T22:02:20.245Z
updated: 2024-09-01T22:02:20.245Z
tags:
  - windows
categories:
  - tech
thumbnail: https://thmb.techidaily.com/12f126cae006dddf10c1360de286a92e906c5d739c81b28f20530205245977db.jpg
---

## Unleash the Potential of Local AI-Driven Imagery Creation: The Ultimate Windows Solution

### Quick Links

* [Why Would You Want Your Own Local AI Image Generator?](https://video-capture.techidaily.com/new-sonic-boom-new-technology-reviewed/)
* [How to Set Up Stable Diffusion Image Generation on Windows](https://youtube-video-recordings.techidaily.com/tackling-social-media-platforms-an-in-depth-look-at-igtv-and-youtube/)
* [AI Is a Whole New Set of Tools for Fun, Learning, and Productivity!](https://hardware-updates.techidaily.com/enhance-your-gaming-experience-the-apex-spectrum-by-maingear-now-with-dazzling-rgb-and-efficient-liquid-cooling-technology/)

## 

### Key Takeaways

* Local AI image generators on Windows are a free, unrestricted, and fun way to experiment with AI.
* Fooocus, a Stable Diffusion program, is easy to set up on Windows 10 and 11, making AI image generation accessible to anyone with a computer powerful enough.
* Generative AI is also a powerful productivity tool, and a good way to learn about technology and programming.

 AI image generation using online tools like ChatGPT, DALL-E and MidJourney is very popular, but what if you want to generate your own images using AI, on your own computer, without any restrictions? Here's the easiest way to do it on Windows.

##  Why Would You Want Your Own Local AI Image Generator?

 Online AI image generators are incredibly powerful, and able to draw from huge amounts of data to build their images based on your prompts (in the AI world, a prompt is the instructions you give the AI), but they do have some drawbacks: They come with monthly fees, they keep a history of your interactions, and they may restrict what kinds of images you can request.

 Local image generation running on your own Windows computer is free (aside from the electricity cost), and comes with no restrictions. You can experiment with any image prompt you can think of, and use community-made models to create unique content. It's a fun introduction to the emerging AI space, and can also help you develop other programming and IT skills.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4550420&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pearlmountainsoft.com/n_img/product/pic/f_02.jpg" border="0">PearlMountain Image Converter</a>
<!-- affiliate ads end -->
##  How to Set Up Stable Diffusion Image Generation on Windows

[Fooocus](https://github.com/lllyasviel/Fooocus "https://github.com/lllyasviel/Fooocus") is an image generation program built using Stable Diffusion. It's 100% free and open-source, runs offline, and provides an out-of-the box AI image generator that "just works" — once you've got it up and running, you can just start prompting it with your ideas and get (almost) immediate results.

 Most other Stable Diffusion and AI image generation tools for Windows are difficult to set up, with complex installation steps that often require familiarity with the underlying program. Fooocus is relatively simple to set up: all you need is a computer that [supports Docker running via Windows Subsystem for Linux (WSL)](https://docs.docker.com/desktop/install/windows-install/ "https://docs.docker.com/desktop/install/windows-install/") and a modest GPU (Fooocus requires a 4GB NVIDIA graphics card to run).

 It's worth noting that these steps also work on Linux. You can skip the WSL-specific steps below and just install Docker Desktop and use the Linux terminal instead of the Windows Terminal app. If you're a MacOS user, check out [DiffusionBee](https://on-screen-recording.techidaily.com/updated-premier-moba-experiences-on-your-android-device/), which provides similar, streamlined image generation with Stable Diffusion wrapped in its own app.

<!-- affiliate ads begin -->

<!-- affiliate ads end -->
###  Step 1: Install Docker Desktop and Windows Terminal

[Docker](https://vp-tips.techidaily.com/new-ultimate-auditory-interface-win-for-2024/) is software that lets you run 'containers', which are isolated environments that can hold all the dependencies and moving parts for a piece of software. They're a bit like a virtual machine, but have less overhead. To install Docker, [download and install Docker Desktop for Windows](https://www.docker.com/products/docker-desktop/ "https://www.docker.com/products/docker-desktop/").

 Docker can run on Windows 10 and 11 in either WSL or Hyper-V mode. As Fooocus only supports WSL, you'll need to [enable WSL first.](https://android-location-track.techidaily.com/top-10-telegram-spy-tools-on-tecno-spark-go-2024-for-parents-drfone-by-drfone-virtual-android/) You'll also need to [install the Windows Terminal app](https://youtube-tips.techidaily.com/ed-mastering-youtube-streaming-a-guide-for-gamers-for-2024/) before continuing.

###  Step 2: Download Fooocus

 To download Fooocus, you'll need to [visit their Github page](https://github.com/lllyasviel/Fooocus "https://github.com/lllyasviel/Fooocus") and then click on the green "Code" button, followed by "Download ZIP". GitHub isn't the most user-friendly website (it's mostly used by developers to share code with each other), so the screenshot below shows where to find the button.

![The location of the 'Download ZIP' button in GitHub](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/04/fooocus-1.png) 

 Once the .zip file has finished downloading, [extract it into its own folder](https://video-screen-grab.techidaily.com/updated-in-2024-essential-screen-capture-software-top-picks-ranked/), and open the folder containing the unzipped Fooocus files.

<!-- affiliate ads begin -->
<iframe id="iframe_672" src="//a.impactradius-go.com/gen-ad-code/5597632/1959812/17834/" width="720" height="300" scrolling="no" frameborder="0" marginheight="0" marginwidth="0"></iframe>
<!-- affiliate ads end -->
###  Step 3: Launch Fooocus

 Next, right-click on an empty spot in the Fooocus directory, and click "Open in Terminal". This will open a [Powershell](https://techtrends.techidaily.com/what-are-the-stages-in-a-game-of-royal-match/) terminal window.

![How to find the 'Open in Terminal' button in the Windows Explorer context menu](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/04/fooocus-2.png) 

<!-- affiliate ads begin -->
<a href="https://purchase.swifdoo.com/order/checkout.php?PRODS=40002162&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8b932759a5a04ddb34bf79e3f9072e4b/products/1_Product%20box%20white-1024x1024.png" border="0">SwifDoo PDF Perpetual (1 PC) Free upgrade. No monthly fees ever. 
</a>
<!-- affiliate ads end -->
 Make sure Docker Desktop is running, and then type the following docker command:

docker compose up -d

 This command does the following:

* Run the **docker compose** program, which is used to manage Docker applications
* Starts the container by bringing it **up**
* Tells the container to run in the background (**\-d** for detached mode)

![Running 'docker compose' in Powershell using the Windows Terminal](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/04/fooocus-3.png) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4737285&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/b2f83c409ce63012229fb9cd465bdcfe/products/copy_reporting_system.png" border="0">  KoolReport Pro  is an advanced solution for creating data reports and dashboards in PHP. Equipped with all  extended packages , KoolReport Pro is able to connect to various datasources, perform advanced data analysis, construct stunning charts and graphs and export your beautiful work to PDF, Excel, JPG or other formats. Plus, it includes powerful built-in reports such as pivot report and drill-down report which will save your time in building ones. 

 It will help you to write dynamic data reports easily, to construct intuitive dashboards or to build a whole business intelligence cockpit. 

  KoolReport Pro  package goes with Full Source Code, Royal Free, ONE (1) Year Priority Support, ONE (1) Year Free Upgrade and 30-Days Money Back Guarantee. 

  Developer License  allows  Single Developer  to create Unlimited Reports, deploy on Unlimited Servers and able deliver the work to Unlimited Clients. </a>
<!-- affiliate ads end -->
 If you haven't run Fooocus with Docker before, it will automatically build the Docker application based on the Fooocus code in the directory. This can take quite a while on some computers, so be patient and grab a coffee (or take a long lunch) while you wait.

 When it's done, you'll see that the Fooocus application has been created and started.

![Terminal output showing the Fooocus Docker container has started successfully](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/04/fooocus-4.png) 

 You will also be able to see the Fooocus container running in Docker Desktop.

![Docker Desktop showing a running container](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/04/fooocus-5.png) 

<!-- affiliate ads begin -->
<a href="https://ancheer.sjv.io/c/5597632/1657301/17326" target="_top" id="1657301"><img src="//a.impactradius-go.com/display-ad/17326-1657301" border="0" alt="" width="1920" height="933"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1657301/17326" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 From Docker Desktop, you can stop and start Fooocus (without having to use the terminal), or delete the container and all its data.

###  Step 4: Generate Some Images!

 Now that Fooocus is up and running in Docker, you can access it from your web browser. By default, it runs on port **7865** and can be accessed at the address **http://localhost:7865** ("[localhost](https://iphone-unlock.techidaily.com/how-do-you-unlock-your-apple-iphone-14-pro-learn-all-4-methods-drfone-by-drfone-ios/)" is the address your computer uses to access itself). You can click on a running container in the Docker Desktop interface to see which ports on localhost can be used to access it.

 Once the Fooocus interface has loaded, it's simply a matter of asking it to make some images!

![The Fooocus Stable Diffusion interface awaiting a user prompt](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/04/fooocus-6.png) 

 The first image might take a bit longer than others while the models Fooocus uses are prepared. Here's an example of an image generated using a simple Fooocus prompt: a photo of a helpful [How-To Geek](https://video-screen-grab.techidaily.com/new-in-2024-ranking-the-best-third-place-recording-tools-for-ipad/) surfing the net.

![The result of a Fooocus Stable Diffusion image prompt, showing a generated man in a suit, riding a surfboard](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/04/fooocus-7.png) 

 If you want to tweak the behavior or try out different styles, or look at the history of images you've generated, click the "Advanced" checkbox. Fooocus comes with a lot of options, and you can even use community-built models from sites like [CivitAI](https://education.civitai.com/generative-ai-art-with-fooocus-quickstart-guide/ "https://education.civitai.com/generative-ai-art-with-fooocus-quickstart-guide/").

 There is some NSFW content on CivitAI.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=38729081&QTY=1&AFFILIATE=108875&CART=1"><img src="https://website-prod.cache.wpscdn.com/img/wps-spreadsheet-free-excel-editor-online-offline-1x.93e269d.png" border="0">
WPS Office Premium ( File Recovery, Photo Scanning, Convert PDF)--Yearly</a>
<!-- affiliate ads end -->
##  AI Is a Whole New Set of Tools for Fun, Learning, and Productivity!

 Generative AI can make text, images, and videos based on your requests. It's a whole new set of tools that you can use for fun, learning, and productivity. It's also a cool way to get started with programming, for example, by [using Stable Diffusion with Python to generate images](https://some-skills.techidaily.com/tag-with-your-favorite-show-podcast-on-ig-for-2024/).

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
<li><a href="https://youtube-docs.techidaily.com/024-approved-maximizing-your-video-potential-through-smart-co-stars-selection/"><u>[New] 2024 Approved  Maximizing Your Video Potential Through Smart Co-Stars Selection</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-cutting-edge-strategies-for-iptv-capture-success/"><u>[New] Cutting-Edge Strategies for IPTV Capture Success</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-in-2024-expert-psd-overhaul-techniques/"><u>[New] In 2024, Expert PSD Overhaul Techniques</u></a></li>
<li><a href="https://extra-resources.techidaily.com/updated-compatibility-score-which-phones-work-with-gear-vr/"><u>[Updated] Compatibility Score  Which Phones Work with Gear VR?</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-in-2024-pioneering-playgrounds-of-action-adventure-classics-top-10/"><u>[Updated] In 2024, Pioneering Playgrounds of Action-Adventure Classics (Top 10)</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-screen-recorder-pro-for-windows-11-for-2024/"><u>[Updated] Screen Recorder Pro for Windows 11 for 2024</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/2024-approved-export-ppt-as-animated-film/"><u>2024 Approved  Export PPT as Animated Film</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/2024-approved-tweet-titans-social-networks-10-most-shared-posts/"><u>2024 Approved  Tweet Titans  Social Network’s 10 Most Shared Posts</u></a></li>
<li><a href="https://techidaily.com/best-fixes-for-samsung-galaxy-a15-5g-hard-reset-drfone-by-drfone-reset-android-reset-android/"><u>Best Fixes For Samsung Galaxy A15 5G Hard Reset | Dr.fone</u></a></li>
<li><a href="https://printer-issues.techidaily.com/brother-printer-not-working-solve-it-in-win1011/"><u>Brother Printer Not Working? Solve It in Win10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-the-apple-homepod-mini-exceptional-sound-intelligent-siri-functionality-and-more/"><u>Deciphering the Apple HomePod Mini – Exceptional Sound, Intelligent Siri Functionality, and More!</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/decoding-displacement-your-snapchat-time-turner-guide-for-2024/"><u>Decoding Displacement  Your Snapchat Time-Turner Guide for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/exploring-taskbar-upgrades-in-windows-11/"><u>Exploring Taskbar Upgrades in Windows 11</u></a></li>
<li><a href="https://fox-that.techidaily.com/fixing-siri-malfunctions-top-7-solutions-for-iphone-and-ipad-users/"><u>Fixing Siri Malfunctions - Top 7 Solutions for iPhone and iPad Users</u></a></li>
<li><a href="https://windows11.techidaily.com/fortifying-win-connections-for-uninterrupted-surfing/"><u>Fortifying Win Connections for Uninterrupted Surfing</u></a></li>
<li><a href="https://windows11.techidaily.com/future-proofing-windows-how-to-leverage-vivetool-advantages/"><u>Future-Proofing Windows: How to Leverage ViVeTool Advantages</u></a></li>
<li><a href="https://driver-download.techidaily.com/get-the-newest-windows-compatible-rtx-2060-super-gpu-drivers-now-available/"><u>Get the Newest Windows Compatible RTX 2060 Super GPU Drivers - Now Available</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-modify-the-visual-cues-in-windows-11-search/"><u>How to Modify the Visual Cues in Windows 11 Search</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-prevent-and-cure-system-settings-failures-in-win11/"><u>How to Prevent and Cure System Settings Failures in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-rectify-shaky-cursor-on-modern-windows/"><u>How to Rectify Shaky Cursor on Modern Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-resurrect-a-freeze-fixing-error-code-x-in-windows-11/"><u>How to Resurrect a Freeze: Fixing Error Code X in Windows 11</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-how-to-unlock-iphone-11-passcode-without-itunes-without-knowing-passcode-by-drfone-ios/"><u>In 2024, How to Unlock iPhone 11 Passcode without iTunes without Knowing Passcode?</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/in-2024-reverberation-artisan-collection/"><u>In 2024, Reverberation Artisan Collection</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-what-is-fake-gps-location-pro-and-is-it-good-on-nokia-g42-5g-drfone-by-drfone-virtual-android/"><u>In 2024, What is Fake GPS Location Pro and Is It Good On Nokia G42 5G? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/insider-secrets-the-edge-of-windows-for-gamers/"><u>Insider Secrets: The Edge of Windows for Gamers</u></a></li>
<li><a href="https://windows11.techidaily.com/insights-on-windows-portable-application-formats/"><u>Insights on Windows Portable Application Formats</u></a></li>
<li><a href="https://windows11.techidaily.com/keeping-taskmanager-above-all-windows/"><u>Keeping TaskManager Above All Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/masterclass-guide-to-overcoming-opengl-glitch-3/"><u>Masterclass Guide to Overcoming OpenGL Glitch #3</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-file-access-toggling-windows-11-filters/"><u>Mastering File Access: Toggling Windows 11 Filters</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-nat-type-adjustment-in-modern-windows-oses/"><u>Mastering NAT Type Adjustment in Modern Windows OSes</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-system-debugging-locating-and-resolving-error-codes-via-windows-command-prompt/"><u>Mastering System Debugging: Locating & Resolving Error Codes via Windows Command Prompt</u></a></li>
<li><a href="https://windows11.techidaily.com/mastering-windows-11-keys-best-offers/"><u>Mastering Windows 11 Keys: Best Offers</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-the-maze-finding-windows-11s-mac-addresses/"><u>Navigating the Maze: Finding Windows 11'S MAC Addresses</u></a></li>
<li><a href="https://windows11.techidaily.com/navigating-the-windows-arp-cache-world-and-purge-processes-129-chars-exceeds-limit-adjusted-to-fit-better-clearing-windows-arp/"><u>Navigating the Windows ARP Cache World and Purge Processes (129 Chars, Exceeds Limit, Adjusted to Fit Better: Clearing Windows ARP</u></a></li>
<li><a href="https://windows11.techidaily.com/old-habits-die-hard-reasons-for-sticking-with-windows-10/"><u>Old Habits Die Hard – Reasons for Sticking with Windows 10</u></a></li>
<li><a href="https://windows11.techidaily.com/preventing-unsolicited-terminal-window-flashes/"><u>Preventing Unsolicited Terminal Window Flashes</u></a></li>
<li><a href="https://windows11.techidaily.com/raising-the-roar-the-top-4-apps-to-boost-windows-decibels-over-limit/"><u>Raising the Roar: The Top 4 Apps to Boost Windows’ Decibels Over Limit</u></a></li>
<li><a href="https://windows11.techidaily.com/restoring-seamless-connectivity-with-fall-guys-windows-edition/"><u>Restoring Seamless Connectivity with Fall Guys (Windows Edition)</u></a></li>
<li><a href="https://windows11.techidaily.com/revive-your-pc-navigating-through-windows-8-options/"><u>Revive Your PC: Navigating Through Windows' 8 Options</u></a></li>
<li><a href="https://windows11.techidaily.com/solutions-for-overcoming-steam-permissions-in-windows-11/"><u>Solutions for Overcoming Steam Permissions in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-guide-unplugging-epic-from-win-11-pcs/"><u>Step-By Step Guide: Unplugging Epic From Win 11 PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-guide-for-removing-isdonedll-from-w11-pc/"><u>Step-By-Step Guide for Removing ISDone.dll From W11 PC</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-adding-outlook-preview-to-windows-devices/"><u>Step-by-Step: Adding Outlook Preview to Windows Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/stop-freezing-sheet-zoom-and-scroll-issues-in-excel-win/"><u>Stop Freezing Sheet Zoom & Scroll Issues in Excel (Win)</u></a></li>
<li><a href="https://windows11.techidaily.com/techniques-for-deactivating-hyper-v-win11/"><u>Techniques for Deactivating Hyper-V Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/the-essential-knowledge-of-command-line-nicknames/"><u>The Essential Knowledge of Command Line Nicknames</u></a></li>
<li><a href="https://windows11.techidaily.com/the-path-to-gaming-bliss-guide-to-drive-selection/"><u>The Path to Gaming Bliss: Guide to Drive Selection</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-windows-access-control-corruption-resolution/"><u>Troubleshooting Windows: Access Control Corruption Resolution</u></a></li>
<li><a href="https://windows11.techidaily.com/unchaining-the-microsoft-store-on-windows-11-devices/"><u>Unchaining the Microsoft Store on Windows 11 Devices</u></a></li>
<li><a href="https://techidaily.com/undelete-lost-contacts-from-nubia-red-magic-8s-pro-by-fonelab-android-recover-contacts/"><u>Undelete lost contacts from Nubia Red Magic 8S Pro.</u></a></li>
<li><a href="https://windows11.techidaily.com/unlock-default-windows-11-terminal-features/"><u>Unlock Default Windows 11 Terminal Features</u></a></li>
<li><a href="https://windows11.techidaily.com/unmasking-windows-remote-desktop-glitch-dark-screen/"><u>Unmasking Windows Remote Desktop Glitch: Dark Screen</u></a></li>
<li><a href="https://windows11.techidaily.com/unraveling-the-mystery-of-a-missing-graphics-driver/"><u>Unraveling the Mystery of a Missing Graphics Driver</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-the-cause-of-winmedia-error/"><u>Unveiling the Cause of WinMedia Error</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-the-hidden-truth-behind-windows-activation-error-0x8007251d/"><u>Unveiling the Hidden Truth Behind Windows Activation Error 0X8007251D</u></a></li>
<li><a href="https://driver-install.techidaily.com/update-nvidias-quadro-6000-firmware/"><u>Update NVIDIA's Quadro 6000 Firmware</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/will-pokemon-go-ban-the-account-if-you-use-pgsharp-on-oneplus-ace-3-drfone-by-drfone-virtual-android/"><u>Will Pokémon Go Ban the Account if You Use PGSharp On OnePlus Ace 3 | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/win-lol-skirting-startup-snags-and-stalls/"><u>Win: LOL – Skirting Startup Snags and Stalls</u></a></li>
</ul></div>
