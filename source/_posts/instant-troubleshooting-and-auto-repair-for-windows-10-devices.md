---
title: Instant Troubleshooting and Auto-Repair for Windows 10 Devices
date: 2025-01-09T18:05:49.532Z
updated: 2025-01-13T16:01:50.720Z
tags:
  - win11
  - win10
  - win7
categories:
  - driver
description: This Article Describes Instant Troubleshooting and Auto-Repair for Windows 10 Devices
excerpt: This Article Describes Instant Troubleshooting and Auto-Repair for Windows 10 Devices
thumbnail: https://thmb.techidaily.com/a63a5a9ae6eb1efed5733d165b83ad90e6d4d9274b455dfd2cda566223079352.jpg
---

## Error Code 80240020: Comprehensive Troubleshooting Steps for Windows 10 Installation Issues Resolved

The**80240020** error happens usually when the Windows 10 files that you downloaded was not complete and the setup process still tried to do the upgrade to Windows 10\. Or it could be that your Windows 10 installation folder is unfinished or corrupted.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/error-code-80240020.jpg)

Luckily, this is an easy question to solve. Please follow the steps below to get this problem fixed. **Step One**1) Navigate to**C:\\$Windows.\~BT**folder. If you cannot see this folder, please make sure that you have checked the hidden items.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/windows-bt-600x427.jpg)

Delete as many files in this folder as you can. You might not be able to delete all the files due to permission issues. 2) Navigate to**C:\\Windows\\SoftwareDistribution\\Download** and delete all the files in this folder. Please note that you don’t have to delete**Download**folder, but rather, you need to delete the content in it.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/softwaredistributiondownload.jpg)

3) Type**cmd.exe**in the search box in**Start**panel and right click the option**cmd**and choose**Run as administrator**. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/run-as-administrator.jpg)Click**Yes**at this prompt.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/uac-command-processor.jpg)

4) Type**wuauclt.exe/updatenow**and hit**Enter**key. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/img_57b5394edbd33.png) **Step Two** **Warning**: Before you proceed with this step, please make sure that you have back up your registry first just in case any irreversible errors happen. Refer to this post to see[**how to backup and restore your registry**](https://tools.techidaily.com/drivereasy/download/). 1) Press**Windows key**and**R**at the same time, then type in**regedit**and hit**Enter**. When prompted for administrator permission, click**Yes** to continue.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/regedit.png)

2) Then follow the path:   **HKEY\_LOCAL\_MACHINE\\SOFTWARE\\Microsoft\\Windows\\CurrentVersion\\WindowsUpdate\\OSUpgrade**

![](https://images.drivereasy.com/wp-content/uploads/2016/10/hkey_local_machinesoftwaremicrosoftwindowscurrentversionwindowsupdateosupgrade-600x394.jpg)

3) On the right side of the pane, right click on the blank spot and select**New > DWORD (32-bit) Value**.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/new-dword-32-bit-value-600x396.jpg)

4) Rename the value to**AllowOSUpgrade**. Then double click the value and set the**Value data**to**1**. Then click**OK**to save the change.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/img_58140207aba43-600x394.jpg)

 Your**Windows Update** panel should come out in a couple of seconds. If it won’t open automatically, you can open this panel from Control Panel manually. Then, you should be able to download your Windows 10 from scratch.

The steps above also work if you are having a**80080080** or **8024600A**  error code. Usually the error is common with Windows 8.1 users, but for those who are using Windows 7, this solution applies as well. If the problem still persists, please be patient, Windows update takes time to download the upgrades in the background. If you still could not get this problem fixed, your Windows update tool might be corrupted so the security settings and background process is now malfunctioned. In this case, it is suggested that you burn the DVD or CD or USB flash drive with Windows 10 ISO files in to do the clean install from scratch. If you want to know how to do it, please refer to[this post here](https://tools.techidaily.com/drivereasy/download/) for more information.

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
<li><a href="https://youtube-lab.techidaily.com/n-2024-the-ultimate-comparison-of-gif-creators/"><u>[New] In 2024, The Ultimate Comparison of GIF Creators</u></a></li>
<li><a href="https://fox-blue.techidaily.com/updated-in-2024-total-control-guide-powerdirector-user-manual/"><u>[Updated] In 2024, Total Control Guide PowerDirector User Manual</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/2024-approved-the-art-of-visual-branding-with-professional-grade-fb-covers/"><u>2024 Approved The Art of Visual Branding with Professional-Grade FB Covers</u></a></li>
<li><a href="https://win-excellent.techidaily.com/capturing-your-screen-with-an-hp-device-a-step-by-step-guide/"><u>Capturing Your Screen with an HP Device: A Step-by-Step Guide</u></a></li>
<li><a href="https://win-solutions.techidaily.com/fixes-and-solutions-overcoming-the-game-crash-issue-in-formula-1-2021-for-pc/"><u>Fixes and Solutions: Overcoming the Game-Crash Issue in Formula 1 2021 for PC</u></a></li>
<li><a href="https://tech-haven.techidaily.com/migrating-chatgpt-dialogues-secure-methods-for-moving-conversation-history/"><u>Migrating ChatGPT Dialogues: Secure Methods for Moving Conversation History</u></a></li>
<li><a href="https://tech-haven.techidaily.com/navigating-artificial-intelligence-misperceptions-strategies-for-identifying-hallucination-scenarios/"><u>Navigating Artificial Intelligence Misperceptions: Strategies for Identifying Hallucination Scenarios</u></a></li>
<li><a href="https://tech-haven.techidaily.com/navigating-through-openai-api-from-basics-to-advanced-applications/"><u>Navigating Through OpenAI API – From Basics to Advanced Applications</u></a></li>
<li><a href="https://tech-haven.techidaily.com/next-gen-ai-escalating-cybersecurity-concerns/"><u>Next-Gen AI: Escalating Cybersecurity Concerns</u></a></li>
<li><a href="https://tech-haven.techidaily.com/next-gen-tech-showcase-the-5-best-ai-hardware-developments-to-watch/"><u>Next-Gen Tech Showcase: The 5 Best AI Hardware Developments to Watch</u></a></li>
<li><a href="https://tech-haven.techidaily.com/novelists-toolbox-expanded-9-uses-of-chatgpt-for-crafting-stories/"><u>Novelists' Toolbox Expanded: 9 Uses of ChatGPT for Crafting Stories</u></a></li>
<li><a href="https://tech-haven.techidaily.com/palm-2-vs-gpt-4-showdown-unveiling-the-divergences-in-next-gen-language-models/"><u>PaLM 2 Vs. GPT-4 Showdown: Unveiling the Divergences in Next-Gen Language Models</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/recording-rapture-screensavers-review-march-2023/"><u>Recording Rapture ScreenSavers Review – March 2023</u></a></li>
<li><a href="https://some-guidance.techidaily.com/superior-psd-text-direction-for-2024/"><u>Superior PSD Text Direction for 2024</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/troubleshooting-how-to-recover-from-a-missing-msoftdll-file/"><u>Troubleshooting: How to Recover From a Missing msoft.dll File</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/bes-best-10-cutting-edge-reaction-ideas/"><u>YouTube's Best 10 Cutting-Edge Reaction Ideas</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/SyMZxS9479s?si=0T6zZpyN2LBftFTM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

