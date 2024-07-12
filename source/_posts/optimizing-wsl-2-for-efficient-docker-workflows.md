---
title: Optimizing WSL 2 for Efficient Docker Workflows
date: 2024-07-11T21:21:33.287Z
updated: 2024-07-12T21:21:33.287Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Optimizing WSL 2 for Efficient Docker Workflows
excerpt: This Article Describes Optimizing WSL 2 for Efficient Docker Workflows
keywords: Docker Workflow Optimization,WSL Docker Efficiency,WSL 2 Performance,Efficient WSL Docker,Improve WSL 2 Speed,Streamlined Docker in WSL,Enhance WSL for Dockers
thumbnail: https://thmb.techidaily.com/f247ef7a94b421ec0fcafea579ee074c3050225ad0c19a044a9d73401964e5e7.jpg
---

## Optimizing WSL 2 for Efficient Docker Workflows

 The Windows Subsystem for Linux 2 is a phenomenal tool on Windows 10 and 11, and integrates with Docker seamlessly. As developers, it's essential to understand what these software offers and how you can make the most out of your Docker-WSL 2 setup.

## What Is Docker?

 Docker is an open-source platform that allows developers to efficiently build, deploy and run their applications within a container. All dependencies are bundled up so your project can easily be deployed in any environment.

 Docker is very popular among many containerization platforms because it is reliable, functional, and highly scalable. It runs on the Docker engine, an essential DevOps tool that provides a clean and lightweight environment for testing and deployment. Docker is similar to a virtual machine but virtualizes the operating system rather than the underlying hardware.

![Microservice architecture](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/microservice-architecture.jpg)

 For software developers, Docker streamlines workflow by creating individual containers for different microservices that include the necessary dependencies, libraries, and configurations. Each microservice container is isolated and individually scalable.

## How to Use Docker on WSL 2

 Docker is compatible with all major operating systems, such as Windows, macOS, and Linux. If you’re on Windows 10 or 11, you can use Docker via Docker Desktop and [integrate it with the Windows Subsystem for Linux 2](https://www.makeuseof.com/how-to-install-docker-windows-10-11/) for improved performance. You can download Docker Desktop for Windows from the [official Docker website](https://www.docker.com/products/docker-desktop/) .

![newly built image on docker](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/newly-built-image-on-docker.jpg)

 The Windows Subsystem for Linux (WSL) is a valuable feature that allows Windows users to run Linux distributions like Ubuntu and Kali without setting up a virtual machine or dual-boot.

 This also means that [Windows users can directly use Linux command-line tools](https://www.makeuseof.com/run-linux-commands-windows-wsl-2/) , applications, and utilities without extra installation steps. The most recent version of WSL, WSL 2, provides greater stability and a dedicated Linux kernel.

 Since Docker containers are robust, you can even configure them to host your server; nginx docker containers are commonly used as web servers. Additionally, you can use Docker in several other ways:

* Run Linux distros easily
* Set up a web server for learning or testing purposes
* Portable deploy applications
* Bundle the application into a single image file
* Simplified CI/CD pipeline

 You must become familiar with the best practices for utilizing Docker with Windows Subsystem for Linux 2, just like you would with any other platform or tool. As a developer, I can say from personal experience that you'll become much more productive and efficient once you integrate the following tips into your workflow.

## 1\. Integrate VS Code with WSL 2

 Visual Studio Code is a popular IDE that’s loved due to its incredible features, community, and extensions. As a developer, the ability to use Visual Studio Code for app development on a Windows platform while also running those apps on a Linux kernel is an incredibly advantageous and almost unbelievable feature.

![wsl extension in VS Code](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/wsl-extension.jpg)

 When you integrate VS Code into the Windows Subsystem for Linux, you can take advantage of its specialized Linux kernel to enhance cross-platform compatibility. You can further streamline your workflow by utilizing the integrated terminal within VS Code with WSL 2.

 To [set up VS Code with WSL 2 on Windows](https://www.makeuseof.com/how-to-set-up-vs-code-with-wsl-2-windows-10-11/) , you can configure the**WSL** extension from the VS Code Marketplace and get things going.

## 2\. Utilize the WSL 2 File System

 To properly run your Docker containers, it's vital that you rely on the file system of your WSL 2 distro and not heavily depend on the native Windows file system. Throughout my experience of working with Docker containers on WSL 2, I’ve discovered it’s better to store your project files within WSL.

## 3\. Use Native Linux Scripts

 Many containerized projects that you’ll work on will probably come with scripts for automation on Linux. Typically, these scripts are first developed for Linux, and Windows developers aren’t a priority.

 With WSL 2, your entire team can use the same Linux automation scripts, and you don’t have to worry about maintaining Windows-compatible automation scripts for your team.

## 4\. Configure BuildKit for Improved Security and Performance

 BuildKit is an open-source toolkit that improves the traditional Docker build process in terms of performance and security; it's directly integrated with Docker, so you don’t need to install it separately.

 When you enable the**BuildKit** by default, you’re making sure that your containers are being built with the BuildKit toolkit, giving you better security, concurrency, flexibility, and caching.

 To enable BuildKit by default, you should make the following changes to the \~/.profile config file:

`export DOCKER_BUILDKIT=1.`

## 5\. Set Up Resource Limits

 When you integrate the WSL 2 backend with Docker Desktop, you give Docker access to all your CPU resources. Doing so helps improve performance for containers that are resource heavy.

 However, in some cases, a container might allocate a lot of excess memory, causing critical OS processes to crash. You’re more likely to experience this when using database containers or a caching microservice.

 Fortunately, you can configure Docker containers to limit the system memory and CPU usage. You should always be careful while configuring the system memory, even a minor mistake can have significant consequences. You can refer to the [official Docker documentation](https://docs.docker.com/config/containers/resource%5Fconstraints/) for a more detailed guide on limiting the memory and CPU resources consumed by a Docker container.

## 6\. Recover Cached Memory

 If you’re running a Docker container in WSL 2, its memory should be freed once the container terminates. Unfortunately, the operating system kernel tends to maintain data in the cache; this means that the effective memory reclaimed by the WSL 2 won’t be sufficient.

 You can recover all of the memory that is unnecessarily being utilized as a cache by running the following command via root in WSL 2:

`echo 1 > /proc/sys/vm/drop_caches`

## Get Smarter With WSL 2

 The WSL 2 is the best feature for Windows-based developers, completely changing how developers use Docker. Developers must understand the best practices for using Docker with WSL to improve performance, security, and workflow flexibility.

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
<li><a href="https://windows11.techidaily.com/perfectly-pivoting-to-windows-11-in-place-strategies/"><u>Perfectly Pivoting to Windows 11: In-Place Strategies</u></a></li>
<li><a href="https://windows11.techidaily.com/optimize-visual-quality-dpi-settings-guide-for-windows-11/"><u>Optimize Visual Quality: DPI Settings Guide for Windows 11</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-data-after-switching-from-nubia-z50s-pro-to-latest-samsung-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Data After Switching From Nubia Z50S Pro to Latest Samsung | Dr.fone</u></a></li>
<li><a href="https://fox-links.techidaily.com/new-silent-symphony-a-compendium-of-top-speech-to-text-tools/"><u>[New] Silent Symphony  A Compendium of Top Speech-to-Text Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/swift-solutions-for-dotnet-health-in-pcs-max-156/"><u>Swift Solutions for DotNet Health in PCs (Max 156)</u></a></li>
<li><a href="https://techidaily.com/what-you-need-to-know-to-improve-your-xiaomi-redmi-note-13-pro-5g-hard-reset-drfone-by-drfone-reset-android-reset-android/"><u>What You Need To Know To Improve Your Xiaomi Redmi Note 13 Pro 5G Hard Reset | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-troubleshooting-guide-no-audio-output-error/"><u>Quick Troubleshooting Guide: No Audio Output Error</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-can-we-unlock-our-vivo-s18e-phone-screen-by-drfone-android/"><u>In 2024, How Can We Unlock Our Vivo S18e Phone Screen?</u></a></li>
<li><a href="https://windows11.techidaily.com/unseen-windows-firewall-protection-sectors-demystified/"><u>Unseen Windows Firewall Protection Sectors Demystified</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-sluggishness-in-windows-discord-app/"><u>Overcoming Sluggishness in Windows Discord App</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/new-2024-approved-mastering-color-in-final-cut-pro-a-step-by-step-guide/"><u>New 2024 Approved Mastering Color in Final Cut Pro A Step-by-Step Guide</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/comprehensive-guide-to-io-screen-capture-capabilities/"><u>Comprehensive Guide to IO Screen Capture Capabilities</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-how-to-record-with-flair-on-windows-10/"><u>[Updated] How to Record with Flair on Windows 10</u></a></li>
<li><a href="https://windows11.techidaily.com/winning-the-angle-game-rotate-images-in-6-steps-w11/"><u>Winning the Angle Game: Rotate Images in 6 Steps W11</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-repeated-sign-in-requests-for-team-collaboration-software/"><u>Overcoming Repeated Sign-In Requests for Team Collaboration Software</u></a></li>
<li><a href="https://windows11.techidaily.com/overcoming-directx-update-issues-on-windows/"><u>Overcoming DirectX Update Issues on Windows</u></a></li>
<li><a href="https://ios-location-track.techidaily.com/in-2024-top-6-appsservices-to-trace-any-apple-iphone-12-pro-max-location-by-mobile-number-drfone-by-drfone-virtual-ios/"><u>In 2024, Top 6 Apps/Services to Trace Any Apple iPhone 12 Pro Max Location By Mobile Number | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/swiftly-overcoming-windows-access-denied-blunders/"><u>Swiftly Overcoming Windows Access Denied Blunders</u></a></li>
<li><a href="https://windows11.techidaily.com/stop-discords-auto-activation-at-pc-boot-sequence/"><u>Stop Discord's Auto-Activation at PC Boot Sequence</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-frustration-with-non-responsive-photoshop/"><u>Tackling Frustration with Non-Responsive Photoshop</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-in-2024-mastering-obs-installation-and-usage-on-mac-systems/"><u>[Updated] In 2024, Mastering OBS  Installation and Usage on Mac Systems</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/updated-in-2024-methods-for-designing-audio-gradual-reduction-effect/"><u>Updated In 2024, Methods for Designing Audio Gradual Reduction Effect</u></a></li>
<li><a href="https://windows11.techidaily.com/boosting-download-velocity-in-steam-fending-off-drops/"><u>Boosting Download Velocity in Steam: Fending Off Drops</u></a></li>
<li><a href="https://windows11.techidaily.com/the-insiders-guide-to-bluescreenview-execution/"><u>The Insider’s Guide to BlueScreenView Execution</u></a></li>
<li><a href="https://windows11.techidaily.com/boosting-speed-with-wordpad-embedding-keyboard-macros-into-windows-menu/"><u>Boosting Speed with WordPad: Embedding Keyboard Macros Into Windows Menu</u></a></li>
<li><a href="https://windows11.techidaily.com/techniques-to-break-the-bond-onedrive-from-ms-account-on-windows/"><u>Techniques to Break the Bond: OneDrive From MS Account on Windows</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ed-2024-approved-explore-best-asmr-apps-both-sides-of-the-os/"><u>[Updated] 2024 Approved  Explore Best ASMR Apps, Both Sides of the OS</u></a></li>
<li><a href="https://fox-info.techidaily.com/new-discover-a-broad-array-top-15-cams-not-like-gopro/"><u>[New] Discover a Broad Array  Top 15 Cams Not Like GoPro</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-high-quality-8-android-video-callers-for-groups-above-four/"><u>[Updated] High-Quality 8 Android Video Callers for Groups Above Four</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-low-end-system-failures-due-to-intel-graphics-requirements/"><u>Tackling Low-End System Failures Due to Intel Graphics Requirements</u></a></li>
<li><a href="https://windows11.techidaily.com/method-rectifying-disks-not-available-on-windows-pcs/"><u>Method: Rectifying Disks Not Available on Windows PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-steam-game-locks-in-windows-environment/"><u>Resolving Steam Game Locks in Windows Environment</u></a></li>
<li><a href="https://windows11.techidaily.com/mastery-on-the-horizon-learning-classic-diablo/"><u>Mastery on the Horizon: Learning Classic Diablo</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-in-2024-easy-recording-guide-powerpoints-and-webcams-unite/"><u>[Updated] In 2024, Easy Recording Guide  PowerPoints & Webcams Unite</u></a></li>
<li><a href="https://windows11.techidaily.com/troubleshooting-eliminating-enter-usernamepassword-alerts-in-windows/"><u>Troubleshooting: Eliminating 'Enter Username/Password' Alerts in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/remedying-the-process-termination-failure-error-window/"><u>Remedying the 'Process Termination Failure' Error Window</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-pro-tips-for-crafting-and-sharing-content-on-reddit/"><u>2024 Approved  Pro Tips for Crafting & Sharing Content on Reddit</u></a></li>
<li><a href="https://windows11.techidaily.com/automate-your-photo-display-craft-the-ultimate-win11-slideshow/"><u>Automate Your Photo Display - Craft the Ultimate Win11 Slideshow</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/beyond-rules-the-real-goal-of-learning-languages/"><u>Beyond Rules: The Real Goal of Learning Languages</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-forgot-pattern-lock-heres-how-you-can-unlock-itel-s23-pattern-lock-screen-by-drfone-android/"><u>In 2024, Forgot Pattern Lock? Heres How You Can Unlock Itel S23 Pattern Lock Screen</u></a></li>
<li><a href="https://video-capture.techidaily.com/perfecting-sound-capture-reviewed-mac-compatible-recorders-for-2024/"><u>Perfecting Sound Capture  Reviewed Mac-Compatible Recorders for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/understanding-the-best-encoding-methods-on-pc/"><u>Understanding the Best Encoding Methods on PC</u></a></li>
<li><a href="https://windows11.techidaily.com/reinforce-internet-ties-for-your-windows-devices-amid-sluggishness/"><u>Reinforce Internet Ties for Your Windows Devices Amid Sluggishness</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-from-good-to-great-a-vlog-on-incredible-instagrams-for-2024/"><u>[New] From Good to Great  A Vlog on Incredible Instagrams for 2024</u></a></li>
<li><a href="https://audio-editing.techidaily.com/updated-ideal-soundtrack-choices-selecting-songs-to-elevate-your-montage-masterpiece-for-2024/"><u>Updated Ideal Soundtrack Choices Selecting Songs to Elevate Your Montage Masterpiece for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/say-goodbye-to-lag-how-to-fix-warhammer-40k-delays-on-your-pc/"><u>Say Goodbye to Lag: How to Fix Warhammer 40K Delays on Your PC</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-fix-unresponsive-phone-touchscreen-of-vivo-y100i-power-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Fix Unresponsive Phone Touchscreen Of Vivo Y100i Power 5G | Dr.fone</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/first-steps-to-successful-vlogging-essentials-for-2024/"><u>First Steps to Successful Vlogging  Essentials for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/simplifying-app-installations-in-windows-11-using-winstall/"><u>Simplifying App Installations in Windows 11 Using Winstall</u></a></li>
<li><a href="https://windows11.techidaily.com/mitigating-critical-programming-issues-in-roblox/"><u>Mitigating Critical Programming Issues in Roblox</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/2024-approved-join-the-giggle-roll-and-tearful-talks-on-instagram-memes/"><u>2024 Approved  Join the Giggle-Roll and Tearful Talks on Instagram Memes</u></a></li>
<li><a href="https://windows11.techidaily.com/steady-your-pc-controlling-high-cpu-load-with-windows-resource-tool/"><u>Steady Your PC: Controlling High CPU Load With Window's Resource Tool</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-10-best-intro-maker-apps-for-iphone-and-android-for-2024/"><u>[New] 10 Best Intro Maker Apps for iPhone and Android for 2024</u></a></li>
<li><a href="https://windows11.techidaily.com/reworking-default-view-of-task-manager-in-win11/"><u>Reworking Default View of Task Manager in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-customizing-your-windows-11-notepad-appearance/"><u>Step-by-Step: Customizing Your Windows 11 Notepad Appearance</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-ultimate-mic-selection-for-vloggers-and-streamers/"><u>[New] Ultimate Mic Selection for Vloggers and Streamers</u></a></li>
<li><a href="https://windows11.techidaily.com/tailored-screenscape-designing-distinctive-displays-on-each-window-of-win-1011/"><u>Tailored Screenscape: Designing Distinctive Displays on Each Window of Win 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/the-art-of-fine-tuning-windows-11-alerts/"><u>The Art of Fine-Tuning Windows 11 Alerts</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/how-to-unlock-apple-iphone-x-passcode-without-computer-drfone-by-drfone-ios/"><u>How to Unlock Apple iPhone X Passcode without Computer? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/optimize-storage-effortlessly-quick-pathways-into-windows-disk-manager/"><u>Optimize Storage Effortlessly: Quick Pathways Into Windows Disk Manager</u></a></li>
<li><a href="https://windows11.techidaily.com/resolve-cannot-open-error-on-closed-folders-in-microsoft-mail-for-pc/"><u>Resolve Cannot Open Error on Closed Folders in Microsoft Mail for PC</u></a></li>
<li><a href="https://windows11.techidaily.com/procedures-to-disregard-the-your-license-will-end-alert/"><u>Procedures to Disregard the Your License Will End Alert</u></a></li>
</ul></div>
