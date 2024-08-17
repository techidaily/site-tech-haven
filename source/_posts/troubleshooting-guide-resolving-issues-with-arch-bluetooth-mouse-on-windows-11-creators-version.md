---
title: "Troubleshooting Guide: Resolving Issues with Arch Bluetooth Mouse on Windows 11 Creators Version"
date: 2024-08-16T10:08:40.452Z
updated: 2024-08-17T10:08:40.452Z
tags:
  - win11
  - win10
  - win7
categories:
  - driver
description: "This Article Describes Troubleshooting Guide: Resolving Issues with Arch Bluetooth Mouse on Windows 11 Creators Version"
excerpt: "This Article Describes Troubleshooting Guide: Resolving Issues with Arch Bluetooth Mouse on Windows 11 Creators Version"
thumbnail: https://thmb.techidaily.com/9304676ddebde0491fac069817e2e83439806cdb3bbe061f637b22cd4655ca5f.jpg
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
<li><a href="https://screen-recording.techidaily.com/new-2024-approved-tips-to-reduce-compression-artifacts-in-obs/"><u>[New] 2024 Approved  Tips to Reduce Compression Artifacts in OBS</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-anonymous-insights-best-story-viewing-apps/"><u>[New] Anonymous Insights  Best Story-Viewing Apps</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-creative-product-launches/"><u>[New] Creative Product Launches</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-dissecting-biggest-fifa-footage-trends-in-graphs-for-2024/"><u>[New] Dissecting Biggest FIFA Footage Trends in Graphs for 2024</u></a></li>
<li><a href="https://fox-links.techidaily.com/new-humor-hacks-simplifying-the-process-of-meme-creation-for-2024/"><u>[New] Humor Hacks  Simplifying the Process of Meme Creation for 2024</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/n-2024-a-quick-guide-to-chroma-key-background/"><u>[New] In 2024, A Quick Guide to Chroma Key Background</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-in-2024-master-10-social-media-movies/"><u>[New] In 2024, Master 10 Social-Media Movies</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-soaring-strengths-top-10-industrial-drones/"><u>[New] Soaring Strengths  Top 10 Industrial Drones</u></a></li>
<li><a href="https://extra-skills.techidaily.com/professional-guide-essential-fixes-for-dull-iphone-hdr-videos-in-adobe-for-2024/"><u>[Professional Guide] Essential Fixes for Dull iPhone HDR Videos in Adobe for 2024</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-leveraging-youtube-and-apple-tv-integration-for-enhanced-fb-video-watching/"><u>[Updated] Leveraging YouTube & Apple TV Integration for Enhanced FB Video Watching</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-navigating-windows-10-features-for-seamless-video-editing/"><u>[Updated] Navigating Windows 10 Features for Seamless Video Editing</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/2024-approved-expertly-edit-extravagant-tiktoks-your-key-to-less-overloaded-drafts/"><u>2024 Approved  Expertly Edit Extravagant TikToks  Your Key to Less Overloaded Drafts</u></a></li>
<li><a href="https://fox-access.techidaily.com/2024-approved-illuminated-influence-elevating-your-cinematic-presentations/"><u>2024 Approved  Illuminated Influence  Elevating Your Cinematic Presentations</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-precision-and-performance-in-the-dell-p2715q-monitor-analysis/"><u>2024 Approved  Precision and Performance in the Dell P2715Q Monitor Analysis</u></a></li>
<li><a href="https://tech-haven.techidaily.com/6-innovative-ways-to-utilize-chatgpt-for-job-seekers-and-workers/"><u>6 Innovative Ways to Utilize ChatGPT for Job Seekers & Workers</u></a></li>
<li><a href="https://tech-haven.techidaily.com/7-ways-that-chatgpt-is-already-being-used-in-the-wild/"><u>7 Ways That ChatGPT Is Already Being Used in the Wild</u></a></li>
<li><a href="https://tech-haven.techidaily.com/8-dall-e-3-prompts-for-your-next-image/"><u>8 DALL-E 3 Prompts for Your Next Image</u></a></li>
<li><a href="https://tech-haven.techidaily.com/a-comprehensive-guide-to-openais-shapley-explainer-shape-features-and-uses/"><u>A Comprehensive Guide to OpenAI's Shapley Explainer (ShapE): Features & Uses</u></a></li>
<li><a href="https://tech-haven.techidaily.com/a-deep-dive-into-artificial-intelligence-prompts-assessing-its-viability-as-a-reliable-profession/"><u>A Deep Dive Into Artificial Intelligence Prompts: Assessing Its Viability as a Reliable Profession</u></a></li>
<li><a href="https://tech-haven.techidaily.com/a-timeline-to-artificial-intelligences-beginnings/"><u>A Timeline to Artificial Intelligence's Beginnings</u></a></li>
<li><a href="https://tech-haven.techidaily.com/1722016610906-access-chatgpt-anywhere-with-the-new-android-app/"><u>Access ChatGPT Anywhere with the New Android App</u></a></li>
<li><a href="https://tech-haven.techidaily.com/ace-your-application-with-these-6-creative-uses-of-chatgpt-in-job-searches/"><u>Ace Your Application with These 6 Creative Uses of ChatGPT in Job Searches</u></a></li>
<li><a href="https://tech-haven.techidaily.com/adaptive-technology-start-with-your-8-customized-models-now/"><u>Adaptive Technology: Start with Your 8 Customized Models Now</u></a></li>
<li><a href="https://tech-haven.techidaily.com/ai-agent-implementation-through-browser-with-agentgpt-tutorials/"><u>AI Agent Implementation Through Browser with AgentGPT Tutorials</u></a></li>
<li><a href="https://tech-haven.techidaily.com/ai-assistant-faceoff-which-reigns-supreme-chatgpt-or-hugbingchat/"><u>AI Assistant Faceoff: Which Reigns Supreme, ChatGPT or HugbingChat?</u></a></li>
<li><a href="https://tech-haven.techidaily.com/ai-chat-guidelines-sidestep-the-top-6-errors-in-dialogue/"><u>AI Chat Guidelines: Sidestep the Top 6 Errors in Dialogue</u></a></li>
<li><a href="https://tech-haven.techidaily.com/ai-humor-evaluation-does-chatgpt-have-what-it-takes-to-joke-and-laugh-with-us/"><u>AI Humor Evaluation: Does ChatGPT Have What It Takes to Joke and Laugh with Us?</u></a></li>
<li><a href="https://tech-haven.techidaily.com/ai-leap-from-gpt-35-to-gpt-4-discovering-the-five-essential-differences-explored/"><u>AI Leap From GPT-3.5 to GPT-4: Discovering the Five Essential Differences Explored</u></a></li>
<li><a href="https://tech-haven.techidaily.com/ai-ushers-new-era-key-capabilities-we-expect-in-gpt-5/"><u>AI Ushers New Era: Key Capabilities We Expect in GPT-5</u></a></li>
<li><a href="https://tech-haven.techidaily.com/ai-driven-research-the-new-norm-for-students/"><u>AI-Driven Research: The New Norm for Students</u></a></li>
<li><a href="https://tech-haven.techidaily.com/ais-role-in-future-dev-workflows/"><u>AI's Role in Future Dev Workflows</u></a></li>
<li><a href="https://tech-haven.techidaily.com/assessing-chatgpts-ability-to-design-and-describe-cocktails/"><u>Assessing ChatGPT's Ability to Design and Describe Cocktails</u></a></li>
<li><a href="https://activate-lock.techidaily.com/best-ways-to-bypass-icloud-activation-lock-from-apple-iphone-13ipadipod-by-drfone-ios/"><u>Best Ways to Bypass iCloud Activation Lock from Apple iPhone 13/iPad/iPod</u></a></li>
<li><a href="https://howto.techidaily.com/cellular-network-not-available-for-voice-calls-on-tecno-spark-20-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Cellular Network Not Available for Voice Calls On Tecno Spark 20 | Dr.fone</u></a></li>
<li><a href="https://tech-haven.techidaily.com/1722081567492-chatgpt-for-fun-check-out-the-6-best-games-you-can-play/"><u>ChatGPT for Fun? Check Out the 6 Best Games You Can Play!</u></a></li>
<li><a href="https://tech-haven.techidaily.com/1722139473883-chatgpt-on-iphone-not-responding-apply-any-of-our-9-proven-strategies/"><u>ChatGPT on iPhone Not Responding? Apply Any of Our 9 Proven Strategies</u></a></li>
<li><a href="https://tech-haven.techidaily.com/1722146022547-explore-the-new-chatgpt-mobile-app-now-available-on-ios-devices/"><u>Explore the New ChatGPT Mobile App Now Available on iOS Devices</u></a></li>
<li><a href="https://tech-haven.techidaily.com/1722106342965-exploring-the-viability-of-using-chatgpt-to-enhance-your-writing-through-proofreading-assistance/"><u>Exploring the Viability of Using ChatGPT to Enhance Your Writing Through Proofreading Assistance.</u></a></li>
<li><a href="https://tech-haven.techidaily.com/1722211196472-free-local-instance-of-gpt-4-allowed-by-gpt4all-get-set-up-in-minutes/"><u>Free Local Instance of GPT-4 Allowed by GPT4All – Get Set Up in Minutes!</u></a></li>
<li><a href="https://tech-haven.techidaily.com/1722087581066-how-excel-outperforms-chatgpt-in-data-management-discover-3-ways/"><u>How Excel Outperforms ChatGPT in Data Management - Discover 3 Ways</u></a></li>
<li><a href="https://tech-haven.techidaily.com/1722120349133-how-palm-2-elevates-googles-bard-ai-discover-7-key-upgrades/"><u>How PaLM 2 Elevates Google's Bard AI - Discover 7 Key Upgrades</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-leave-a-life360-group-on-realme-12-5g-without-anyone-knowing-drfone-by-drfone-virtual-android/"><u>How To Leave a Life360 Group On Realme 12 5G Without Anyone Knowing? | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-bypassing-google-account-with-vnrom-bypass-for-vivo-s18-by-drfone-android/"><u>In 2024, Bypassing Google Account With vnROM Bypass For Vivo S18</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/mastering-mac-screenshots-and-screen-recording-for-2024/"><u>Mastering Mac Screenshots & Screen Recording for 2024</u></a></li>
<li><a href="https://tech-haven.techidaily.com/1722120515701-navigate-through-the-best-free-ai-image-synthesis-programs-our-open-source-selection/"><u>Navigate Through the Best Free AI Image Synthesis Programs – Our Open Source Selection!</u></a></li>
<li><a href="https://tech-haven.techidaily.com/1722184338031-no-subscriptions-for-gpt-4-however-select-plus-membership-retains-its-unique-6-features/"><u>No Subscriptions for GPT-4: However, Select Plus Membership Retains Its Unique 6 Features</u></a></li>
<li><a href="https://extra-support.techidaily.com/optimal-viewing-and-audio-top-webcams-for-podcast-creators-for-2024/"><u>Optimal Viewing & Audio  Top Webcams for Podcast Creators for 2024</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/step-by-step-designing-striking-youtube-thumbnails-with-macos/"><u>Step-by-Step  Designing Striking Youtube Thumbnails with macOS</u></a></li>
<li><a href="https://win-dash.techidaily.com/step-by-step-guide-upgrading-and-downloading-tb16-drivers-for-optimal-performance-on-a-dell-thunderbolt-dock/"><u>Step-by-Step Guide: Upgrading and Downloading TB16 Drivers for Optimal Performance on a Dell Thunderbolt Dock</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/step-by-step-strategy-for-unearthing-secret-youtube-videos/"><u>Step-by-Step Strategy for Unearthing Secret YouTube Videos</u></a></li>
<li><a href="https://fake-location.techidaily.com/the-best-8-vpn-hardware-devices-reviewed-on-asus-rog-phone-7-ultimate-drfone-by-drfone-virtual-android/"><u>The Best 8 VPN Hardware Devices Reviewed On Asus ROG Phone 7 Ultimate | Dr.fone</u></a></li>
<li><a href="https://tech-haven.techidaily.com/1722212047230-the-secrets-of-successfully-engaging-with-openais-bug-bounty-program-top-strategies-revealed/"><u>The Secrets of Successfully Engaging with OpenAI's Bug Bounty Program – Top Strategies Revealed!</u></a></li>
<li><a href="https://extra-resources.techidaily.com/threefold-technique-to-tame-iphone-video-tremors/"><u>Threefold Technique to Tame iPhone Video Tremors</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/undercover-echo-enthusiasts-6-hidden-voice-capture-apps/"><u>Undercover Echo Enthusiasts  6 Hidden Voice Capture Apps</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/unveiling-gadgets-with-toms-computer-and-electronics/"><u>Unveiling Gadgets with Tom's Computer & Electronics</u></a></li>
<li><a href="https://tech-haven.techidaily.com/1722201689537-waiting-for-chatgpts-desktop-version-is-tough-heres-a-great-free-software-replacement/"><u>Waiting for ChatGPT's Desktop Version Is Tough – Here’s a Great, Free Software Replacement!</u></a></li>
<li><a href="https://tech-haven.techidaily.com/1721926571623-what-is-behind-elon-musks-bold-claims-exploring-the-revolutionary-concept-of-truthgpt/"><u>What Is Behind Elon Musk's Bold Claims? Exploring the Revolutionary Concept of TruthGPT</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/what-legendaries-are-in-pokemon-platinum-on-poco-x5-pro-drfone-by-drfone-virtual-android/"><u>What Legendaries Are In Pokemon Platinum On Poco X5 Pro? | Dr.fone</u></a></li>
<li><a href="https://sound-issues.techidaily.com/windows-7-microphone-not-functioning-heres-how-to-fix-it-step-by-step/"><u>Windows 7 Microphone Not Functioning? Here's How to Fix It Step-by-Step</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BEducational%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/educational-970x90.gif" border="0"></a>
<!-- affiliate ads end -->