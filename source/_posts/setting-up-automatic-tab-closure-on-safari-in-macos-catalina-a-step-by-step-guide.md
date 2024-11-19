---
title: "Setting up Automatic Tab Closure on Safari in macOS Catalina: A Step-by-Step Guide"
date: 2024-11-17T01:37:33.457Z
updated: 2024-11-18T20:32:19.791Z
tags:
  - apple
categories:
  - tech
thumbnail: https://thmb.techidaily.com/3ca289f4707af5e0ebcc0fe8b2f301906af8c014f3bb06033bb1a4fefba543ee.jpg
---

## Managing Diverse Networking Scenarios in macOS: A Step-by-Step Guide | Expert Advice

![MacOS Ventura](https://www.zdnet.com/a/img/resize/f9b803b11abf24ef89a80e3eab2b456c1d35293a/2022/07/11/47775a46-83d9-4a0e-a1e0-bac36bb3c798/macos-ventura-apple-hero.jpg?auto=webp&width=1280)

Apple

I connect to a lot of different networks. At home, I have three different LANs to choose from, which I use depending on my needs. For example, I have a general-purpose network and one that I use for the deployment of containers and the like. 

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

### **ZDNET** Recommends

[The best Macs Apple's Mac lineup can be confusing as the company transitions from Intel processors to its own Apple Silicon processors. But we're here to help.  Read now](https://www.zdnet.com/article/best-mac/)

For the general-purpose network, I can just have MacOS accept an IP address from the DHCP server. However, for the container network, I prefer assigning a static IP address.

Is this possible?

It certainly is. With the help of MacOS Network Locations, you can assign specific configurations for specific networks (or locations) and even define a particular network you want to connect to within a location.

Let me show you how it works.

**Also:** [**How to manage SSH connections on MacOS with Termius**](https://www.zdnet.com/article/how-to-manage-ssh-connections-on-macos-with-termius/) 

## How to create different network locations in MacOS

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118305/7443" target="_top" id="2118305">
  <img src="//a.impactradius-go.com/display-ad/7443-2118305" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118305/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Requirements

The only thing you'll need is a device running an updated version of MacOS. This feature works with both wired and wireless connections.

## 1\. Open System Preferences

Click the Apple menu at the top right of your display and select System Preferences from the menu.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2016170/19272" target="_top" id="2016170">
  <img src="//a.impactradius-go.com/display-ad/19272-2016170" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2016170/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. Open Network

From within System Preferences, click the Network icon to open the Network section.

## 3\. Create a new network location

From the Location drop-down, select Edit Locations. In the resulting pop-up, click + (the plus sign). You will be prompted to name the location, so type a new name and hit Enter on your keyboard, and then click Done.

Creating a new Network Location in MacOS Monterey.

Image: Jack Wallen

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137223/26400" target="_top" id="2137223">
  <img src="//a.impactradius-go.com/display-ad/26400-2137223" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137223/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 4\. Configure the new location

Make sure to select the new location you created from the Location drop-down. Click Advanced to open the location configuration window, where you can configure the location to meet your specific needs. For example, you can select the network to be used and then configure that network for a static IP address using the Cloudflare DNS servers.

Configuring a network for the new location in MacOS.

Image: Jack Wallen

Once you've configured the location exactly how you need it, click Apply to save everything.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1896532/19272" target="_top" id="1896532">
  <img src="//a.impactradius-go.com/display-ad/19272-1896532" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1896532/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Switching to a different Network Location

After you've created all of the network locations you need, MacOS makes it very easy to switch between them. All you have to do is click the Apple menu > Location > \[Location name\] (select the name of the location you want to use).

Switching between network locations is a few mouse clicks away.

Image: Jack Wallen

And that's all there is to creating and using network locations in MacOS. If you need to get specific with how your MacOS device interacts with a network, this is a great way to go. Just remember, however, if you move from the current location, you'll want to select another. For example, if you have [one location for home and one for work](https://www.zdnet.com/article/hybrid-workers-dont-want-to-return-to-the-office-but-soon-they-might-have-to/), your machine might have trouble connecting to that work LAN with the home settings.

  
Fortunately, you are now empowered to more easily make that switch.

#### Jack Wallen: Here's how to...

[How to get true window snapping in MacOS](https://www.zdnet.com/article/how-to-get-true-window-snapping-in-macos/ "How to get true window snapping in MacOS")

[The AGM 5 Pro might be the loudest Android phone ever](https://www.zdnet.com/article/the-agm-5-pro-might-be-the-loudest-android-phone-ever/ "The AGM 5 Pro might be the loudest Android phone ever")

[Nitrux 2.4 Linux distro shows promise](https://www.zdnet.com/article/nitrux-2-4-linux-distribution-shows-promise-but-seems-rough-around-the-edges/ "Nitrux 2.4 Linux distro shows promise")

[Tired of being tracked online? DuckDuckGo's Email Protection can help](https://www.zdnet.com/article/tired-of-being-tracked-online-duckduckgos-email-protection-can-help/ "Tired of being tracked online? DuckDuckGo's Email Protection can help")

* [How to get true window snapping in MacOS](https://www.zdnet.com/article/how-to-get-true-window-snapping-in-macos/ "How to get true window snapping in MacOS")
* [The AGM 5 Pro might be the loudest Android phone ever](https://www.zdnet.com/article/the-agm-5-pro-might-be-the-loudest-android-phone-ever/ "The AGM 5 Pro might be the loudest Android phone ever")
* [Nitrux 2.4 Linux distro shows promise](https://www.zdnet.com/article/nitrux-2-4-linux-distribution-shows-promise-but-seems-rough-around-the-edges/ "Nitrux 2.4 Linux distro shows promise")
* [Tired of being tracked online? DuckDuckGo's Email Protection can help](https://www.zdnet.com/article/tired-of-being-tracked-online-duckduckgos-email-protection-can-help/ "Tired of being tracked online? DuckDuckGo's Email Protection can help")

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
<li><a href="https://screen-mirroring-recording.techidaily.com/new-getting-the-most-out-of-google-meet-for-free/"><u>[New] Getting the Most Out of Google Meet (For Free)</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-lightning-windows-image-inspector/"><u>[New] Lightning Windows Image Inspector</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-2024-approved-crafting-countdowns-the-essentials-for-obs-users/"><u>[Updated] 2024 Approved Crafting Countdowns The Essentials for OBS Users</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/about-tecno-pop-8-frp-bypass-by-drfone-android/"><u>About Tecno Pop 8 FRP Bypass</u></a></li>
<li><a href="https://extra-resources.techidaily.com/beginners-vectors-guide-types-and-applications-demystified-for-2024/"><u>Beginner's Vectors Guide Types & Applications Demystified for 2024</u></a></li>
<li><a href="https://tech-haven.techidaily.com/exploring-potential-security-risks-in-using-chatgpt-services/"><u>Exploring Potential Security Risks in Using ChatGPT Services</u></a></li>
<li><a href="https://tech-haven.techidaily.com/getting-started-with-chatgpt-on-smartphones-tips-for-android-and-ios/"><u>Getting Started with ChatGPT on Smartphones: Tips for Android and iOS</u></a></li>
<li><a href="https://tech-haven.techidaily.com/harnessing-chatgpt-for-detailed-poetry-books-crafting/"><u>Harnessing ChatGPT for Detailed Poetry Books Crafting</u></a></li>
<li><a href="https://tech-haven.techidaily.com/improving-chatgpt-dialogues-a-guide-to-7-effective-techniques/"><u>Improving ChatGPT Dialogues: A Guide to 7 Effective Techniques</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-change-honor-play-8t-lock-screen-clock-in-seconds-by-drfone-android/"><u>In 2024, How To Change Honor Play 8T Lock Screen Clock in Seconds</u></a></li>
<li><a href="https://tech-haven.techidaily.com/innovate-with-ai-navigating-the-features-and-capabilities-of-the-openai-platform/"><u>Innovate with AI: Navigating the Features and Capabilities of the OpenAI Platform</u></a></li>
<li><a href="https://tech-haven.techidaily.com/is-user-interaction-crucial-to-advancing-chatgpts-capabilities/"><u>Is User Interaction Crucial to Advancing ChatGPT's Capabilities?</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-get-rid-of-tiktok-watermarks-the-best-online-removal-methods-for-2024/"><u>New Get Rid of TikTok Watermarks The Best Online Removal Methods for 2024</u></a></li>
<li><a href="https://program-issues.techidaily.com/resolving-the-issue-free-from-the-fog-unsticking-sea-of-thieves-load-screen-woes/"><u>Resolving the Issue: Free From the Fog - Unsticking 'Sea of Thieves' Load Screen Woes</u></a></li>
<li><a href="https://blog-min.techidaily.com/top-free-and-premium-substitutes-for-adobe-software/"><u>Top Free and Premium Substitutes for Adobe Software</u></a></li>
</ul></div>

