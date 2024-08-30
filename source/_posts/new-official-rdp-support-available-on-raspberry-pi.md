---
title: New Official RDP Support Available on Raspberry Pi
date: 2024-08-29T02:12:20.935Z
updated: 2024-08-30T02:12:20.935Z
tags:
  - desktop
categories:
  - tech
thumbnail: https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/05/8-1.png
---

## New Official RDP Support Available on Raspberry Pi

Now available in beta, Raspberry Pi Connect provides remote access to your Pi desktop from a web browser. Install the Pi Connect beta, sign in with a Raspberry Pi ID, and you're good to go.

 This is the first _official_ remote access client for Raspberry Pi. Yes, you could already establish a remote connection over [VNC](https://www.raspberrypi.com/documentation/computers/remote-access.html#vnc), but VNC is mainly for technical support and can be difficult to set up. Third-party remote access tools, while robust, may fail to keep up with major Pi OS upgrades or under-the-hood OS changes. For example, the latest Pi OS Bookworm release completely ended X remote desktop support by switching to the newer Wayland technology.

[Raspberry Pi Connect](https://www.raspberrypi.com/software/connect/) is easy to install but requires a 64-bit version of [Pi OS Bookworm](https://some-tips.techidaily.com/2024-approved-the-experts-list-of-top-vector-stock-portals/) with Wayland window server. So, hardware-wise, you're limited to the Pi 5, Pi 4, and Pi 400\. If you own an eligible Raspberry Pi but need to upgrade to OS Bookworm, go visit the [Raspberry Pi Imager](https://www.raspberrypi.com/software/).

 Once you're running Pi OS Bookworm, open a terminal window and enter the following:

sudo apt update

    
                    sudo apt upgrade

    
                    sudo apt install rpi-connect

 Reboot your Raspberry Pi and click the Connect icon (spinning wheel) icon at the right side of your menu bar. You'll be asked to sign in with a Raspberry Pi ID. Finally, you can access your Raspberry Pi from any computer by visiting the [Connect Portal](https://connect.raspberrypi.com/sign-in). It should work for both local and remote Raspberry Pi computers.

 Raspberry Pi Connect automatically turns on at startup. If you need to pause or disable this service, click the Connect icon in your Raspberry Pi's menu bar and select "Disable screen sharing" or "Sign out." If you plan on sharing Connect with other users, or if you're deeply concerned about security, I suggest enabling [enhanced logging](https://www.raspberrypi.com/documentation/services/connect.html#enable-enhanced-logging) for the service.

 As a beta app, Pi Connect may be a bit buggy. It also lacks the ability to share multiple screens at a time, so if your Pi computer is connected to multiple monitors, you may run into some weird problems. Also, if the Connect service needs to relay your traffic, you'll experience a lot of lag. The Pi Foundation currently has just one TURN relay server in the UK and doesn't know how often relaying will be required.

 For additional information and instructions, check out the [Raspberry Pi Connect documentation](https://www.raspberrypi.com/documentation/services/connect.html). The Connect service will be free forever, but traffic relays may cost money at some point, depending on how things work out.

 Source: [The Raspberry Pi Foundation](https://www.raspberrypi.com/news/raspberry-pi-connect/)

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
<li><a href="https://visual-screen-recording.techidaily.com/new-2024-approved-elite-arsenal-choosing-the-top-7-fps/"><u>[New] 2024 Approved  Elite Arsenal  Choosing the Top 7 FPS</u></a></li>
<li><a href="https://extra-hints.techidaily.com/new-audience-accessibility-switching-from-srt-to-sub/"><u>[New] Audience Accessibility  Switching From SRT to SUB</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-discover-8-trustworthy-online-content-promoters-for-2024/"><u>[New] Discover 8 Trustworthy Online Content Promoters for 2024</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-divided-footage-delight-top-cam-discussion-for-2024/"><u>[New] Divided Footage Delight  Top Cam Discussion for 2024</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ed-discover-the-art-of-curating-music-on-youtube-with-our-steps-for-2024/"><u>[Updated] Discover the Art of Curating Music on YouTube with Our Steps for 2024</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-in-2024-the-key-to-memorable-tiktok-opens-mac-edition/"><u>[Updated] In 2024, The Key to Memorable TikTok Opens - Mac Edition</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/a-comprehensive-look-at-uploading-images-to-youtube-for-2024/"><u>A Comprehensive Look at Uploading Images to YouTube for 2024</u></a></li>
<li><a href="https://tech-haven.techidaily.com/best-5-ai-assistants-for-enhancing-text-generation-in-writing-projects/"><u>Best 5 AI Assistants for Enhancing Text Generation in Writing Projects</u></a></li>
<li><a href="https://tech-haven.techidaily.com/beyond-expectations-the-birth-of-gpt-4/"><u>Beyond Expectations: The Birth of GPT-4</u></a></li>
<li><a href="https://tech-haven.techidaily.com/chatgpt-a-tool-for-banks-vulnerabilities/"><u>ChatGPT: A Tool for Banks' Vulnerabilities?</u></a></li>
<li><a href="https://tech-haven.techidaily.com/claudio-and-chatgpt-showdown-determining-top-ai-helper-for-your-routine-needs/"><u>Claudio and ChatGPT Showdown: Determining Top AI Helper for Your Routine Needs</u></a></li>
<li><a href="https://tech-haven.techidaily.com/delving-into-prompt-engineering-job-opportunities-9-crucial-elements-for-your-decision/"><u>Delving Into Prompt Engineering Job Opportunities - 9 Crucial Elements for Your Decision</u></a></li>
<li><a href="https://driver-download.techidaily.com/direct-download-links-newest-nvidia-geforce-rtx-cufft-driver-for-microsoft-windows-64-bit/"><u>Direct Download Links: Newest Nvidia GeForce RTX cuFFT Driver For Microsoft Windows (64-Bit)</u></a></li>
<li><a href="https://tech-haven.techidaily.com/enhancing-emotional-awareness-mastering-eq-with-chatgpt/"><u>Enhancing Emotional Awareness: Mastering EQ with ChatGPT</u></a></li>
<li><a href="https://tech-haven.techidaily.com/enhancing-excel-experience-3-powerful-chatgpt-applications/"><u>Enhancing Excel Experience: 3 Powerful ChatGPT Applications</u></a></li>
<li><a href="https://tech-haven.techidaily.com/ensuring-online-safety-top-5-methods-for-kids-to-use-chatgpt-responsibly/"><u>Ensuring Online Safety: Top 5 Methods for Kids to Use ChatGPT Responsibly</u></a></li>
<li><a href="https://technical-tips.techidaily.com/expertly-curated-list-of-preferred-visual-voicemail-platforms/"><u>Expertly Curated List of Preferred Visual Voicemail Platforms</u></a></li>
<li><a href="https://tech-haven.techidaily.com/exploring-the-advantages-and-disadvantages-of-utilizing-chatgpt-in-creative-composition/"><u>Exploring the Advantages & Disadvantages of Utilizing ChatGPT in Creative Composition</u></a></li>
<li><a href="https://tech-haven.techidaily.com/exploring-the-veracity-of-chatgpt-uncovering-potential-lies/"><u>Exploring the Veracity of ChatGPT: Uncovering Potential Lies</u></a></li>
<li><a href="https://tech-haven.techidaily.com/from-language-model-to-game-master-chatgpts-surprising-gaming-features-here-are-the-best/"><u>From Language Model to Game Master: ChatGPT's Surprising Gaming Features - Here Are The Best!</u></a></li>
<li><a href="https://tech-haven.techidaily.com/how-to-solve-the-persistent-body-stream-problem-with-chatgpt-top-7-remedies/"><u>How to Solve the Persistent 'Body Stream' Problem with ChatGPT: Top 7 Remedies</u></a></li>
<li><a href="https://tech-haven.techidaily.com/improving-accessibility-four-steps-to-transform-the-chatgpt-plugins-platform/"><u>Improving Accessibility: Four Steps to Transform the ChatGPT Plugins Platform</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-a-comprehensive-guide-to-iphone-7-blacklist-removal-tips-and-tools-drfone-by-drfone-ios/"><u>In 2024, A Comprehensive Guide to iPhone 7 Blacklist Removal Tips and Tools | Dr.fone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-how-does-the-stardust-trade-cost-in-pokemon-go-on-tecno-spark-go-2024-drfone-by-drfone-virtual-android/"><u>In 2024, How does the stardust trade cost In pokemon go On Tecno Spark Go (2024)? | Dr.fone</u></a></li>
<li><a href="https://tech-haven.techidaily.com/introduce-a-cost-free-localized-chatbot-ai-on-pc/"><u>Introduce a Cost-Free Localized Chatbot AI on PC</u></a></li>
<li><a href="https://tech-haven.techidaily.com/mastering-the-art-of-finding-books-top-5-ai-assisted-reader-sites/"><u>Mastering the Art of Finding Books - Top 5 AI-Assisted Reader Sites</u></a></li>
<li><a href="https://tech-haven.techidaily.com/mastering-the-art-of-integrating-gpt-references-enhancing-conversations-with-personalized-ai/"><u>Mastering the Art of Integrating GPT References: Enhancing Conversations with Personalized AI</u></a></li>
<li><a href="https://tech-haven.techidaily.com/mastering-the-art-of-poetry-a-guide-on-utilizing-chatgpt/"><u>Mastering the Art of Poetry: A Guide on Utilizing ChatGPT</u></a></li>
<li><a href="https://extra-information.techidaily.com/mastering-your-screenplay-netflix-speed-controls/"><u>Mastering Your Screenplay (Netflix) - Speed Controls</u></a></li>
<li><a href="https://tech-haven.techidaily.com/microsoft-takes-over-blizzard-exploring-ai-innovation-and-linguistic-translation-in-our-latest-podcast-episode/"><u>Microsoft Takes Over Blizzard: Exploring AI Innovation and Linguistic Translation in Our Latest Podcast Episode</u></a></li>
<li><a href="https://tech-haven.techidaily.com/navigating-the-world-of-ai-conversationalists-how-does-chatgpt-plus-stack-up-against-perplex3/"><u>Navigating the World of AI Conversationalists: How Does ChatGPT Plus Stack Up Against Perplex^3?</u></a></li>
<li><a href="https://tech-haven.techidaily.com/project-gemini-explained-how-google-is-pioneering-advanced-artificial-intelligence/"><u>Project Gemini Explained: How Google Is Pioneering Advanced Artificial Intelligence</u></a></li>
<li><a href="https://tech-haven.techidaily.com/running-ai-conversations-with-chatgpt-on-windows-quick-setup-instructions/"><u>Running AI Conversations with ChatGPT on Windows – Quick Setup Instructions</u></a></li>
<li><a href="https://tech-haven.techidaily.com/seamless-conversations-with-bing-ai-setup-guide-for-android-devices/"><u>Seamless Conversations with Bing AI: Setup Guide for Android Devices</u></a></li>
<li><a href="https://tech-haven.techidaily.com/the-quora-poe-blueprint-for-ai-conversation/"><u>The Quora PoE Blueprint for AI Conversation</u></a></li>
<li><a href="https://tech-haven.techidaily.com/transform-your-ai-experience-with-9-pluses-perks/"><u>Transform Your AI Experience with 9 Pluses Perks</u></a></li>
<li><a href="https://tech-haven.techidaily.com/transforming-the-internet-the-impact-of-ai-on-future-search-engine-results/"><u>Transforming the Internet: The Impact of AI on Future Search Engine Results</u></a></li>
<li><a href="https://tech-haven.techidaily.com/troubleshooting-steps-for-chatgpts-conversation-saving-glitches/"><u>Troubleshooting Steps for ChatGPT's Conversation Saving Glitches</u></a></li>
<li><a href="https://tech-haven.techidaily.com/unveiling-nvidias-customizable-ai-service-your-guide-to-generative-tech-innovation/"><u>Unveiling NVIDIA's Customizable AI Service – Your Guide to Generative Tech Innovation</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/updated-how-to-use-ken-burns-effect-in-final-cut-pro-with-detailed-steps-for-2024/"><u>Updated How to Use Ken Burns Effect in Final Cut Pro with Detailed Steps for 2024</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/updated-supercharge-adobe-premiere-pro-the-best-free-and-paid-plugins/"><u>Updated Supercharge Adobe Premiere Pro The Best Free and Paid Plugins</u></a></li>
<li><a href="https://tech-haven.techidaily.com/voice-activated-intelligence-chatgpts-command-responsive-prowess/"><u>Voice Activated Intelligence: ChatGPT's Command-Responsive Prowess</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=1300375&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-15_%281%29.jpg" border="0"></a>
<!-- affiliate ads end -->