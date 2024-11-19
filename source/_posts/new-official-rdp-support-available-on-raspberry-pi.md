---
title: New Official RDP Support Available on Raspberry Pi
date: 2024-11-13T20:44:31.493Z
updated: 2024-11-18T21:17:25.907Z
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
<li><a href="https://screen-recording.techidaily.com/new-efficient-screen-capture-devices-for-education-for-2024/"><u>[New] Efficient Screen Capture Devices for Education for 2024</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-from-zero-to-zoom-expert-launching-successful-webinars-for-2024/"><u>[New] From Zero to Zoom Expert Launching Successful Webinars for 2024</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-in-2024-all-you-need-to-know-about-bandicam-updated/"><u>[New] In 2024, All You Need to Know About Bandicam (Updated )</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/updated-transcendence-in-music-mixing-crossfade-unveiled/"><u>[Updated] Transcendence in Music Mixing Crossfade Unveiled</u></a></li>
<li><a href="https://technical-tips.techidaily.com/building-your-dream-gaming-pc-an-rtx-4070-rig-complete-with-a-2tb-ssd-under-budget-at-just-1000-exclusive-prime-day-guide/"><u>Building Your Dream Gaming PC: An RTX 4070 Rig Complete with a 2TB SSD Under Budget at Just $1,000 - Exclusive Prime Day Guide</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-sharefake-gps-on-uber-for-oppo-reno-10-5g-drfone-by-drfone-virtual-android/"><u>How to share/fake gps on Uber for Oppo Reno 10 5G | Dr.fone</u></a></li>
<li><a href="https://tech-haven.techidaily.com/inside-our-mistral-ai-and-chatgpt-showdown-which-one-wins-as-the-best-ai-chatbot/"><u>Inside Our Mistral AI and ChatGPT Showdown: Which One Wins as the Best AI Chatbot?</u></a></li>
<li><a href="https://tech-haven.techidaily.com/is-the-google-bard-app-safe-exposing-potential-malware-risks-to-users/"><u>Is the Google Bard App Safe? Exposing Potential Malware Risks to Users</u></a></li>
<li><a href="https://tech-haven.techidaily.com/navigating-artificial-intelligence-rules-identifying-authorities-in-tech-regulation/"><u>Navigating Artificial Intelligence Rules: Identifying Authorities in Tech Regulation</u></a></li>
<li><a href="https://driver-install.techidaily.com/secure-logitech-webcam-updater-for-windows-10/"><u>Secure Logitech Webcam Updater for Windows 10</u></a></li>
<li><a href="https://article-posts.techidaily.com/the-12th-circle-of-conversation-personalizing-whatsapp-bios-by-signs/"><u>The 12Th Circle of Conversation - Personalizing WhatsApp Bios by Signs</u></a></li>
<li><a href="https://tech-haven.techidaily.com/the-hidden-pitfalls-of-ai-6-essential-factors-demanding-your-attention/"><u>The Hidden Pitfalls of AI: 6 Essential Factors Demanding Your Attention</u></a></li>
<li><a href="https://tech-haven.techidaily.com/unlocking-the-mystery-behind-chatgpts-new-sign-up-hiatus-when-will-it-reopen/"><u>Unlocking the Mystery Behind ChatGPT's New Sign-Up Hiatus - When Will It Reopen?</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2087262/19272" target="_top" id="2087262">
  <img src="//a.impactradius-go.com/display-ad/19272-2087262" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2087262/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

