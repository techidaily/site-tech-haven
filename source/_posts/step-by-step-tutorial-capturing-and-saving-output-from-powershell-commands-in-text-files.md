---
title: "Step-by-Step Tutorial: Capturing and Saving Output From PowerShell Commands in Text Files"
date: 2024-08-29T02:14:03.357Z
updated: 2024-08-30T02:14:03.357Z
tags:
  - deals
categories:
  - tech
thumbnail: https://thmb.techidaily.com/d1f3ab1e0f303254b5da0d1c46b4cd5df7801fb77b72cd0a87c2f6333bdfc5bd.jpg
---

## Step-by-Step Tutorial: Capturing and Saving Output From PowerShell Commands in Text Files

### Quick Links

* [Send a PowerShell Command's Output to a Text File](https://eaxpv-info.techidaily.com/new-free-mobile-downloader-the-ultimate-apps-for-video-buffs-for-2024/)
* [Send a PowerShell Command's Output to a CSV File](https://facebook-record-videos.techidaily.com/updated-2024-approved-effortless-rearrangement-of-your-personalized-lists/)
* [View Your Text or CSV File’s Contents in PowerShell](https://some-guidance.techidaily.com/in-2024-the-ultimate-playbook-iphone-downloading-for-podcast-enthusiasts/)

### Key Takeaways

* To save a PowerShell command's output to a TXT file, type the command, press Spacebar, type the > (greater than) symbol, press Spacebar, and type the full path to the TXT file.
* To generate a CSV file from a PowerShell command, type your command, press Spacebar, type the | (pipe) sign, press Spacebar, type "Export-CSV", press Spacebar, enter the full path to the CSV file, press Spacebar, type "-NoTypeInformation", and press Enter.

 Do you want to save your PowerShell command’s result in a TXT (text) or CSV (comma-separated values) file on your computer? If so, it's easy to do, and we'll show you how on your Windows 11 or Windows 10 PC.

<!-- affiliate ads begin -->
<a href="https://tokenmetrics.sjv.io/c/5597632/1864921/20702" target="_top" id="1864921"><img src="//a.impactradius-go.com/display-ad/20702-1864921" border="0" alt="" width="1251" height="1042"/></a>
<!-- affiliate ads end -->
##  Send a PowerShell Command's Output to a Text File

 To write your PowerShell command’s output to a text (TXT) file, first [launch a PowerShell window](https://techtrends.techidaily.com/what-are-the-stages-in-a-game-of-royal-match/). Here, type whatever command you need, the output of which you want in a text file. After you’ve typed the command, press Spacebar, type the > (greater than) symbol, press Spacebar, enter the full path to the text file where you want to save the output, and press Enter.

 For example, if you want to save the “[systeminfo](https://tech-haven.techidaily.com/has-chatgpt-simplified-or-compromised-academic-writings/)” command’s output to a file named "SystemInfo.txt" on your desktop, your command will look something like the following:

systeminfo > C:\Users\mahes\Desktop\SystemInfo.txt

!['systeminfo' command highlighted on a PowerShell window.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/10/1-systeminfo-command-output-txt-file.jpg) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=19080710&QTY=1&AFFILIATE=108875&CART=1"><img src="https://smart-seo-tool.com/images/SmartSEOAuditorBox.png" border="0"></a>
<!-- affiliate ads end -->
 As soon as you press Enter, PowerShell creates your specified file and adds your command’s result to it. When that’s done, access your specified path, and you’ll find your newly created file there.

<!-- affiliate ads begin -->

<!-- affiliate ads end -->
##  Send a PowerShell Command's Output to a CSV File

 If you want to create a CSV file containing the output of your specified PowerShell command, use the tool’s "Export-CSV" [cmdlet](https://extra-guidance.techidaily.com/new-prophotomaster-the-ai-enhanced-editing-edge/).

 To do that, launch PowerShell. Here, enter your command (the results of which you want in a CSV file). Then, press Spacebar, enter the | (pipe) sign, press Spacebar, enter "Export-CSV", press Spacebar, enter the full path to the CSV file you want to create, press Spacebar, type "-NoTypeInformation", and press Enter.

 For example, if you want to save the current directory’s item list in a file called "List.csv" on your desktop, you’d use a command that looks like the following. Note that the "NoTypeInformation" parameter here tells the command not to include the #TYPE information header in your CSV file.

Get-ChildItem | Export-CSV C:\Users\mahes\Desktop\List.csv -NoTypeInformation

!['Get-ChildItem' cmdlet highlighted in PowerShell.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/10/2-directory-item-csv-file.jpg) 

<!-- affiliate ads begin -->
<a href="https://caperobbin.sjv.io/c/5597632/2006118/18460" target="_top" id="2006118"><img src="//a.impactradius-go.com/display-ad/18460-2006118" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2006118/18460" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 When you’ve finished running the command, you’ll have a file called "List.csv" on your desktop containing the list of the items in your current directory.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075482/7443" target="_top" id="2075482"><img src="//a.impactradius-go.com/display-ad/7443-2075482" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075482/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
##  View Your Text or CSV File’s Contents in PowerShell

 You can view your newly created text or CSV file’s contents right inside PowerShell. You don’t have to leave the tool and use another app to open your files.

 To do that, open a PowerShell window, type the following command, replacing "PATH" with the full path to your text or CSV file, and press Enter.

Type PATH

 For example, if you want to [read the contents of a file](https://tiktok-video-files.techidaily.com/updated-key-points-to-consider-when-navigating-tiktok-web-on-macos-for-2024/) named "SystemInfo.txt" placed on your desktop, you’d use the following command:

Type C:\Users\mahes\Desktop\SystemInfo.txt

![A TXT file's contents displayed in PowerShell using the 'Type' command.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/10/3-read-file-powershell.jpg) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=40203538&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/cc4b82e826b52ec41c810301548e8f48/products/audio-to-text-transcription-software.png" border="0">EaseText Audio to Text Converter for Windows (Personal Edition) - An intelligent tool to transcribe & convert audio to text freely </a>
<!-- affiliate ads end -->
 Instantly, PowerShell will load your file’s contents in your open window, allowing you to read the file content.

---

 And that’s all there is to know about saving your PowerShell command results in text or CSV files. Enjoy!

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
<li><a href="https://facebook-clips.techidaily.com/new-windows-and-mac-friendly-techniques-for-fb-video-download-for-2024/"><u>[New] Windows & Mac-Friendly Techniques for FB Video Download for 2024</u></a></li>
<li><a href="https://tech-haven.techidaily.com/balancing-the-scales-chatgpts-role-in-enhancing-and-hindering-creativity-in-writing/"><u>Balancing the Scales: ChatGPT’s Role in Enhancing and Hindering Creativity in Writing</u></a></li>
<li><a href="https://tech-haven.techidaily.com/banks-and-computers-are-you-protected-from-gpt-powered-cyberattacks/"><u>Banks & Computers: Are You Protected From GPT-Powered Cyberattacks?</u></a></li>
<li><a href="https://tech-haven.techidaily.com/boost-productivity-with-these-8-smart-ways-to-implement-auto-gpt-tools/"><u>Boost Productivity with These 8 Smart Ways to Implement Auto-GPT Tools</u></a></li>
<li><a href="https://tech-haven.techidaily.com/boosting-workplace-efficiency-with-onlyoffice-docspace-and-chatgpt-integration/"><u>Boosting Workplace Efficiency with ONLYOFFICE DocSpace & ChatGPT Integration</u></a></li>
<li><a href="https://tech-haven.techidaily.com/can-chatgpt-replace-me-what-jobs-will-generative-ai-replace/"><u>Can ChatGPT Replace Me? What Jobs Will Generative AI Replace?</u></a></li>
<li><a href="https://tech-haven.techidaily.com/chagpt-designed-for-you/"><u>ChaGPT: Designed for You</u></a></li>
<li><a href="https://tech-haven.techidaily.com/chatbots-unveiled-the-ai-enthusiasts-guide/"><u>Chatbots Unveiled: The AI Enthusiast's Guide</u></a></li>
<li><a href="https://tech-haven.techidaily.com/deciphering-the-mystery-detecting-fake-bingchatgpt-coins-before-youre-scammed/"><u>Deciphering the Mystery: Detecting Fake BingChatGPT Coins Before You're Scammed</u></a></li>
<li><a href="https://tech-haven.techidaily.com/decoding-progression-an-examination-and-contrast-of-every-generation-of-openais-gpt-series/"><u>Decoding Progression: An Examination and Contrast of Every Generation of OpenAI's GPT Series</u></a></li>
<li><a href="https://tech-haven.techidaily.com/delineating-artificial-intelligence-categories-comparing-strong-vs-weak-ai-concepts/"><u>Delineating Artificial Intelligence Categories: Comparing Strong Vs. Weak AI Concepts</u></a></li>
<li><a href="https://tech-haven.techidaily.com/discover-the-top-7-innovative-features-of-bard-introduced-at-google-io-2023/"><u>Discover the Top 7 Innovative Features of BARD Introduced at Google I/O 2023</u></a></li>
<li><a href="https://tech-haven.techidaily.com/discovering-truthgpt-law-enforcements-raid-on-mullvad-vpn-prime-listings-for-no-cost-computer-games-and-demystifying-mechanical-keyboards/"><u>Discovering TruthGPT: Law Enforcement's Raid on Mullvad VPN, Prime Listings for No-Cost Computer Games, and Demystifying Mechanical Keyboards</u></a></li>
<li><a href="https://tech-haven.techidaily.com/evaluating-privacy-concerns-with-chatgpt-should-users-be-worried/"><u>Evaluating Privacy Concerns with ChatGPT: Should Users Be Worried?</u></a></li>
<li><a href="https://tech-haven.techidaily.com/everyone-enjoys-gpt-4-for-free-yet-6-advantages-of-premium/"><u>Everyone Enjoys GPT-4 for Free; Yet, 6 Advantages of Premium.</u></a></li>
<li><a href="https://tech-haven.techidaily.com/fix-your-gameplay-woes-troubleshooting-persistent-wwe-2k22-pc-crashes/"><u>Fix Your Gameplay Woes: Troubleshooting Persistent WWE 2K22 PC Crashes</u></a></li>
<li><a href="https://tech-haven.techidaily.com/from-gpt-to-bert-comparing-two-landmark-nlp-techniques-in-artificial-intelligence/"><u>From GPT to BERT - Comparing Two Landmark NLP Techniques in Artificial Intelligence</u></a></li>
<li><a href="https://tech-haven.techidaily.com/how-does-an-ai-black-box-operate-unveiling-the-mystery-of-intelligent-systems/"><u>How Does an AI Black Box Operate? Unveiling the Mystery of Intelligent Systems</u></a></li>
<li><a href="https://tech-haven.techidaily.com/how-to-profit-from-spotting-code-flaws-in-openais-challenge-arena/"><u>How to Profit From Spotting Code Flaws in OpenAI's Challenge Arena</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-how-to-unlock-apple-iphone-6s-3-ways-to-unlock-by-drfone-ios/"><u>In 2024, How To Unlock Apple iPhone 6s 3 Ways To Unlock</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-infusing-life-into-text-instagram-story-animations-tips/"><u>In 2024, Infusing Life Into Text  Instagram Story Animations Tips</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/midnight-guardian-vs-sunlit-sentinel-for-2024/"><u>Midnight Guardian Vs Sunlit Sentinel for 2024</u></a></li>
<li><a href="https://tech-haven.techidaily.com/navigating-change-how-automated-content-creation-could-transform-the-video-game-industry/"><u>Navigating Change: How Automated Content Creation Could Transform the Video Game Industry</u></a></li>
<li><a href="https://audio-editing.techidaily.com/new-in-2024-proven-choices-selecting-the-top-6-costless-cloud-based-sound-editors/"><u>New In 2024, Proven Choices Selecting the Top 6 Costless Cloud-Based Sound Editors</u></a></li>
<li><a href="https://tech-haven.techidaily.com/openai-redefines-future-with-the-launch-of-innovative-gpt-4-algorithm/"><u>OpenAI Redefines Future with the Launch of Innovative GPT-4 Algorithm</u></a></li>
<li><a href="https://tech-haven.techidaily.com/quintessential-6-giants-mammoth-data-model-excellence/"><u>Quintessential 6 Giants: Mammoth Data Model Excellence</u></a></li>
<li><a href="https://tech-haven.techidaily.com/reclaim-your-privacy-the-ultimate-guide-to-exiting-gpt/"><u>Reclaim Your Privacy: The Ultimate Guide to Exiting GPT</u></a></li>
<li><a href="https://fox-glue.techidaily.com/safest-and-cutest-toy-drones-for-children/"><u>Safest and Cutest Toy Drones for Children</u></a></li>
<li><a href="https://tech-haven.techidaily.com/safety-assessment-for-gpt-browser-integrations/"><u>Safety Assessment for GPT Browser Integrations</u></a></li>
<li><a href="https://tech-haven.techidaily.com/sarah-silverman-joins-legal-battle-against-openai-and-meta-the-fight-over-artificial-intelligence/"><u>Sarah Silverman Joins Legal Battle Against OpenAI & Meta: The Fight Over Artificial Intelligence</u></a></li>
<li><a href="https://tech-haven.techidaily.com/scam-suspicions-surrounding-truthcoin/"><u>Scam Suspicions Surrounding TruthCoin</u></a></li>
<li><a href="https://tech-haven.techidaily.com/secure-your-digital-assets-blocking-ai-powered-bots-from-scoping-your-sites-content/"><u>Secure Your Digital Assets: Blocking AI-Powered Bots From Scoping Your Site's Content</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/sound-brilliance-for-podcasters-top-10-microphones-for-2024/"><u>Sound Brilliance for Podcasters  Top 10 Microphones for 2024</u></a></li>
<li><a href="https://tech-haven.techidaily.com/the-growing-problem-with-ai-safety-eight-key-factors-contributing-to-more-significant-issues/"><u>The Growing Problem with AI Safety: Eight Key Factors Contributing to More Significant Issues</u></a></li>
<li><a href="https://tech-haven.techidaily.com/the-ultimate-guide-to-personalizing-gpt-with-10-tweaks/"><u>The Ultimate Guide to Personalizing GPT with 10 Tweaks</u></a></li>
<li><a href="https://some-skills.techidaily.com/top-11-techniques-for-spectacular-color-enhancement-for-2024/"><u>Top 11 Techniques for Spectacular Color Enhancement for 2024</u></a></li>
<li><a href="https://tech-haven.techidaily.com/top-8-ai-chromium-addons-to-supercharge-your-daily-tasks-and-enhance-efficiency/"><u>Top 8 AI Chromium Addons to Supercharge Your Daily Tasks and Enhance Efficiency</u></a></li>
<li><a href="https://buynow-help.techidaily.com/top-review-of-dbpowers-600a-peak-charger-a-deep-dive-into-its-18k-mah-features/"><u>Top Review of DBPower's 600A Peak Charger: A Deep Dive Into Its 18K mAh Features</u></a></li>
<li><a href="https://techidaily.com/undelete-lost-messages-from-motorola-moto-g73-5g-by-fonelab-android-recover-messages/"><u>Undelete lost messages from Motorola Moto G73 5G</u></a></li>
<li><a href="https://tech-haven.techidaily.com/unleashing-potential-integrating-chatgpt-with-add-ons/"><u>Unleashing Potential: Integrating ChatGPT with Add-Ons</u></a></li>
<li><a href="https://tech-haven.techidaily.com/unlocking-the-secrets-of-gpt-3-at-openai-sandbox/"><u>Unlocking the Secrets of GPT-3 at OpenAI Sandbox</u></a></li>
<li><a href="https://tech-haven.techidaily.com/unraveling-predictive-ai-its-mechanism-and-functionality/"><u>Unraveling Predictive AI: Its Mechanism and Functionality</u></a></li>
<li><a href="https://tech-haven.techidaily.com/unveiling-5-key-reasons-for-the-corporate-ban-on-chatgpt-services/"><u>Unveiling 5 Key Reasons for the Corporate Ban on ChatGPT Services</u></a></li>
<li><a href="https://hardware-help.techidaily.com/update-to-newest-realtek-device-driver-for-windows-10-download-here/"><u>Update to Newest Realtek Device Driver for Windows 10 – Download Here</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/walking-dead-top-picks-for-horror-gamers/"><u>Walking Dead  Top Picks for Horror Gamers</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/where-is-the-best-place-to-catch-dratini-on-tecno-pop-7-pro-drfone-by-drfone-virtual-android/"><u>Where Is the Best Place to Catch Dratini On Tecno Pop 7 Pro | Dr.fone</u></a></li>
</ul></div>
