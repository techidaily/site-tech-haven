---
title: "Fixing the Windows 10 KB Error Code 0X80070422: A Comprehensive Solution"
date: 2024-08-16T10:06:00.068Z
updated: 2024-08-17T10:06:00.068Z
tags:
  - win11
  - win10
  - win7
categories:
  - driver
description: "This Article Describes Fixing the Windows 10 KB Error Code 0X80070422: A Comprehensive Solution"
excerpt: "This Article Describes Fixing the Windows 10 KB Error Code 0X80070422: A Comprehensive Solution"
thumbnail: https://thmb.techidaily.com/7fab9a6185158d097b206408c1b02e98fd2b514b00431bdf0c9ec5881d711d0e.jpg
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
<li><a href="https://snapchat-videos.techidaily.com/new-2024-approved-maintaining-a-continuous-snapchat-connection/"><u>[New] 2024 Approved  Maintaining a Continuous Snapchat Connection</u></a></li>
<li><a href="https://fox-helps.techidaily.com/new-conquer-broadcasting-unite-obs-and-streamlabs-for-mac/"><u>[New] Conquer Broadcasting  Unite OBS & Streamlabs for Mac</u></a></li>
<li><a href="https://extra-resources.techidaily.com/new-crafting-harmonious-mixes-the-audacity-crossfade-method/"><u>[New] Crafting Harmonious Mixes  The Audacity Crossfade Method</u></a></li>
<li><a href="https://youtube-web.techidaily.com/picurean-envoys-the-best-food-vloggers-to-watch/"><u>[New] Epicurean Envoys  The Best Food Vloggers to Watch</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-initiating-into-the-world-of-facebook-video-content-creation/"><u>[Updated] Initiating Into the World of Facebook Video Content Creation</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-social-media-snippet-seizers-2023/"><u>[Updated] Social Media Snippet Seizers, 2023</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-uncharted-visual-narrative-evaluation-and-parallel-proposals/"><u>[Updated] Uncharted Visual Narrative Evaluation & Parallel Proposals</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-find-the-best-8-spots-for-free-3d-text-psd-downloads/"><u>2024 Approved  Find the Best 8 Spots for FREE 3D Text PSD Downloads</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/2024-approved-secure-video-communication-made-simple-with-top-10-safe-apps-on-mobile-devices/"><u>2024 Approved  Secure Video Communication Made Simple with Top 10 Safe Apps on Mobile Devices</u></a></li>
<li><a href="https://android-location.techidaily.com/3-effective-methods-to-fake-gps-location-on-android-for-your-zte-blade-a73-5g-drfone-by-drfone-virtual/"><u>3 Effective Methods to Fake GPS location on Android For your ZTE Blade A73 5G | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/configuring-prints-with-microsoft-defender-smartscreen-edge/"><u>Configuring Prints with Microsoft Defender SmartScreen Edge</u></a></li>
<li><a href="https://apple-account.techidaily.com/everything-to-know-about-apple-id-password-requirements-for-iphone-12-pro-max-by-drfone-ios/"><u>Everything To Know About Apple ID Password Requirements For iPhone 12 Pro Max</u></a></li>
<li><a href="https://driver-download.techidaily.com/get-your-canon-mx920-wi-fi-a3586dw-printer-drivers-installed-on-windows/"><u>Get Your Canon MX920 Wi-Fi A3586dw Printer Drivers Installed on Windows</u></a></li>
<li><a href="https://tech-haven.techidaily.com/how-is-generative-ai-emerging-as-a-key-player-in-information-manipulation/"><u>How Is Generative AI Emerging as a Key Player in Information Manipulation?</u></a></li>
<li><a href="https://tech-haven.techidaily.com/how-palm-2-elevates-googles-bard-ai-7-key-improvements-unveiled/"><u>How PaLM 2 Elevates Google's Bard AI: 7 Key Improvements Unveiled</u></a></li>
<li><a href="https://techidaily.com/how-to-repair-apple-iphone-xs-max-system-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Repair Apple iPhone XS Max System? | Dr.fone</u></a></li>
<li><a href="https://tech-haven.techidaily.com/how-to-secure-your-system-by-not-downloading-google-bard-potential-virus-alert/"><u>How to Secure Your System by Not Downloading Google Bard – Potential Virus Alert</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-unlock-oppo-a38-pin-codepattern-lockpassword-by-drfone-android/"><u>How to Unlock Oppo A38 PIN Code/Pattern Lock/Password</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-how-to-open-your-apple-iphone-13-pro-max-without-a-home-button-by-drfone-ios/"><u>In 2024, How To Open Your Apple iPhone 13 Pro Max Without a Home Button</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-pokemon-go-cooldown-chart-on-oneplus-nord-3-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Pokémon Go Cooldown Chart On OnePlus Nord 3 5G | Dr.fone</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-progopro-enhancing-footage-and-stability/"><u>In 2024, ProGoPro  Enhancing Footage & Stability</u></a></li>
<li><a href="https://tech-haven.techidaily.com/is-openais-dominion-over-gpt-dwindling/"><u>Is OpenAI's Dominion Over GPT Dwindling?</u></a></li>
<li><a href="https://tech-haven.techidaily.com/is-your-information-secure-addressing-privacy-matters-with-chatgpt/"><u>Is Your Information Secure? Addressing Privacy Matters with ChatGPT</u></a></li>
<li><a href="https://tech-haven.techidaily.com/jumpstart-your-ai-journey-access-8-easy-to-implement-custom-gpts-today/"><u>Jumpstart Your AI Journey: Access 8 Easy-to-Implement Custom GPTs Today</u></a></li>
<li><a href="https://tech-haven.techidaily.com/leveraging-ai-in-scholarly-pursuits/"><u>Leveraging AI in Scholarly Pursuits</u></a></li>
<li><a href="https://tech-haven.techidaily.com/leveraging-chatgpt-in-therapeutic-sessions-a-guide-to-enhancing-cbt/"><u>Leveraging ChatGPT in Therapeutic Sessions: A Guide to Enhancing CBT</u></a></li>
<li><a href="https://tech-haven.techidaily.com/mastering-the-verification-process-for-medical-advice-from-ai-sources-such-as-chatgpt/"><u>Mastering the Verification Process for Medical Advice From AI Sources Such as ChatGPT</u></a></li>
<li><a href="https://tech-haven.techidaily.com/mystery-unraveled-what-is-the-new-gpt/"><u>Mystery Unraveled: What Is the New GPT?</u></a></li>
<li><a href="https://tech-haven.techidaily.com/navigating-through-potential-data-security-issues-the-hidden-dangers-of-chatbots/"><u>Navigating Through Potential Data Security Issues: The Hidden Dangers of Chatbots</u></a></li>
<li><a href="https://fox-that.techidaily.com/need-a-speedy-phone-connection-try-these-proven-methods-to-up-your-mobile-data-speed/"><u>Need a Speedy Phone Connection? Try These Proven Methods to Up Your Mobile Data Speed</u></a></li>
<li><a href="https://tech-haven.techidaily.com/nlp-versus-ml-unraveling-key-contrasts-in-ai-technologies/"><u>NLP versus ML: Unraveling Key Contrasts in AI Technologies</u></a></li>
<li><a href="https://extra-support.techidaily.com/optimal-vlog-filming-ideal-handheld-stabilizers-compared-for-2024/"><u>Optimal Vlog Filming  Ideal Handheld Stabilizers Compared for 2024</u></a></li>
<li><a href="https://tech-haven.techidaily.com/prompt-engineering-as-a-career-navigating-the-factors-that-count-for-success/"><u>Prompt Engineering as a Career - Navigating the Factors that Count for Success</u></a></li>
<li><a href="https://tech-haven.techidaily.com/revolutionize-your-brainwriting-process-with-mind-mapping-strategies-enhanced-by-chatgpt-ai/"><u>Revolutionize Your Brainwriting Process with Mind Mapping Strategies Enhanced by ChatGPT AI</u></a></li>
<li><a href="https://tech-haven.techidaily.com/start-today-with-our-handpicked-selection-of-8-versatile-custom-gpts/"><u>Start Today with Our Handpicked Selection of 8 Versatile Custom GPTs</u></a></li>
<li><a href="https://tech-haven.techidaily.com/step-by-step-guide-erasing-your-presence-on-chatgpt/"><u>Step-by-Step Guide: Erasing Your Presence on ChatGPT</u></a></li>
<li><a href="https://tech-haven.techidaily.com/synthesizing-pros-and-cons-ai-in-the-writers-realm/"><u>Synthesizing Pros & Cons: AI in the Writer's Realm</u></a></li>
<li><a href="https://tech-haven.techidaily.com/the-seventh-wave-ais-role-in-workforce-change/"><u>The Seventh Wave: AI's Role in Workforce Change</u></a></li>
<li><a href="https://tech-haven.techidaily.com/top-5-strategies-how-pupils-utilize-chatgpt-for-academic-success/"><u>Top 5 Strategies: How Pupils Utilize ChatGPT for Academic Success</u></a></li>
<li><a href="https://tech-haven.techidaily.com/top-9-chatgpt-hacks-to-simplify-your-daily-routine/"><u>Top 9 ChatGPT Hacks to Simplify Your Daily Routine</u></a></li>
<li><a href="https://tech-haven.techidaily.com/transform-your-games-storyline-with-these-6-innovative-uses-of-chatgpt/"><u>Transform Your Game's Storyline with These 6 Innovative Uses of ChatGPT</u></a></li>
<li><a href="https://tech-haven.techidaily.com/unblock-your-account-tackling-four-major-issues/"><u>Unblock Your Account: Tackling Four Major Issues</u></a></li>
<li><a href="https://tech-haven.techidaily.com/understanding-chatgpts-performance-a-look-at-why-chatgpt-4-lags-behind-chatgpt-35/"><u>Understanding ChatGPT's Performance: A Look at Why ChatGPT-4 Lags Behind ChatGPT- 3.5</u></a></li>
<li><a href="https://some-approaches.techidaily.com/unleash-the-potential-of-ifunnys-meme-application-for-2024/"><u>Unleash the Potential of iFunny’s Meme Application for 2024</u></a></li>
<li><a href="https://tech-haven.techidaily.com/unleashing-the-power-6-ways-to-utilize-chatgpts-programming-capabilities/"><u>Unleashing the Power: 6 Ways to Utilize ChatGPT’s Programming Capabilities</u></a></li>
<li><a href="https://tech-haven.techidaily.com/unlocking-new-features-in-chatgpt-an-insight-into-custom-instruction-functionality/"><u>Unlocking New Features in ChatGPT - An Insight Into Custom Instruction Functionality</u></a></li>
<li><a href="https://tech-haven.techidaily.com/unlocking-the-power-of-distributing-your-ai-interactions/"><u>Unlocking the Power of Distributing Your AI Interactions</u></a></li>
<li><a href="https://tech-haven.techidaily.com/unveiling-the-next-era-of-web-browsing-microsoft-brings-powerful-ai-to-revolutionize-bings-search-capabilities/"><u>Unveiling the Next Era of Web Browsing: Microsoft Brings Powerful AI to Revolutionize Bing's Search Capabilities</u></a></li>
<li><a href="https://tech-haven.techidaily.com/using-a-vpn-how-to-connect-with-chatgpt-securely/"><u>Using a VPN: How to Connect with ChatGPT Securely</u></a></li>
<li><a href="https://tech-haven.techidaily.com/utilizing-chatgpt-plus-for-efficient-and-effective-language-learning-strategies/"><u>Utilizing ChatGPT Plus for Efficient and Effective Language Learning Strategies</u></a></li>
<li><a href="https://tech-haven.techidaily.com/verse-virtuosos-vs-artificial-shepherds-purebred-alpacas-rivalry/"><u>Verse Virtuosos vs Artificial Shepherds, Purebred Alpacas' Rivalry</u></a></li>
<li><a href="https://tech-haven.techidaily.com/vital-considerations-before-leveraging-chatgpt-in-mental-health-practices/"><u>Vital Considerations Before Leveraging ChatGPT in Mental Health Practices</u></a></li>
<li><a href="https://tech-haven.techidaily.com/what-is-emotion-ai-and-can-it-really-understand-our-feelings/"><u>What Is Emotion AI and Can It Really Understand Our Feelings?</u></a></li>
<li><a href="https://fake-location.techidaily.com/wondering-the-best-alternative-to-hola-on-xiaomi-redmi-note-12-pro-5g-here-is-the-answer-drfone-by-drfone-virtual-android/"><u>Wondering the Best Alternative to Hola On Xiaomi Redmi Note 12 Pro 5G? Here Is the Answer | Dr.fone</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2048972/16384" target="_top" id="2048972"><img src="//a.impactradius-go.com/display-ad/16384-2048972" border="0" alt="" width="1200" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2048972/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->