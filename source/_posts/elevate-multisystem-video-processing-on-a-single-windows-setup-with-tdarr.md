---
title: Elevate Multisystem Video Processing on a Single Windows Setup with Tdarr
date: 2024-07-29T04:27:00.617Z
updated: 2024-07-30T04:27:00.617Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Elevate Multisystem Video Processing on a Single Windows Setup with Tdarr
excerpt: This Article Describes Elevate Multisystem Video Processing on a Single Windows Setup with Tdarr
keywords: Windows Video Elevation,Tdarr Multisystem Pro,Single-Pc Video Tech,Streamline Windows Processing,Tdarr for Single Setup,Unified Video System,Simplified Video Workflow
thumbnail: https://thmb.techidaily.com/64cbdaa1aef5615ff39347b9db4c0280ec8c3ce520d27154774aa65c3ef13831.jpg
---

## Elevate Multisystem Video Processing on a Single Windows Setup with Tdarr

 Transcoding is one of the most demanding tasks for your PC, translating to a time-consuming process for the end user. Encoding a single video can take days, depending on the PC's specifications, the codec used, and the source video's characteristics. That's where multiple PCs and an app like Tdarr can be a lifesaver.

 If you have more than one PC in your home network, why not let them lend a helping hand when transcoding media? Tdarr can turn all your PCs into nodes of the same networked transcoder, resulting in much faster audio and video encoding. Let's see how.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4576829&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/9e740b84bb48a64dde25061566299467/products/copy_1_jp_box_big.png" border="0">Jet Profiler for MySQL, Enterprise Version： Jet Profiler for MySQL is real-time query performance and diagnostics tool for the MySQL database server. Its detailed query information, graphical interface and ease of use makes this a great tool for finding performance bottlenecks in your MySQL databases. </a>
<!-- affiliate ads end -->
## What Is Tdarr?

 Sonarr, Radarr, and their "siblings" were created to assist with media piracy. However, unlike the other apps in the pirate-y "...arr" family, Tdarr differs in two crucial ways, justifying why we've decided to use it for this guide:

* It doesn't specialize in "granting access to illegal content" like (most of) its siblings, but in modifying the media files you already own.
* It trivializes the creation of mass-video-encoding networks. In the past, few, apart from professionals in the field, like Netflix, could pull this off successfully.

 After setting it up, Tdarr can help you "unify" your media collection, whose files are spread on various devices. You can always [compress videos to reduce their file size](https://www.makeuseof.com/compress-video-file/) yourself, but why not completely delegate the task to Tdarr?

1. You can configure Tdarr to "pull" your media files from all your devices.
2. It can then re-encode them to formats appropriate for each of them.
3. Finally, it can store the results in a shared folder or "push" them to each device on your local network.

 Best of all, after you set it up, it works automatically while taking advantage of the hardware capabilities of the "nodes" in your network: Windows desktop PCs, Linux servers, ARM-based Chromebooks, or your shiny new Mac.

 For this article, we'll see how you can set it up and use it on two Windows-based PCs on the same home network.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4715391&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/7f687767ccf20fcea1c9dc4a5adc2326/Digisigner_banner_728_x_90_color_version.png" border="0"></a>
<!-- affiliate ads end -->
## How to Install Tdarr

 Despite being a relatively complicated collection of separate scripts and tools, Tdarr's installation is straightforward.

1. Start by downloading the appropriate version of the application for your platform from [Tdarr's official GitHub page](https://GitHub.com/HaveAGitGat/Tdarr).
2. Extract the downloaded zip archive and run the Tdarr **updater** app.
3. Windows protection might warn you that you are trying to run an unrecognized application. Click on **More info** to allow the app to run.
4. Click on **Run anyway** to acknowledge that you want to run an application created "by an unknown publisher".  
![Tdarr Install App Run Anyway](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/tdarr-install-app-run-anyway.jpg)
5. Allow the Tdarr updater to download everything needed by the application. If you see any mention that a connection failed, grant the Tdarr updater access to the Internet through your firewall.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=22741618&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.diskpart.com/resource/images/index/dp-index-img-banner-people@2x.png" border="0">Easy and Safe Partition Software & Hard Disk Manager</a>
<!-- affiliate ads end -->
![Tdarr Downloading Necessary Data](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/tdarr-downloading-necessary-data.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4599951&QTY=1&AFFILIATE=108875&CART=1"><iframe width="864" height="500" src="https://www.youtube.com/embed/jVnfr5HudQw" title="The Latest and Easiest Solution to Remove Kindle DRM on Windows (without Degrading)" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
Epubor Ultimate for Win：Helps you read books anywhere, including the best eBook Converter + eBook DRM Removal functions.</a>
<!-- affiliate ads end -->
### Tdarr's Hardware Requirements

 You can run the Tdarr server and the node software on any PC and access its interface through almost any browser. However, your hardware's performance and features can significantly affect encoding speeds.

 For example, a node running on a modern AMD Ryzen CPU will encode the same video in a blink compared to a ten-year-old Intel Celeron.

 Another node, using Nvidia's **NVEnc** hardware encoder for transcoding, will, in turn, be much faster than the AMD Ryzen CPU, but will also produce lower quality or larger files.

 So, if you find Tdarr's encoding too slow, you have two options:

* Try a less demanding codec or one that's "hardware accelerated" by your hardware.
* Upgrade to better hardware.

 Apart from that, you can run Tdarr even on a ten-year-old laptop if you can tolerate slow encoding speeds.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4713565&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/uppic/audible-converter-interface.png" border="0">Epubor Audible Converter for Mac： Download and convert Audible AAXC/AA/AAX to MP3 with 100% original quality preserved.</a>
<!-- affiliate ads end -->
### What About Tdarr's Codecs?

 We won't go into detail about what codecs are and how they work. However, we must mention that the codecs and encoders you choose are the most important factor for Tdarr's encoding performance and quality of produced results.

* Newer Codecs come with better quality-to-bitrate ratios but also higher hardware requirements.
* Hardware encoders can dramatically boost performance but also produce lower quality/larger files than software encoders (when using similar settings).

 With the above in mind, here's a list of the codecs worth using with Tdarr for re-encoding your media files. The closer a codec is to the top, the better the output quality, the higher its requirements, and the slower the encoding time.

1. AV1
2. H.265/HEVC
3. VP9
4. H.264/AVC
5. AV1/H.265 GPU-assisted Encoding
6. H.264 GPU-Assisted Encoding
7. MPEG4, DivX, Xvid
8. MPEG2

## How to Configure Tdarr

 Tdarr's core is its server, which provides a browser-accessible interface for the app, manages media, and orchestrates encoding among various nodes. The server doesn't do any encoding on its own. For that, it needs at least one node.

 Each node can have its own configuration and run locally on your PC or another computer on the same network. Nodes are responsible for media analysis, health checks, re-encoding, etc.

 The server controls all nodes, how they act on media, and manages files.

 Tdarr's nodes come pre-configured for running on the "local" PC without requiring a network. Thus, if you only plan to use Tdarr on a single PC, you only have to configure its server (apart from minor node tweaks).

### Configuring Your Tdarr Server

 For this article, we'll see how you can configure Tdarr Server from scratch without importing an existing media collection. Have you got a media library set up? You can modify the paths we'll use to point to your existing folders to have Tdarr process and re-encode them.

1. To configure Tdarr for a single computer, enter the **Tdarr Server** folder created by Tdarr's updater and run the **Tdarr Server app**.
2. As with the updater, you will probably have to allow it access through your firewall.
3. Tdarr's page didn't open automatically in your default browser? Enter the following in your browser's address bar: "localhost:8265/", and press **Enter** to visit Tdarr's web-based GUI. We suggest you **bookmark** it for easier access in the future.  
![Tdarr Change Log](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/tdarr-change-log.jpg)
4. If you don't like how Tdarr's page looks, you can change its theme from the **Options** page.
5. Scrolling down on the same page, you'll find a series of **Resolution boundaries** fields. Those allow you to set custom resolutions for your media.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4728277&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/f7f07e7dab09533bc71247a5b29a7373/products/1_iDeviceMessageBox.png" border="0"></a>
<!-- affiliate ads end -->
![Tdarr Options Define Resolution Boundary Crop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/tdarr-options-define-resolution-boundary-crop.jpg)

1. For example, since I only have access to **Full HD** screens, I've set "**1920**" as the width in the **Width Max** field of all resolutions above 1080p and their height as "**1188**" in their respective **Height Max** fields. This way, Tdarr will never re-encode media at a higher resolution than the native Full HD (1920 x 1080) of my monitors, producing much smaller files more quickly than if it had to deal with higher resolutions.  
<!-- affiliate ads begin -->
<a href="https://electronicx.pxf.io/c/5597632/1872496/14483" target="_top" id="1872496"><img src="//a.impactradius-go.com/display-ad/14483-1872496" border="0" alt="" width="750" height="625"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1872496/14483" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Tdarr Options Custom Resolution Boundary Crop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/tdarr-options-custom-resolution-boundary-crop.jpg)
2. You need at least one library for your media, so visit the **Libraries** page and click the **Library +** button to create one.
3. Type any name you wish in the field stating "**Library Name**".
4. Fire up your favorite file explorer. Choose where you want to keep your media and create a folder. For this article, we used a folder named "**Videos**" at the root of the system "C" drive.
5. Create three subfolders inside that folder. For ease of use, we've named them "**Incoming**", "**Ready**", and "**Temporary**". "Incoming" is where we will drop any unprocessed files for Tdarr to check out. "Temporary" is the folder Tdarr will use while processing files. "Ready" is where Tdarr will output processed files.  
<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=2069351&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-24_%282%29.jpg" border="0"></a>
<!-- affiliate ads end -->
![Tdarr Incoming Ready Temporary Folders](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/tdarr-incoming-ready-temporary-folders.jpg)
6. Go back to Tdarr's interface, move to the **Libraries** page, select your library, and if not visible on your screen, scroll down to find the **Source** tab. Click on it and enter the full path to your Incoming folder in the **Source** field below.  
![Tdarr Define Library Source Crop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/tdarr-define-library-source-crop.jpg)
7. Move to the **Transcode cache** tab and enter the full path to your "Temporary" folder in the **Cache** field.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4712430&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/c404a5adbf90e09631678b13b05d9d7a/products/dlnow_256.png" border="0">DLNow Video Downloader</a>
<!-- affiliate ads end -->
![Tdarr Set Transcode Cache to Temporary Folder Crop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/tdarr-set-transcode-cache-to-temporary-folder-crop.jpg)
8. Finally, move to the **Output folder**, and as you might have guessed, enter the full path to your "Ready" folder in the **Output** field.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4940312&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/333ac5d90817d69113471fbb6e531bee/sps-partnership-728x90eng.png" border="0"></a>
<!-- affiliate ads end -->
![Tdarr Point Output Folder to Ready Folder Path Copy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/tdarr-point-output-folder-to-ready-folder-path-copy.jpg)
9. Click the switch next to **Output Folder** on that tab to have Tdarr use the Incoming and Ready folders as Input and Output. If you don't do that, Tdarr will store everything in the Incoming folder. If you've got many media files, that can quickly get messy.

 If you wish, you can control the rate at which Tdarr scans the Incoming folder for new files. To do that, move to your library's **Source** tab, scroll down a bit, and change the number in the **Folder watch scan interval** field under **Folder watch settings**.

 Similarly, right below, you can tell it to run an hourly scan and define how many **File scanner threads** that will use. If you store your media on NVMe or SSD drives, increasing the number of File scanner threads can boost performance.

 Older mechanical HDDs, though, take a significant hit in performance when trying to access files in parallel, so it's best not to exceed the default value of "**2**" for those. You can also enable the option to **Hold files after scanning** and define how long (in seconds) those files will remain locked to ensure other apps won't interfere with them.

 Your library's **Filters** tab lets you define resolutions and codecs you'd prefer to skip. If, for example, you want Tdarr only to **downscale** videos, you can enter all the popular lower resolutions up to your monitor's native resolution (like "360p", "720p", and "1080p"), separated by commas in the **Resolutions to skip field**.

![Tdarr Library Filters Crop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/tdarr-library-filters-crop.jpg)

 The **Codecs to skip** field works similarly. For example, if you type "**AV1, HEVC**" in that field, Tdarr won't try re-encoding video files already compressed with those codecs.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4530091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pearlmountainsoft.com/n_img/product/cit_win/banScrn.jpg" border="0">CollageIt Pro</a>
<!-- affiliate ads end -->
![Tdarr Library Filter Skip Code Crop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/tdarr-library-filter-skip-code-crop.jpg)

 To have Tdarr process your files, it will have to watch the incoming folder to detect changes (AKA: new files). For that, visit your library's **Source** tab and flick the switch next to **Folder watch** to the right.

![Tdarr Library Source Enable Folder Watch Crop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/tdarr-library-source-enable-folder-watch-crop.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4600113&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/drm-removal-feature2.png" border="0">Any DRM Removal for Win：Remove DRM from Adobe, Kindle, Sony eReader, Kobo, etc, read your ebooks anywhere.</a>
<!-- affiliate ads end -->
## Customizing Tdarr's Nodes & Encoding

 Tdarr requires at least one active node to act on your media, so it's time to turn our attention to them.

1. With your Tdarr server still active, to add a node to it, enter the **Tdarr node** folder created by the Tdarr updater and run the **Tdarr node app** you'll find within it.
2. You will see a notification on Tdarr's interface web interface page that a node was **registered**.  
![Tdarr Node Connected to Server](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/tdarr-node-connected-to-server.jpg)
3. To test things out, place a media file in your incoming folder.  
![Tdarr Place Video into Incoming Folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/tdarr-place-video-into-incoming-folder.jpg)
4. Move to Tdarr's main page (named "Tdarr") and scroll to the bottom, under **Status**, to find your library. Soon you will see the file you added to your Incoming folder appear there.  
<!-- affiliate ads begin -->
<a href="https://otszone.ots7.com/order/checkout.php?PRODS=4713321&QTY=1&AFFILIATE=108875&CART=1"><img src="https://green.ots7.com/screenshots/OtsAV/OtsAVDJ1.90-300x188.jpg" border="0">OtsAV DJ Pro</a>
<!-- affiliate ads end -->
![Tdarr Media Added to Library Crop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/tdarr-media-added-to-library-crop.jpg)
5. Nothing will happen because your node needs to be configured to act on it. For that, scroll up to find the **Nodes** panel and click on your node name.  
<!-- affiliate ads begin -->
<a href="https://aofit.pxf.io/c/5597632/1399701/16396" target="_top" id="1399701"><img src="//a.impactradius-go.com/display-ad/16396-1399701" border="0" alt="" width="960" height="300"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1399701/16396" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Tdarr Node Selection Crop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/tdarr-node-selection-crop.jpg)

1. You will see more details about the selected node, and you can use the **plus** and **minus** buttons next to **Transcode** and **Health Check** to assign to the node CPU and GPU threads for each task. This way, you control which node does what, which is especially useful in a multi-computer environment.  
<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=22889392&QTY=1&AFFILIATE=108875&CART=1"><img src="http://webstatic.nero.com/nero2015-com-wAssets/img/affiliate/media/banner728-90eng.jpg" border="0"></a>
<!-- affiliate ads end -->
![Tdarr Node Transcode and Health Check Crop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/tdarr-node-transcode-and-health-check-crop.jpg)
2. Click on your node's **Options** button to access its more advanced options.
3. You can manually edit the node's configuration from here. Still, it's best to leave it as is and only manipulate it using external applications like Notepad.  
![Tdarr Node Config](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/tdarr-node-config-1.jpg)
4. Scroll down and use the drop-down menu to select which type of GPU acceleration you want the node to use (if available on your hardware).  
![Tdarr Node Hardware Encoding Crop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/tdarr-node-hardware-encoding-crop.jpg)
5. If you want to use the PC on which the node runs for other tasks while encoding, flick the switch under **Low FFMPEG/HandBrake Process Priority** to have the node consume fewer resources and avoid choking your PC. Alternatively, [use an app like Process Lasso to take control of your CPU threads](https://www.makeuseof.com/process-lasso-take-control-of-cpu-threads/) and ensure it won't start crawling while encoding.
6. For even more control, you can scroll down further and create a **Node schedule**, stating which hours of the day a node will be allowed to perform health-checking or transcoding tasks using the CPU or GPU.
7. When you return to the **Nodes** panel with at least one CPU or GPU assigned for transcoding and health checks, you will see that your node has started working on your incoming file.  
<!-- affiliate ads begin -->
<a href="https://newchic.sjv.io/c/5597632/1659704/14420" target="_top" id="1659704"><img src="//a.impactradius-go.com/display-ad/14420-1659704" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1659704/14420" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Tdarr Node Scanning Media File Crop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/tdarr-node-scanning-media-file-crop.jpg)
8. After an initial check and if the incoming file doesn't match your filter, Tdarr will start transcoding it.

 You can see the result when it's done if you scroll to the **Staging** section where, in our case, the status of our file was "**Transcode Success**", and its size was down to around 49 MB. The **Handling** field on the right offers three buttons for controlling the entries of this list.

 Using those, you can requeue, skip, or accept an encode. You can find the re-encoded version of your file inside the "Ready" folder.

![Tdarr Re encoded File in Ready Folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/tdarr-re-encoded-file-in-ready-folder.jpg)

<!-- affiliate ads begin -->
<a href="https://caperobbin.sjv.io/c/5597632/2006123/18460" target="_top" id="2006123"><img src="//a.impactradius-go.com/display-ad/18460-2006123" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2006123/18460" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Network & Hardware-Accelerated Encoding

 Tdarr is best when using all the CPU and GPU power of all PCs on your local network for re-encoding your files. However, that's a bit more complicated to set up.

 For this part of our guide, we take for granted that you have more than one PC, and they can "see" each other through your local network. You've got the PCs but haven't "networked them" yet? Choose a networking approach from our collection of [diagrams on which to base your home network for full connectivity](https://www.makeuseof.com/home-network-setup-diagrams/), and then follow our guide on [how to set up a secure home network](https://www.makeuseof.com/home-network-setup/).

1. Since all the PCs that will become nodes in Tdarr's network will require access to the same media files, you should keep them in a network-accessible shared folder. It's better to use a dedicated network drive for that. Still, we shared the same "Videos" folder we created earlier, but with "**shared**" as its network alias.  
![Tdarr Shared Folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/tdarr-shared-folder.jpg)
2. Update the **Source**, **Transcode cache**, and **Output folder** paths of your library to point to the respective subfolders within your "Shared" folder.
3. Install Tdarr on the other PCs in your local network. Use your file manager to enter the "**configs**" folder in Tdarr's installation directory.  
![Tdarr Config Folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/tdarr-config-folder.jpg)
4. Make a copy of the "**Tdarr\_Node\_Config.json**" file, then open the original with a text editor (like Notepad).  
![Tdarr Node Config in Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/tdarr-node-config-in-explorer-1.jpg)
5. You can change the value next to "**nodeName**" to assign the node any name you wish, like "my\_laptop", to make it easier to recognize and manage what runs where. Next to "**serverIP**", enter the IP of the PC on which you run the Tdarr server. As the "**serverPort**", enter "**8266**".  
![Tdarr Editing Node Config](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/tdarr-editing-node-config.jpg)

1. Next, you have to configure the "**pathTranslators**". This section is the most complicated to grasp since it needs you to define **pairs of paths**. Next to "**server**", you must enter the path from which the Tdarr server can access a particular folder.
2. Next to "**node**", you must enter the equivalent path from which a node can access the same folder through the network. So, the actual path to our incoming folder on the Tdarr server PC was **//vmware-host/Shared Folders/Shared/Incoming**, but the path to the same folder on our node PC was through the mapped network drive "D:" and the folders **/Shared/Incoming**.
3. You have to define a path translator for each of the folders you've specified in Tdarr's interface for your "Incoming", "Temporary", and "Output" folders. The goal is to have both the Tdarr server and its nodes able to find the same files through their respective paths.  
![Tdarr Node Config Path Translators](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/tdarr-node-config-path-translators.jpg)
4. Run the node software on your second PC and ensure both its firewall and the one on your main Tdarr server PC allow connections between them. Our guide on [how to allow apps through Windows firewall](https://www.makeuseof.com/how-to-allow-apps-windows-firewall/) can help with that. You should see the remote node popup in your Tdarr server interface if everything works correctly.  
![Tdarr Network Node Connected](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/tdarr-network-node-connected.jpg)
5. Next to its address, you will see its IP address and be able to control its CPU and GPU threads and options as if it were a local node.
6. If GPU encoding doesn't work for you, it's probably because the appropriate plugin is disabled. For that, move back to the **Libraries** page, scroll down to find its tabs, and click on **Transcode options**.
7. There, enable the "**Migz-Transcode Using Nvidia GPU & FFMPEG**" plugin. You must also prioritize it over CPU encoding by left-clicking, dragging, and dropping it above the "**Migz-Transcode Using CPU & FFMPEG**" plugin.  
![Tdarr Libraries Enable Hardware Transcoding Crop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/tdarr-libraries-enable-hardware-transcoding-crop.jpg)
8. From the same spot, if you click on a plugin, you can configure some options about how it will work. However, we won't dive into those, for they're outside the scope of this article.  
<!-- affiliate ads begin -->
<a href="https://propmoneyinc.pxf.io/c/5597632/1803115/14559" target="_top" id="1803115"><img src="//a.impactradius-go.com/display-ad/14559-1803115" border="0" alt="" width="859" height="859"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1803115/14559" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Tdarr Libraries Customize Hardware Transcoding Crop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/tdarr-libraries-customize-hardware-transcoding-crop.jpg)
9. When you return to the **Nodes** panel, your nodes (for which you've enabled that) should be using their GPUs for transcoding.

## Set Up Your Auto-Multi-Hyper-Encoder With Tdarr

 Setting up complicated automation software like Tdarr can take a while and occasionally make you wonder why something doesn't work as intended. When you set it up, though, Tdarr feels like magic.

 Add its server and nodes to your computers' auto-startup sequences, and hey presto, your media will always be re-encoded to high-quality, smaller files, using the optimal resolutions and formats for every single "machine" in your network. All while taking advantage of all available CPUs and GPUs in your PCs without you having to lift a finger.

 If you have more than one PC in your home network, why not let them lend a helping hand when transcoding media? Tdarr can turn all your PCs into nodes of the same networked transcoder, resulting in much faster audio and video encoding. Let's see how.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-docs.techidaily.com/024-approved-live-watch-tracker-applications/"><u>[New] 2024 Approved  Live Watch Tracker Applications</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/new-2024-approved-step-by-step-guide-to-facebook-mastery-pro-and-novice-edition/"><u>[New] 2024 Approved  Step-by-Step Guide to Facebook Mastery  Pro & Novice Edition</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-demystifying-the-purpose-what-is-a-blue-image-on-facebook-for-2024/"><u>[New] Demystifying the Purpose  What Is a Blue Image on Facebook for 2024</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-how-to-effortlessly-record-and-share-snapchat-videos-for-2024/"><u>[New] How to Effortlessly Record and Share Snapchat Videos for 2024</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-master-screen-recording-on-windows-macos-and-android-devices/"><u>[New] Master Screen Recording on Windows, macOS, and Android Devices</u></a></li>
<li><a href="https://fox-links.techidaily.com/new-unlock-iphone-video-potential-mastering-8-essential-filmmaking-skills-for-2024/"><u>[New] Unlock iPhone Video Potential  Mastering 8 Essential Filmmaking Skills for 2024</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-creating-an-individualistic-tiktok-identifier/"><u>[Updated] Creating an Individualistic TikTok Identifier</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-propel-your-workflow-final-cut-pros-must-have-tools/"><u>[Updated] Propel Your Workflow  Final Cut Pro’s Must-Have Tools</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/2024-approved-the-entrepreneurs-lifeline-critical-items-every-startup-needs-right-now/"><u>2024 Approved  The Entrepreneur's Lifeline  Critical Items Every Startup Needs Right Now</u></a></li>
<li><a href="https://vp-tips.techidaily.com/2024-approved-the-ultimate-guide-to-iphone-multimedia-magic/"><u>2024 Approved  The Ultimate Guide to iPhone Multimedia Magic</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-unleash-your-pcs-hidden-treasures-with-new-windows-10-games/"><u>2024 Approved  Unleash Your PC’s Hidden Treasures with New Windows 10 Games</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/2024-approved-unlocking-creative-edits-your-guide-to-snapchat-photos/"><u>2024 Approved  Unlocking Creative Edits  Your Guide to Snapchat Photos</u></a></li>
<li><a href="https://windows11.techidaily.com/8-strategies-for-enhancing-windows-11-wi-fi-connectivity/"><u>8 Strategies for Enhancing Windows 11 Wi-Fi Connectivity</u></a></li>
<li><a href="https://windows11.techidaily.com/a-step-by-step-guide-to-modifying-windows-file-attributes/"><u>A Step-by-Step Guide to Modifying Windows File Attributes</u></a></li>
<li><a href="https://windows11.techidaily.com/achieve-peak-performance-self-update-system-with-new-amd-drivers/"><u>Achieve Peak Performance: Self-Update System with New AMD Drivers</u></a></li>
<li><a href="https://windows11.techidaily.com/adapting-oculus-quest-3-for-windows-os-vr-environment/"><u>Adapting Oculus Quest 3 for Windows OS VR Environment</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-latency-issues-when-connecting-external-monitors/"><u>Addressing Latency Issues When Connecting External Monitors</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-win-1011s-xc0f1103f-with-geforce-error/"><u>Addressing Win 10/11'S XC0F1103F with GeForce Error</u></a></li>
<li><a href="https://windows11.techidaily.com/altering-start-page-in-windows-11-task-manager/"><u>Altering Start Page in Windows 11 Task Manager</u></a></li>
<li><a href="https://windows11.techidaily.com/boost-windows-11-notepad-using-ai-mentor/"><u>Boost Windows 11 Notepad Using AI Mentor</u></a></li>
<li><a href="https://windows11.techidaily.com/bring-back-disappearing-desktop-elements-on-windows/"><u>Bring Back Disappearing Desktop Elements on Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-need-old-password-error-in-microsoft-windows/"><u>Bypassing 'Need Old Password' Error in Microsoft Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-invalid-captcha-on-steam/"><u>Bypassing Invalid CAPTCHA on Steam</u></a></li>
<li><a href="https://windows11.techidaily.com/bypassing-os-admin-error-run-blocked-apps/"><u>Bypassing OS Admin Error: Run Blocked Apps</u></a></li>
<li><a href="https://windows11.techidaily.com/cant-open-the-credential-manager-on-windows-try-these-fixes/"><u>Can’t Open the Credential Manager on Windows? Try These Fixes</u></a></li>
<li><a href="https://windows11.techidaily.com/clearing-obstructions-uninstalling-programs-on-win-11/"><u>Clearing Obstructions: Uninstalling Programs on Win 11</u></a></li>
<li><a href="https://windows11.techidaily.com/clearing-up-dual-users-fixing-their-windows-account-error/"><u>Clearing Up Dual Users: Fixing Their Windows Account Error</u></a></li>
<li><a href="https://windows11.techidaily.com/comprehensive-guide-to-resolve-error-0x8007007e-in-windows/"><u>Comprehensive Guide to Resolve Error 0X8007007E in Windows</u></a></li>
<li><a href="https://windows11.techidaily.com/concealing-windows-firewall-areas-a-step-by-step-guide/"><u>Concealing Windows Firewall Areas: A Step-by-Step Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/connectivity-problems-windows-solutions/"><u>Connectivity Problems: Windows Solutions</u></a></li>
<li><a href="https://windows11.techidaily.com/context-menu-augmentation-with-disk-space-visualization-tools/"><u>Context Menu Augmentation with Disk Space Visualization Tools</u></a></li>
<li><a href="https://windows11.techidaily.com/correcting-windows-11-upgrade-problem-code-0x800f0922/"><u>Correcting Windows 11 Upgrade Problem - Code 0X800f0922</u></a></li>
<li><a href="https://windows11.techidaily.com/curbing-the-noise-quiet-explore-tab-behavior/"><u>Curbing the Noise: Quiet Explore Tab Behavior</u></a></li>
<li><a href="https://windows11.techidaily.com/customizing-interval-for-automatic-logoff/"><u>Customizing Interval for Automatic Logoff</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphering-disconnect-adjustable-gif-sizes-for-discord-on-windows/"><u>Deciphering Disconnect: Adjustable GIF Sizes for Discord on Windows</u></a></li>
<li><a href="https://activate-lock.techidaily.com/effective-ways-to-fix-checkra1n-error-31-on-apple-iphone-15-pro-by-drfone-ios/"><u>Effective Ways To Fix Checkra1n Error 31 On Apple iPhone 15 Pro</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/in-2024-best-practices-for-non-audio-filming/"><u>In 2024, Best Practices for Non-Audio Filming</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-changefake-your-samsung-galaxy-a34-5g-location-on-viber-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change/Fake Your Samsung Galaxy A34 5G Location on Viber | Dr.fone</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/interpreting-the-purpose-behind-a-facebooks-blue-video-icon-for-2024/"><u>Interpreting the Purpose Behind a Facebook's Blue Video Icon for 2024</u></a></li>
<li><a href="https://data-recovery.techidaily.com/skydata-rescue-service/"><u>SkyData Rescue Service</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>