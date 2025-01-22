---
title: Boosting Performance of Docker in WSL 2 on Windows Devices
date: 2025-01-18T19:24:07.719Z
updated: 2025-01-22T20:09:07.951Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Boosting Performance of Docker in WSL 2 on Windows Devices
excerpt: This Article Describes Boosting Performance of Docker in WSL 2 on Windows Devices
keywords: Docker WSL 2 Optimize,Enhance Docker Windows,Boost WSL2 Docker Efficiency,WSL2 Improve Docker Performance,Windows Devices Docker Accelerate,Speed Up WSL2 Docker,Maximize Docker on WSL2
thumbnail: https://thmb.techidaily.com/a688e86ffbdc3e471be20f57f8c10af5824b747637513c90eaa9668068fec723.jpg
---

## Boosting Performance of Docker in WSL 2 on Windows Devices

 The Windows Subsystem for Linux 2 is a phenomenal tool on Windows 10 and 11, and integrates with Docker seamlessly. As developers, it's essential to understand what these software offers and how you can make the most out of your Docker-WSL 2 setup.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/NC0rdKEQ98o?si=HYgqC8CxF_WTO5if" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/jpdGEJJwMLY?si=eKgXOPpNeYvYKcel" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Integrate VS Code with WSL 2

 Visual Studio Code is a popular IDE that’s loved due to its incredible features, community, and extensions. As a developer, the ability to use Visual Studio Code for app development on a Windows platform while also running those apps on a Linux kernel is an incredibly advantageous and almost unbelievable feature.

![wsl extension in VS Code](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/wsl-extension.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/W5aJC8okA8s?si=L2rnYAp-gmGlLQSf" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 When you integrate VS Code into the Windows Subsystem for Linux, you can take advantage of its specialized Linux kernel to enhance cross-platform compatibility. You can further streamline your workflow by utilizing the integrated terminal within VS Code with WSL 2.

 To [set up VS Code with WSL 2 on Windows](https://www.makeuseof.com/how-to-set-up-vs-code-with-wsl-2-windows-10-11/) , you can configure the**WSL** extension from the VS Code Marketplace and get things going.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/ZLb1ViO4WR8?si=g_aiHGNCd7eAvmDM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/L603QXgjb3I?si=sMYHfMGy2kNPSHPt" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://snapchat-videos.techidaily.com/new-2024-approved-tailor-your-vocal-expression-masterful-techniques-for-snapchat-voices/"><u>[New] 2024 Approved Tailor Your Vocal Expression Masterful Techniques for Snapchat Voices</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-in-2024-comprehensible-guide-to-high-quality-audios-on-youtube/"><u>[New] In 2024, Comprehensible Guide to High-Quality Audios on YouTube</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/updated-2024-approved-voice-driven-operation-platform-zero-price/"><u>[Updated] 2024 Approved Voice-Driven Operation Platform Zero Price</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/ed-essential-free-tools-convert-youtube-audio-to-mp3-on-iphone/"><u>[Updated] Essential Free Tools Convert YouTube Audio to MP3 on iPhone</u></a></li>
<li><a href="https://windows11.techidaily.com/accelerating-windows-11-app-launches/"><u>Accelerating Windows 11 App Launches</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-windows-services-that-dont-launch/"><u>Addressing Windows Services That Don't Launch</u></a></li>
<li><a href="https://windows11.techidaily.com/advanced-tips-for-adding-sound-in-snipping-tool-recordings-max-156/"><u>Advanced Tips for Adding Sound in Snipping Tool Recordings (Max 156)</u></a></li>
<li><a href="https://windows11.techidaily.com/beneath-the-surface-innocent-looking-apps-steal-speed-from-pcs/"><u>Beneath the Surface, Innocent-Looking Apps Steal Speed From PCs</u></a></li>
<li><a href="https://windows11.techidaily.com/clearing-the-obscure-fixing-white-out-screens-in-win1011/"><u>Clearing the Obscure: Fixing White Out Screens in WIN10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/distinguishing-key-features-of-exe-and-msi-formats/"><u>Distinguishing Key Features of EXE and MSI Formats</u></a></li>
<li><a href="https://windows11.techidaily.com/diving-deep-using-the-netstat-command-in-windows-11-os/"><u>Diving Deep: Using the Netstat Command in Windows 11 OS</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/24-the-beat-drops-highlighting-this-years-best-music-vids/"><u>In 2024, The Beat Drops Highlighting This Year's Best Music Vids</u></a></li>
<li><a href="https://win-amazing.techidaily.com/install-the-updated-lenovo-digital-camera-drivers-on-your-pc-running-windows-7/"><u>Install the Updated Lenovo Digital Camera Drivers on Your PC Running Windows 7</u></a></li>
<li><a href="https://fake-location.techidaily.com/spoofing-life360-how-to-do-it-on-samsung-galaxy-m34-drfone-by-drfone-virtual-android/"><u>Spoofing Life360 How to Do it on Samsung Galaxy M34? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/supercharge-your-windows-11-search-with-these-top-tips/"><u>Supercharge Your Windows 11 Search with These Top Tips</u></a></li>
<li><a href="https://app-tips.techidaily.com/the-misconception-among-smbs-about-not-needing-cyber-insurance-despite-potential-risks-perspectives-by-zdnet/"><u>The Misconception Among SMBs About Not Needing Cyber Insurance Despite Potential Risks - Perspectives by ZDNET</u></a></li>
</ul></div>

