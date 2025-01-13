---
title: "Frozen on Update: Expert Tips to Resolve a Stalled Windows Update Process"
date: 2025-01-11T18:01:25.836Z
updated: 2025-01-13T16:01:29.334Z
tags:
  - win11
  - win10
  - win7
categories:
  - driver
description: "This Article Describes Frozen on Update: Expert Tips to Resolve a Stalled Windows Update Process"
excerpt: "This Article Describes Frozen on Update: Expert Tips to Resolve a Stalled Windows Update Process"
thumbnail: https://thmb.techidaily.com/749c8b13fba53b16e3cca7c517e32ea283379a232e31a28dc3a9b19edc9409b3.jpg
---

## Error Code 80240020 Deciphered: Easy Steps to Successfully Install Windows 10 without a Glitch

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
<li><a href="https://youtube-tips.techidaily.com/ed-expert-tips-for-harnessing-the-power-of-top-9-free-youtube-makers-for-2024/"><u>[Updated] Expert Tips for Harnessing the Power of Top 9 Free YouTube Makers for 2024</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/2024-approved-professional-insights-into-recording-quality-conversations-on-facetime/"><u>2024 Approved Professional Insights Into Recording Quality Conversations on FaceTime</u></a></li>
<li><a href="https://tech-haven.techidaily.com/apples-elite-tablets-face-off-which-ipad-pro-is-best-for-you-insights-and-reviews/"><u>Apple's Elite Tablets Face-Off: Which iPad Pro Is Best for You? Insights & Reviews</u></a></li>
<li><a href="https://tech-haven.techidaily.com/exploring-superior-wallet-trackers-beyond-apple-and-tile-unveiled-by-zdnets-in-depth-testing/"><u>Exploring Superior Wallet Trackers Beyond Apple and Tile - Unveiled by ZDNET's In-Depth Testing!</u></a></li>
<li><a href="https://win-answers.techidaily.com/fixing-pc-issues-in-euro-truck-simulator-2-a-comprehve-solutions-compilation/"><u>Fixing PC Issues in Euro Truck Simulator 2 - A Comprehve Solutions Compilation</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-stop-life360-from-tracking-you-on-oppo-reno-8t-5g-drfone-by-drfone-virtual-android/"><u>How to Stop Life360 from Tracking You On Oppo Reno 8T 5G? | Dr.fone</u></a></li>
<li><a href="https://tech-haven.techidaily.com/identifying-and-locating-hidden-airtags-around-you-insights/"><u>Identifying and Locating Hidden AirTags Around You - Insights</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-what-are-location-permissions-life360-on-huawei-nova-y91-drfone-by-drfone-virtual-android/"><u>In 2024, What are Location Permissions Life360 On Huawei Nova Y91? | Dr.fone</u></a></li>
<li><a href="https://tech-haven.techidaily.com/is-it-time-for-you-to-grab-an-apple-vision-pro-on-presale-five-crucial-questions-answered-by-experts-at-zdnet/"><u>Is It Time for You to Grab an Apple Vision Pro on Presale? Five Crucial Questions Answered by Experts at ZDNet</u></a></li>
<li><a href="https://tech-haven.techidaily.com/resolving-major-issues-how-pixel-watch-3-enhances-googles-smartwatch-experience-techdigest/"><u>Resolving Major Issues: How Pixel Watch 3 Enhances Google's Smartwatch Experience | TechDigest</u></a></li>
<li><a href="https://novels-ebooks.techidaily.com/210023092-9781734758023-the-nature-of-god-the-revelation/"><u>The Nature of God: The Revelation | Free Book</u></a></li>
<li><a href="https://discover-cloud.techidaily.com/tips-menyimpan-kegiatan-lama-dalam-aplikasi-wechat-dengan-keamanan-terbesarkan/"><u>Tips Menyimpan Kegiatan Lama Dalam Aplikasi WeChat Dengan Keamanan Terbesarkan</u></a></li>
<li><a href="https://tech-haven.techidaily.com/top-36-unbeatable-tablet-offers-still-available-on-prime-day-2024-exclusive-list/"><u>Top 36 Unbeatable Tablet Offers Still Available on Prime Day 2024 - Exclusive List</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/qmQjRcnaq9g?si=jadcGtXemUAlKOTa" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

