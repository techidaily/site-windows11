---
title: Troubleshooting Windows 11 Issues on Legacy Processors
date: 2024-08-26 22:46:24
updated: 2024-08-29 12:47:17
tags:
  - windows
categories:
  - tech
thumbnail: https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/08/windows-11-2.jpg
---

## Troubleshooting Windows 11 Issues on Legacy Processors

The official system requirements for Windows 11 are much higher than Windows 10, but workarounds exist to install the operating system on older PCs. However, some of those older PCs can no longer use Windows 11 due to a CPU instruction update.

 Microsoft started testing Windows 11 builds back in February that required the POPCNT CPU instruction for some system functions. It was unclear at the time if the change was intentional or accidental, but the newer Windows 11 Build 26080 won’t even boot up if the processor doesn’t support POPCNT. Instead, Windows 11 gets stuck in a reboot loop. Microsoft declined to comment on the change when asked by _The Register_.

 The POPCNT CPU instruction is part of the SSE4.2 instruction set. Intel added it with the first generation of Core i5 and Core i7 processors (the [Nehalem architecture](https://en.wikipedia.org/wiki/Nehalem%5F%28microarchitecture%29)) in 2008\. AMD added the SSE4.2 instruction set to its [Bulldozer processors](https://en.wikipedia.org/wiki/Bulldozer%5F%28microarchitecture%29) in 2013—the POPCNT instruction was supported in earlier AMD CPUs, but only under the incomplete SSE4a instruction set, which Windows 11 doesn't appear to support. There’s no workaround for missing CPU instructions.

 Microsoft’s official system requirements for Windows 11 already included an eight-generation Intel Core CPU or later, or a second-generation Ryzen processor or later, as well as [other PC features like TPM 2.0](https://ai-video-apps.techidaily.com/new-mkv-file-trimming-made-simple-top-3-mac-apps-for-2024/). This change only affects people who bypassed those official requirements on computers with incredibly old processors. If you have a PC just outside of the official requirements, such as a first-gen Ryzen laptop or a desktop with a seventh-generation Intel CPU, you’re still fine for now.

 Even though those older CPUs were never supposed to run Windows 11 in the first place, it’s still an annoying change. Microsoft will [end support for Windows 10](https://remote-screen-capture.techidaily.com/new-in-2024-screenflow-unleashed-the-ultimate-macos-experience/) in October 2025, unless you pay for continued software support—we [still don’t know how much that will cost](https://hardware-tips.techidaily.com/unlocking-innovations-in-computers-and-electronics-on-toms-hardware/). If you have a PC with an older CPU, you’ll have to revert back to Windows 10, or try your luck with another operating system. However, some applications and games don’t work without that CPU instruction either, [such as Apex Legends](https://steamcommunity.com/app/1172470/discussions/0/3001047413708016057/).

 The next major release of Windows could arrive as early as this year, likely named Windows 12, and could have even higher system requirements than Windows 11\. However, all of the processors that lack support for POPCNT were already officially unsupported, and many of those PCs are likely still running earlier versions of Windows anyway.

 Source: Bob Pony on Twitter/X ([1](https://twitter.com/TheBobPony/status/1758023533064565076), [2](https://twitter.com/TheBobPony/status/1781922187252797805)), [The Register](https://www.theregister.com/2024/04/23/windows%5F11%5Fcpu%5Frequirements/)

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
