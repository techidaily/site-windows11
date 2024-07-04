---
title: Boosting Performance of Docker in WSL 2 on Windows Devices
date: 2024-07-03T11:16:59.840Z
updated: 2024-07-04T11:16:59.840Z
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
<li><a href="https://windows11.techidaily.com/unblock-your-computers-usb-hub-windows-fix-guide/"><u>Unblock Your Computer's USB Hub: Windows Fix Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/what-is-ftdibussys-on-windows-and-why-does-it-disable-memory-integrity/"><u>What Is ftdibus.sys on Windows and Why Does It Disable Memory Integrity?</u></a></li>
<li><a href="https://windows11.techidaily.com/monitoring-for-failed-windows-logins-a-security-checkers-guide/"><u>Monitoring for Failed Windows Logins: A Security Checker's Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-wins-system-alert-messages-in-windows-1011/"><u>Correcting WINS System Alert Messages in Windows 10/11</u></a></li>
<li><a href="https://windows11.techidaily.com/decoding-hardware-utilization-in-windows-11/"><u>Decoding Hardware Utilization in Windows 11</u></a></li>
<li><a href="https://windows11.techidaily.com/tactics-for-finding-hidden-regedit-command/"><u>Tactics for Finding Hidden Regedit Command</u></a></li>
<li><a href="https://windows11.techidaily.com/accelerating-your-gaming-experience-update-radeon-drivers-now/"><u>Accelerating Your Gaming Experience: Update Radeon Drivers Now</u></a></li>
<li><a href="https://windows11.techidaily.com/nullify-specification-shortfalls-alerts-in-win11/"><u>Nullify Specification Shortfalls Alerts in Win11</u></a></li>
<li><a href="https://windows11.techidaily.com/eliminating-pubg-save-problems-on-windows-systems/"><u>Eliminating PUBG Save Problems on Windows Systems</u></a></li>
<li><a href="https://windows11.techidaily.com/building-your-signature-input-scheme-on-win11/"><u>Building Your Signature Input Scheme on Win11</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-data-from-vivo-v27-pro-to-other-android-devices-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Data from Vivo V27 Pro to Other Android Devices? | Dr.fone</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-fix-oem-unlock-missing-on-nokia-c12-plus-by-drfone-android/"><u>How To Fix OEM Unlock Missing on Nokia C12 Plus?</u></a></li>
<li><a href="https://youtube-help.techidaily.com/new-simplified-techniques-for-reordering-yt-videos/"><u>[New] Simplified Techniques for Reordering YT Videos</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-cross-platform-streaming-techniques-from-youtube-to-30plus-platforms-for-2024/"><u>[New] Cross-Platform Streaming Techniques  From YouTube to 30+ Platforms for 2024</u></a></li>
<li><a href="https://howto.techidaily.com/9-solutions-to-fix-infinix-note-30-vip-system-crash-issue-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>9 Solutions to Fix Infinix Note 30 VIP System Crash Issue | Dr.fone</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-excellence-in-offline-speech-recognition-software-for-2024/"><u>[New] Excellence in Offline Speech Recognition Software for 2024</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/updated-in-2024-6-instant-mp4-to-gif-online-tools-for-you/"><u>Updated In 2024, 6 Instant Mp4 to GIF Online Tools for You</u></a></li>
<li><a href="https://some-tips.techidaily.com/in-2024-the-pinnacle-of-personal-data-holdings/"><u>In 2024, The Pinnacle of Personal Data Holdings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revamping-gpos-a-step-by-step-guide-for-windows-users/"><u>Revamping GPOs: A Step-by-Step Guide for Windows Users</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-in-2024-best-ubuntu-video-editors-free-and-fabulous-options/"><u>New In 2024, Best Ubuntu Video Editors Free and Fabulous Options</u></a></li>
</ul></div>
