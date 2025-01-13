---
title: "Error Code 80240020: Comprehensive Troubleshooting Steps for Windows 10 Installation Issues Resolved!"
date: 2025-01-12T16:57:53.116Z
updated: 2025-01-13T17:47:27.660Z
tags:
  - win11
  - win10
  - win7
categories:
  - driver
description: "This Article Describes Error Code 80240020: Comprehensive Troubleshooting Steps for Windows 10 Installation Issues Resolved!"
excerpt: "This Article Describes Error Code 80240020: Comprehensive Troubleshooting Steps for Windows 10 Installation Issues Resolved!"
thumbnail: https://thmb.techidaily.com/000e56d00bac67101c26bbcafc9a191ee8cdd264920caaf7cb5a4bce74372cb0.jpg
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
<li><a href="https://video-screen-grab.techidaily.com/new-2024-approved-effortless-video-segmentation-techniques/"><u>[New] 2024 Approved Effortless Video Segmentation Techniques</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-expert-techniques-for-ps4-gameplay-documentation-for-2024/"><u>[Updated] Expert Techniques for PS4 Gameplay Documentation for 2024</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-unshackle-your-gaming-experience-with-diverse-capture-tools/"><u>[Updated] Unshackle Your Gaming Experience with Diverse Capture Tools</u></a></li>
<li><a href="https://tech-haven.techidaily.com/download-ios-18-a-comprehensive-guide-on-installation-and-compatible-iphone-models-detailed-insights-from-zdnet/"><u>Download IOS 18: A Comprehensive Guide on Installation and Compatible iPhone Models - Detailed Insights From ZDNet</u></a></li>
<li><a href="https://tech-haven.techidaily.com/iphones-unveiled-deciding-if-the-iphone-13-pro-or-pro-max-is-right-for-you-expert-insights/"><u>IPhones Unveiled: Deciding if the iPhone 13 Pro or Pro Max Is Right for You – Expert Insights</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/mastering-instagrams-frame-tips-and-tricks-for-full-image-captures/"><u>Mastering Instagram's Frame: Tips & Tricks for Full Image Captures</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/new-2024-approved-videopad-video-editor-2023-a-comprehensive-review-and-recommendation/"><u>New 2024 Approved Videopad Video Editor 2023 A Comprehensive Review and Recommendation</u></a></li>
<li><a href="https://tech-haven.techidaily.com/secure-your-advance-order-on-iphone-15-and-apple-watch-series-9ultra-2-with-top-savings-insights-from-zdnet/"><u>Secure Your Advance Order on iPhone 15 & Apple Watch Series 9/Ultra 2 with Top Savings - Insights From ZDNet</u></a></li>
<li><a href="https://tech-haven.techidaily.com/top-3-groundbreaking-iphone-16-innovations-that-will-make-you-rethink-your-next-phone-upgrade-insights-from-zdnet/"><u>Top 3 Groundbreaking iPhone 16 Innovations That Will Make You Rethink Your Next Phone Upgrade - Insights From ZDNet</u></a></li>
<li><a href="https://android-location-track.techidaily.com/top-5-tracking-apps-to-track-realme-11-proplus-without-them-knowing-drfone-by-drfone-virtual-android/"><u>Top 5 Tracking Apps to Track Realme 11 Pro+ without Them Knowing | Dr.fone</u></a></li>
<li><a href="https://tech-haven.techidaily.com/ultimate-guide-to-premium-wireless-charging-devices-of-2024-features-and-reviews-tested-by-professionals-zdnet/"><u>Ultimate Guide to Premium Wireless Charging Devices of 2024 - Features and Reviews Tested by Professionals | ZDNet</u></a></li>
<li><a href="https://tech-haven.techidaily.com/ultimate-selection-of-premium-wireless-charge-coils-professional-evaluations-by-techradar/"><u>Ultimate Selection of Premium Wireless Charge Coils : Professional Evaluations by TechRadar</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/updated-get-ready-for-the-movies-top-movie-trailer-apps-for-ios-for-2024/"><u>Updated Get Ready for the Movies Top Movie Trailer Apps for iOS for 2024</u></a></li>
<li><a href="https://tech-haven.techidaily.com/upgrading-to-iphone-16-pro-or-sticking-with-iphone-14-pro-insights-and-value-comparison/"><u>Upgrading to iPhone 16 Pro or Sticking with iPhone 14 Pro? Insights & Value Comparison</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/dvdsoft-dvd/"><u>윈엑스 DVDSoft 공식 웹사이트: 기꺼이 하는 DVD 리퍼, 비디오 컨버터, 아이폰 전송을 위한 단일 해결책</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/gOyLy8DeizY?si=GkAmK0hChZw6_2tW" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

