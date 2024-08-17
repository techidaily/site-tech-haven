---
title: The Ultimate Guide to Accessing Windows 10 Recovery Options Menu Successfully
date: 2024-08-16T10:04:51.239Z
updated: 2024-08-17T10:04:51.239Z
tags:
  - win11
  - win10
  - win7
categories:
  - driver
description: This Article Describes The Ultimate Guide to Accessing Windows 10 Recovery Options Menu Successfully
excerpt: This Article Describes The Ultimate Guide to Accessing Windows 10 Recovery Options Menu Successfully
thumbnail: https://thmb.techidaily.com/f8511b1b508552460f630419c51d2d616ebcbf19dbd124bdf2e50582d197ea31.jpg
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
<li><a href="https://instagram-videos.techidaily.com/updated-2024-approved-step-by-step-harnessing-instagram-filters/"><u>[Updated] 2024 Approved  Step-by-Step  Harnessing Instagram Filters</u></a></li>
<li><a href="https://fox-access.techidaily.com/updated-revolutionizing-education-through-vr-for-2024/"><u>[Updated] Revolutionizing Education Through VR for 2024</u></a></li>
<li><a href="https://tech-haven.techidaily.com/discover-how-to-leverage-chatgpts-capabilities-within-visual-studio-code/"><u>Discover How to Leverage ChatGPT's Capabilities Within Visual Studio Code</u></a></li>
<li><a href="https://tech-haven.techidaily.com/effectively-querying-chatgpt-5-tactics-to-ensure-high-quality-ai-answers/"><u>Effectively Querying ChatGPT: 5 Tactics to Ensure High-Quality AI Answers</u></a></li>
<li><a href="https://tech-haven.techidaily.com/effortless-codegpt-implementation-within-your-visual-studio-code-environment/"><u>Effortless CodeGPT Implementation Within Your Visual Studio Code Environment</u></a></li>
<li><a href="https://tech-haven.techidaily.com/enhance-academic-exploration-discover-how-ai-can-revolutionize-your-research-process/"><u>Enhance Academic Exploration: Discover How AI Can Revolutionize Your Research Process</u></a></li>
<li><a href="https://tech-haven.techidaily.com/exploring-ai-through-the-eyes-of-10-leading-international-technology-visionaries/"><u>Exploring AI Through the Eyes of 10 Leading International Technology Visionaries</u></a></li>
<li><a href="https://tech-haven.techidaily.com/forefront-ai-vs-chatgpt-which-artificial-intelligence-is-superior/"><u>Forefront AI Vs. ChatGPT: Which Artificial Intelligence Is Superior?</u></a></li>
<li><a href="https://tech-haven.techidaily.com/google-io-2nd-the-top-7-cutting-edge-features-revealed-for-the-new-bard-ai/"><u>Google I/O 2nD: The Top 7 Cutting-Edge Features Revealed for the New Bard AI</u></a></li>
<li><a href="https://tech-haven.techidaily.com/how-reliable-are-googles-bard-and-microsofts-chatgpt-for-making-savvy-investment-choices/"><u>How Reliable Are Google's Bard and Microsoft's ChatGPT for Making Savvy Investment Choices?</u></a></li>
<li><a href="https://tech-haven.techidaily.com/how-to-access-new-features-in-chatgpt-turn-on-the-beta-version-of-web-browsing-and-plugins/"><u>How To Access New Features in ChatGPT - Turn On the Beta Version of Web Browsing and Plugins</u></a></li>
<li><a href="https://techidaily.com/how-to-perform-hard-reset-on-google-pixel-fold-drfone-by-drfone-reset-android-reset-android/"><u>How to Perform Hard Reset on Google Pixel Fold? | Dr.fone</u></a></li>
<li><a href="https://tech-haven.techidaily.com/how-to-securely-backup-and-export-your-data-from-chatgpt/"><u>How to Securely Backup and Export Your Data From ChatGPT</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-use-google-assistant-on-your-lock-screen-of-oppo-f25-pro-5g-phone-by-drfone-android/"><u>How to Use Google Assistant on Your Lock Screen Of Oppo F25 Pro 5G Phone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-use-phone-clone-to-migrate-your-oppo-a18-data-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Use Phone Clone to Migrate Your Oppo A18 Data? | Dr.fone</u></a></li>
<li><a href="https://fake-location.techidaily.com/in-2024-a-detailed-guide-on-faking-your-location-in-mozilla-firefox-on-honor-magic-6-pro-drfone-by-drfone-virtual-android/"><u>In 2024, A Detailed Guide on Faking Your Location in Mozilla Firefox On Honor Magic 6 Pro | Dr.fone</u></a></li>
<li><a href="https://iphone-location.techidaily.com/in-2024-does-itools-virtual-location-not-work-on-apple-iphone-xs-maxipad-drfone-by-drfone-virtual-ios/"><u>In 2024, Does iTools virtual location not work On Apple iPhone XS Max/iPad? | Dr.fone</u></a></li>
<li><a href="https://tech-haven.techidaily.com/inside-look-how-chatgpt-revolutionized-my-podcast-scriptwriting-process/"><u>Inside Look: How ChatGPT Revolutionized My Podcast Scriptwriting Process</u></a></li>
<li><a href="https://fox-that.techidaily.com/iphone-users-troubleshoot-your-contacts-app-issues-with-these-simple-solutions/"><u>IPhone Users: Troubleshoot Your Contacts App Issues with These Simple Solutions</u></a></li>
<li><a href="https://tech-haven.techidaily.com/kickstart-embrace-8-customizable-gpt-models-now/"><u>Kickstart: Embrace 8 Customizable GPT Models Now</u></a></li>
<li><a href="https://tech-haven.techidaily.com/maintain-silence-on-secrets-not-with-gpt-assistance/"><u>Maintain Silence on Secrets, Not with GPT Assistance</u></a></li>
<li><a href="https://tech-haven.techidaily.com/master-the-art-of-hiding-your-chatconversations-with-gpt-no-deletions-involved/"><u>Master the Art of Hiding Your ChatConversations with GPT: No Deletions Involved</u></a></li>
<li><a href="https://tech-haven.techidaily.com/mastering-dual-ai-voice-assistance-using-chatgpt-alongside-siri-on-ios-devices/"><u>Mastering Dual AI Voice Assistance: Using ChatGPT Alongside Siri on iOS Devices</u></a></li>
<li><a href="https://tech-haven.techidaily.com/mastering-the-art-of-specialized-instructions-for-chatgpt-top-5-techniques/"><u>Mastering the Art of Specialized Instructions for ChatGPT: Top 5 Techniques</u></a></li>
<li><a href="https://tech-haven.techidaily.com/mastering-the-art-of-verifying-health-advice-a-guide-to-evaluating-info-from-chatgpt-and-ai/"><u>Mastering the Art of Verifying Health Advice: A Guide to Evaluating Info From ChatGPT & AI</u></a></li>
<li><a href="https://tech-haven.techidaily.com/mastering-the-chatgpt-widget-a-comprehensive-guide-for-android-users/"><u>Mastering the ChatGPT Widget: A Comprehensive Guide for Android Users</u></a></li>
<li><a href="https://tech-haven.techidaily.com/natures-edge-is-chatbot-support-crucial-for-survival/"><u>Nature's Edge: Is Chatbot Support Crucial for Survival?</u></a></li>
<li><a href="https://tech-haven.techidaily.com/navigating-ai-top-6-chatgpt-enhancements-tailored-for-developers-using-vs-code/"><u>Navigating AI: Top 6 ChatGPT Enhancements Tailored for Developers Using VS Code</u></a></li>
<li><a href="https://tech-haven.techidaily.com/navigating-novelty-bard-vs-bing-for-optimal-chatting/"><u>Navigating Novelty: Bard Vs. Bing for Optimal Chatting</u></a></li>
<li><a href="https://tech-haven.techidaily.com/navigating-the-complexities-of-chatgpt-in-professional-writing/"><u>Navigating the Complexities of ChatGPT in Professional Writing</u></a></li>
<li><a href="https://tech-haven.techidaily.com/navigating-the-use-of-modified-chatgpt-versions-risks-and-rewards/"><u>Navigating the Use of Modified ChatGPT Versions: Risks and Rewards</u></a></li>
<li><a href="https://tech-haven.techidaily.com/offline-maps/"><u>Offline Maps</u></a></li>
<li><a href="https://tech-haven.techidaily.com/protecting-the-web-insight-into-next-gen-security-predictions/"><u>Protecting the Web : Insight Into Next-Gen Security Predictions</u></a></li>
<li><a href="https://tech-haven.techidaily.com/six-key-benefits-of-opting-for-the-chatgpt-app-on-apple-devices-instead-of-the-web-site/"><u>Six Key Benefits of Opting for the ChatGPT App on Apple Devices Instead of the Web Site</u></a></li>
<li><a href="https://buynow-info.techidaily.com/stay-active-in-style-discover-how-the-garmin-vivomove-hr-enhances-daily-workouts/"><u>Stay Active in Style: Discover How the Garmin Vivomove HR Enhances Daily Workouts</u></a></li>
<li><a href="https://android-transfer.techidaily.com/top-6-ways-to-transfer-text-messages-from-oppo-a2-to-other-android-devices-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>Top 6 Ways to Transfer Text Messages from Oppo A2 to Other Android Devices | Dr.fone</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/unveiling-the-performance-of-the-samsung-cf591-in-modern-gaming-scenarios/"><u>Unveiling the Performance of the Samsung CF591 in Modern Gaming Scenarios</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=4691139&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/SU-200-1.png" border="0">Software Update Pro - Check and update software installed on your computer. </a>
<!-- affiliate ads end -->