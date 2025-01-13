---
title: How to Fix Windows 11 Installation Failure - Error Code 80240020 Solution Guide
date: 2025-01-09T17:10:30.988Z
updated: 2025-01-13T16:52:45.512Z
tags:
  - win11
  - win10
  - win7
categories:
  - driver
description: This Article Describes How to Fix Windows 11 Installation Failure - Error Code 80240020 Solution Guide
excerpt: This Article Describes How to Fix Windows 11 Installation Failure - Error Code 80240020 Solution Guide
thumbnail: https://thmb.techidaily.com/1d642682ec5cb6a6ea7cd33f84c3c6bed241d468dfb7fb68a3c7508632db1da6.jpg
---

## Resolving Windows 10 Installation Issue - Fix Error Code 80 #

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
<li><a href="https://facebook-videos.techidaily.com/new-discover-the-best-fb-movie-tools-no-8-in-23/"><u>[New] Discover the Best FB Movie Tools No. 8 in '23</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-top-5-techniques-for-captivating-your-twitch-audience-for-2024/"><u>[New] Top 5 Techniques for Captivating Your Twitch Audience for 2024</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-in-2024-perfecting-online-presence-key-to-knowing-and-using-fb-video-ratios/"><u>[Updated] In 2024, Perfecting Online Presence Key to Knowing and Using FB Video Ratios</u></a></li>
<li><a href="https://extra-tips.techidaily.com/2024-approved-achieving-smooth-volume-decreases-using-lumafusion/"><u>2024 Approved Achieving Smooth Volume Decreases Using Lumafusion</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-geforce-experience-error-how-to-restore-missing-configuration/"><u>Fixing GeForce Experience Error: How to Restore Missing Configuration</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/how-apple-can-level-up-its-intelligence-game-against-rivals-like-openai-and-google-expert-analysis-by-zdnet/"><u>How Apple Can Level Up Its Intelligence Game Against Rivals Like OpenAI and Google - Expert Analysis by ZDNet</u></a></li>
<li><a href="https://extra-resources.techidaily.com/in-2024-best-electrolytes-for-hero5-authentic-and-3rd-party-companies/"><u>In 2024, Best Electrolytes for Hero5 - Authentic & 3Rd Party Companies</u></a></li>
<li><a href="https://extra-information.techidaily.com/in-2024-best-hd-action-recorder-brands-under-100/"><u>In 2024, Best HD Action Recorder Brands Under $100</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-detailed-guide-of-ispoofer-for-pogo-installation-on-nokia-c32-drfone-by-drfone-virtual-android/"><u>In 2024, Detailed guide of ispoofer for pogo installation On Nokia C32 | Dr.fone</u></a></li>
<li><a href="https://tech-haven.techidaily.com/unveiling-the-secrets-behind-chatgpts-shared-link-functionality/"><u>Unveiling the Secrets Behind ChatGPT's Shared Link Functionality</u></a></li>
<li><a href="https://tech-haven.techidaily.com/unveiling-the-unique-characteristics-of-nlp-vs-machine-learning-in-artificeal-intelligence/"><u>Unveiling the Unique Characteristics of NLP vs Machine Learning in Artificeal Intelligence</u></a></li>
<li><a href="https://tech-haven.techidaily.com/utilizing-anthropics-new-claude-prompts/"><u>Utilizing Anthropic's New Claude Prompts</u></a></li>
<li><a href="https://tech-haven.techidaily.com/veiled-preservation-of-private-gpt-interactions/"><u>Veiled Preservation of Private GPT Interactions</u></a></li>
<li><a href="https://tech-haven.techidaily.com/why-consider-a-local-llm-unlock-the-potential-benefits-and-recognize-the-risks/"><u>Why Consider a Local LLM? Unlock the Potential Benefits and Recognize the Risks</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/epKTCSREjhI?si=Ez_hObK1FZrmEE7f" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

