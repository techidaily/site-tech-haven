---
title: "Ultimate Guide: Turning Off Pop-Up Suppressors on Major Browsers (Chrome, Firefox, Edge & IE)"
date: 2025-01-18T18:17:50.907Z
updated: 2025-01-19T17:24:49.755Z
tags:
  - win11
  - win10
  - win7
categories:
  - driver
description: "This Article Describes Ultimate Guide: Turning Off Pop-Up Suppressors on Major Browsers (Chrome, Firefox, Edge & IE)"
excerpt: "This Article Describes Ultimate Guide: Turning Off Pop-Up Suppressors on Major Browsers (Chrome, Firefox, Edge & IE)"
thumbnail: https://thmb.techidaily.com/dccea8e74312ef3978115e47791b42d8d3af59ddef7b2d9a4c85759dfb53f1ee.jpg
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
<li><a href="https://youtube-docs.techidaily.com/024-approved-innovative-classroom-techniques-utilizing-youtube-effectively/"><u>[New] 2024 Approved Innovative Classroom Techniques Utilizing YouTube Effectively</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-key-lights-and-soft-shadows-for-vloggers-for-2024/"><u>[Updated] Key Lights and Soft Shadows for Vloggers for 2024</u></a></li>
<li><a href="https://tech-haven.techidaily.com/7-compelling-reasons-why-chatgpt-is-an-asset-for-personalized-health-advice/"><u>7 Compelling Reasons Why ChatGPT Is an Asset for Personalized Health Advice</u></a></li>
<li><a href="https://tech-haven.techidaily.com/academic-research-revolutionized-discover-how-ai-tools-play-a-vital-role/"><u>Academic Research Revolutionized: Discover How AI Tools Play a Vital Role</u></a></li>
<li><a href="https://tech-haven.techidaily.com/ais-creative-domain-who-holds-the-title/"><u>AI's Creative Domain: Who Holds The Title?</u></a></li>
<li><a href="https://tech-haven.techidaily.com/anticipating-chatgpt-desktop-launch-explore-an-exceptional-open-source-option-now/"><u>Anticipating ChatGPT Desktop Launch? Explore an Exceptional Open-Source Option Now!</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-full-guide-to-unlock-iphone-15-pro-max-with-itunes-drfone-by-drfone-ios/"><u>In 2024, Full Guide to Unlock iPhone 15 Pro Max with iTunes | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-proven-ways-in-how-to-hide-location-on-life360-for-oppo-k11-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Proven Ways in How To Hide Location on Life360 For Oppo K11 5G | Dr.fone</u></a></li>
<li><a href="https://fox-access.techidaily.com/instructions-for-installing-windows-movie-maker-6/"><u>Instructions for Installing Windows Movie Maker 6</u></a></li>
<li><a href="https://buynow-info.techidaily.com/top-rated-acer-aspire-e-15-analysis-the-ultimate-guide-to-affordable-high-performance-laptops/"><u>Top Rated Acer Aspire E 15 Analysis - The Ultimate Guide to Affordable, High-Performance Laptops</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Xq2r4ZKM-Po?si=fA2DdEB1op-atCkz" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

