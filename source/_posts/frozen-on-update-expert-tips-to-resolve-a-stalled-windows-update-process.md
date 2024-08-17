---
title: "Frozen on Update: Expert Tips to Resolve a Stalled Windows Update Process"
date: 2024-08-16T10:02:48.720Z
updated: 2024-08-17T10:02:48.720Z
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
<li><a href="https://fox-links.techidaily.com/new-from-raw-footage-to-high-quality-mpeg-youtube-conversion-techniques-for-2024/"><u>[New] From Raw Footage to High-Quality MPEG  YouTube Conversion Techniques for 2024</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-top-30-beginner-pro-facebook-strategies-for-boosting-sales-for-2024/"><u>[Updated] Top 30 Beginner-Pro Facebook Strategies for Boosting Sales for 2024</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-mastering-the-art-of-adjusting-netflix-pace-settings/"><u>2024 Approved  Mastering the Art of Adjusting Netflix Pace Settings</u></a></li>
<li><a href="https://tech-haven.techidaily.com/a-failing-frontline-in-the-cyber-realm/"><u>A Failing Frontline in the Cyber Realm</u></a></li>
<li><a href="https://tech-haven.techidaily.com/a-step-by-step-guide-to-boosting-eq-with-conversational-ai-technology/"><u>A Step-by-Step Guide to Boosting EQ with Conversational AI Technology</u></a></li>
<li><a href="https://tech-haven.techidaily.com/advanced-ai-based-tools-and-platforms-for-enhanced-online-search-capabilities/"><u>Advanced AI Based Tools and Platforms for Enhanced Online Search Capabilities</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-common-windows-camera-app-malfunctions/"><u>Fixing Common Windows Camera App Malfunctions</u></a></li>
<li><a href="https://tech-haven.techidaily.com/google-palm-2-versus-openai-gpt-4-a-deep-dive-into-their-unique-features/"><u>Google PaLM 2 Versus OpenAI GPT-4: A Deep Dive Into Their Unique Features</u></a></li>
<li><a href="https://techidaily.com/hard-reset-poco-f5-pro-5g-in-3-efficient-ways-drfone-by-drfone-reset-android-reset-android/"><u>Hard Reset Poco F5 Pro 5G in 3 Efficient Ways | Dr.fone</u></a></li>
<li><a href="https://technical-tips.techidaily.com/how-to-achieve-viral-status-on-tiktok-the-top-10-essentials-you-need-to-know/"><u>How to Achieve Viral Status on TikTok: The Top 10 Essentials You Need to Know</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-lock-apps-on-motorola-moto-g14-to-protect-your-individual-information-by-drfone-android/"><u>How to Lock Apps on Motorola Moto G14 to Protect Your Individual Information</u></a></li>
<li><a href="https://tech-haven.techidaily.com/ignite-your-wordsmith-potential-leveraging-chatgpt-to-transform-creative-writing/"><u>Ignite Your Wordsmith Potential: Leveraging ChatGPT to Transform Creative Writing</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-full-guide-to-bypass-vivo-y36i-frp-by-drfone-android/"><u>In 2024, Full Guide to Bypass Vivo Y36i FRP</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-list-of-pokemon-go-joysticks-on-samsung-galaxy-z-fold-5-drfone-by-drfone-virtual-android/"><u>In 2024, List of Pokémon Go Joysticks On Samsung Galaxy Z Fold 5 | Dr.fone</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-the-key-steps-to-composing-engaging-youtube-video-plans/"><u>In 2024, The Key Steps to Composing Engaging YouTube Video Plans</u></a></li>
<li><a href="https://tech-haven.techidaily.com/in-depth-comparison-can-github-copilot-outperform-chatgpt-in-coding/"><u>In-Depth Comparison: Can GitHub Copilot Outperform ChatGPT in Coding?</u></a></li>
<li><a href="https://tech-haven.techidaily.com/influence-and-impact-a-step-by-step-strategy-for-convincing-proposals-via-chatgpt/"><u>Influence and Impact: A Step-by-Step Strategy for Convincing Proposals via ChatGPT</u></a></li>
<li><a href="https://extra-support.techidaily.com/laugh-labs-free-comedy-creation-for-creative-souls-for-2024/"><u>Laugh Labs  Free Comedy Creation for Creative Souls for 2024</u></a></li>
<li><a href="https://tech-haven.techidaily.com/learning-through-dialogue-can-chatgpt-adapt-from-conversations-with-people/"><u>Learning Through Dialogue: Can ChatGPT Adapt From Conversations With People?</u></a></li>
<li><a href="https://tech-haven.techidaily.com/leveraging-chatgpt-for-enhanced-sound-creation-within-a-music-production-software-environment/"><u>Leveraging ChatGPT for Enhanced Sound Creation Within a Music Production Software Environment</u></a></li>
<li><a href="https://tech-haven.techidaily.com/maximizing-your-academic-success-leveraging-chatgpt-in-research-and-writing-assignments/"><u>Maximizing Your Academic Success: Leveraging ChatGPT in Research & Writing Assignments</u></a></li>
<li><a href="https://tech-haven.techidaily.com/mistral-ais-le-chat-in-focus-how-it-stacks-up-against-the-renowned-chatgpt/"><u>Mistral AI's Le Chat in Focus: How It Stacks Up Against the Renowned ChatGPT</u></a></li>
<li><a href="https://tech-haven.techidaily.com/navigating-ai-assistance-dos-and-donts-for-writers-using-chatgpt/"><u>Navigating AI Assistance: Dos and Don'ts for Writers Using ChatGPT</u></a></li>
<li><a href="https://tech-haven.techidaily.com/navigating-cyberspace-with-brainpowered-bots-the-future-of-websites-in-an-age-of-artificial-intelligence/"><u>Navigating Cyberspace with Brainpowered Bots: The Future of Websites in an Age of Artificial Intelligence</u></a></li>
<li><a href="https://tech-haven.techidaily.com/online-whispers-and-silent-audiences-demystifying-the-dead-internet-theory/"><u>Online Whispers and Silent Audiences: Demystifying the 'Dead Internet' Theory</u></a></li>
<li><a href="https://tech-haven.techidaily.com/protect-your-digital-life-discover-the-real-danger-behind-these-9-deceptive-chatgpt-linked-viruses-and-malwares/"><u>Protect Your Digital Life: Discover the Real Danger Behind These 9 Deceptive ChatGPT-Linked Viruses and Malwares</u></a></li>
<li><a href="https://tech-haven.techidaily.com/protecting-patient-privacy-using-ai-like-chatgpt-responsibly-in-counseling/"><u>Protecting Patient Privacy: Using AI Like ChatGPT Responsibly in Counseling</u></a></li>
<li><a href="https://review-topics.techidaily.com/recover-your-music-after-zte-blade-a73-5g-has-been-deleted-by-fonelab-android-recover-music/"><u>Recover your music after ZTE Blade A73 5G has been deleted</u></a></li>
<li><a href="https://tech-haven.techidaily.com/safeguarding-creations-againnst-ai-with-nightshade-techniques/"><u>Safeguarding Creations Againnst AI with Nightshade Techniques</u></a></li>
<li><a href="https://tech-haven.techidaily.com/save-time-on-document-management-discover-the-best-10-pdf-plugin-solutions-inspired-by-chatgpt/"><u>Save Time on Document Management: Discover the Best 10 PDF Plugin Solutions Inspired by ChatGPT</u></a></li>
<li><a href="https://tech-haven.techidaily.com/seamless-integration-tutorial-using-chatgpt-for-automated-support-on-whatsapp/"><u>Seamless Integration Tutorial: Using ChatGPT for Automated Support on WhatsApp</u></a></li>
<li><a href="https://win-solutions.techidaily.com/star-wars-battlefront-ii-error-resolution-overcoming-error-code-327-for-uninterrupted-fun/"><u>Star Wars Battlefront II Error Resolution – Overcoming Error Code 327 for Uninterrupted Fun</u></a></li>
<li><a href="https://tech-haven.techidaily.com/streamline-your-journey-explore-7-free-ai-tools-and-chatgpt-apps-for-fast-trip-organization/"><u>Streamline Your Journey: Explore 7 Free AI Tools & ChatGPT Apps for Fast Trip Organization</u></a></li>
<li><a href="https://tech-haven.techidaily.com/the-key-factors-you-must-evaluate-before-using-chatgpt-as-a-mental-health-tool/"><u>The Key Factors You Must Evaluate Before Using ChatGPT as a Mental Health Tool</u></a></li>
<li><a href="https://tech-haven.techidaily.com/the-rise-of-bard-googles-artificial-intelligence-set-to-take-on-chatgpt/"><u>The Rise of Bard: Google's Artificial Intelligence Set to Take on ChatGPT</u></a></li>
<li><a href="https://tech-haven.techidaily.com/the-ultimate-decision-which-bot-will-triumph/"><u>The Ultimate Decision: Which Bot Will Triumph?</u></a></li>
<li><a href="https://tech-haven.techidaily.com/1721809986180-the-ultimate-guide-to-choosing-your-ai-sidekick-chatgpt-versus-microsofts-bing-chat/"><u>The Ultimate Guide to Choosing Your AI Sidekick: ChatGPT Versus Microsoft's Bing Chat.</u></a></li>
<li><a href="https://tech-haven.techidaily.com/the-ultimate-guide-to-high-volume-content-design-using-canva-and-chatgpt/"><u>The Ultimate Guide to High-Volume Content Design Using Canva & ChatGPT</u></a></li>
<li><a href="https://android-location-track.techidaily.com/top-10-best-spy-watches-for-your-oppo-a1-5g-drfone-by-drfone-virtual-android/"><u>Top 10 Best Spy Watches For your Oppo A1 5G | Dr.fone</u></a></li>
<li><a href="https://tech-haven.techidaily.com/top-5-substitute-options-for-openais-sora-offering-no-cost-access-to-state-of-the-art-ai/"><u>Top 5 Substitute Options for OpenAI's Sora, Offering No Cost Access to State-of-the-Art AI</u></a></li>
<li><a href="https://tech-haven.techidaily.com/transform-your-interview-skills-with-chatgpt-strategies-and-tips/"><u>Transform Your Interview Skills with ChatGPT Strategies and Tips</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/ultimate-shooter-showdown-our-best-picks/"><u>Ultimate Shooter Showdown - Our Best Picks</u></a></li>
<li><a href="https://tech-haven.techidaily.com/understanding-generative-artificn-intelligence-an-in-depth-guide/"><u>Understanding Generative Artificn Intelligence: An In-Depth Guide</u></a></li>
<li><a href="https://tech-haven.techidaily.com/unlocking-clause-2-uses-demystified/"><u>Unlocking Clause 2: Uses Demystified</u></a></li>
<li><a href="https://tech-haven.techidaily.com/unlocking-gpts-boundaries-an-overview/"><u>Unlocking GPT's Boundaries: An Overview</u></a></li>
<li><a href="https://tech-haven.techidaily.com/which-bot-wins-gpt-plus-or-perplexity-face-off/"><u>Which Bot Wins? GPT Plus or Perplexity Face-Off</u></a></li>
<li><a href="https://driver-install.techidaily.com/windows-software-hp-p1102w-firmware/"><u>Windows Software: HP P1102w Firmware</u></a></li>
<li><a href="https://tech-haven.techidaily.com/worth-the-price-tag-a-deep-dive-into-chatgpt-plus-benefits/"><u>Worth the Price Tag: A Deep Dive Into ChatGPT Plus Benefits</u></a></li>
<li><a href="https://tech-haven.techidaily.com/your-path-to-advanced-interactions-with-new-chatgpt-extensions/"><u>Your Path to Advanced Interactions with New ChatGPT Extensions</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://coinrule.sjv.io/c/5597632/1958379/18409" target="_top" id="1958379"><img src="//a.impactradius-go.com/display-ad/18409-1958379" border="0" alt="" width="856" height="508"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1958379/18409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->