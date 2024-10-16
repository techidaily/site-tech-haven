---
title: "Setting up Automatic Tab Closure on Safari in macOS Catalina: A Step-by-Step Guide"
date: 2024-10-10T03:02:57.565Z
updated: 2024-10-15T19:24:52.144Z
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

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134492/18498" target="_top" id="2134492">
  <img src="//a.impactradius-go.com/display-ad/18498-2134492" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134492/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to create different network locations in MacOS

## Requirements

The only thing you'll need is a device running an updated version of MacOS. This feature works with both wired and wireless connections.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134489/18498" target="_top" id="2134489">
  <img src="//a.impactradius-go.com/display-ad/18498-2134489" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134489/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 1\. Open System Preferences

Click the Apple menu at the top right of your display and select System Preferences from the menu.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1925489/19272" target="_top" id="1925489">
  <img src="//a.impactradius-go.com/display-ad/19272-1925489" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1925489/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. Open Network

From within System Preferences, click the Network icon to open the Network section.

<!-- affiliate ads begin -->
<span id="1495277">
					<video width="1536" height="864" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1495277.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/17189-1495277">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1495277.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:960px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Ffunwhole.sjv.io%2Fc%2F5597632%2F1495277%2F17189'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1495277/17189" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 3\. Create a new network location

From the Location drop-down, select Edit Locations. In the resulting pop-up, click + (the plus sign). You will be prompted to name the location, so type a new name and hit Enter on your keyboard, and then click Done.

Creating a new Network Location in MacOS Monterey.

Image: Jack Wallen

## 4\. Configure the new location

Make sure to select the new location you created from the Location drop-down. Click Advanced to open the location configuration window, where you can configure the location to meet your specific needs. For example, you can select the network to be used and then configure that network for a static IP address using the Cloudflare DNS servers.

Configuring a network for the new location in MacOS.

Image: Jack Wallen

Once you've configured the location exactly how you need it, click Apply to save everything.

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
<li><a href="https://extra-lessons.techidaily.com/new-crafting-powerful-narratives-with-these-30-video-plans/"><u>[New] Crafting Powerful Narratives with These 30 Video Plans</u></a></li>
<li><a href="https://fox-direct.techidaily.com/updated-2024-approved-cost-breakdown-for-youtube-ads/"><u>[Updated] 2024 Approved Cost Breakdown for YouTube Ads</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/updated-in-2024-mastering-viewing-on-facebook-live/"><u>[Updated] In 2024, Mastering Viewing on Facebook Live</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-sound-sculpting-on-android-the-7-ultimate-audio-editing-apps-for-2024/"><u>[Updated] Sound Sculpting on Android The 7 Ultimate Audio Editing Apps for 2024</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/approved-captivate-audiences-with-perfectly-tailored-youtube-descriptions/"><u>2024 Approved Captivate Audiences with Perfectly Tailored Youtube Descriptions</u></a></li>
<li><a href="https://tech-haven.techidaily.com/best-in-class-bots-chatgpt-or-gemini-for-top-notch-programming-assistance/"><u>Best in Class Bots: ChatGPT or Gemini for Top-Notch Programming Assistance</u></a></li>
<li><a href="https://tech-haven.techidaily.com/elevate-your-writing-game-go-paperless-with-hix-and-gpt-narratives/"><u>Elevate Your Writing Game - Go Paperless with HIX and GPT-Narratives</u></a></li>
<li><a href="https://tech-haven.techidaily.com/exploiting-chatgpts-link-to-wolframalpha-in-3-ways/"><u>Exploiting ChatGPT's Link to WolframAlpha in 3 Ways</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-different-methods-to-unlock-your-apple-iphone-13-pro-max-by-drfone-ios/"><u>In 2024, Different Methods To Unlock Your Apple iPhone 13 Pro Max</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-how-to-fake-gps-on-android-without-mock-location-for-your-tecno-spark-20c-drfone-by-drfone-virtual/"><u>In 2024, How to Fake GPS on Android without Mock Location For your Tecno Spark 20C | Dr.fone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/ipogo-will-be-the-new-ispoofer-on-nokia-c02-drfone-by-drfone-virtual-android/"><u>iPogo will be the new iSpoofer On Nokia C02? | Dr.fone</u></a></li>
<li><a href="https://tech-haven.techidaily.com/mastering-3d-print-designs-a-step-by-step-guide-using-chatgpt/"><u>Mastering 3D Print Designs: A Step-by-Step Guide Using ChatGPT</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/ring-cost-effective-visual-integration-in-writing/"><u>Mastering Cost-Effective Visual Integration in Writing</u></a></li>
<li><a href="https://tech-haven.techidaily.com/quick-tutorial-guide-download-and-install-llama-2-locally/"><u>Quick Tutorial Guide: Download & Install Llama 2 Locally</u></a></li>
<li><a href="https://tech-haven.techidaily.com/tired-of-awaiting-chatgpt-desktop-embrace-this-robust-open-source-substitute-now/"><u>Tired of Awaiting ChatGPT Desktop? Embrace This Robust Open-Source Substitute Now!</u></a></li>
<li><a href="https://tech-haven.techidaily.com/visual-visionaries-top-30-conceptual-spark-plugs-from-ai-art/"><u>Visual Visionaries: Top 30 Conceptual Spark Plugs From AI Art</u></a></li>
<li><a href="https://tech-haven.techidaily.com/who-reigns-supreme-googles-bard-or-microsofts-bing-chat/"><u>Who Reigns Supreme? Google’s Bard or Microsoft’s Bing Chat</u></a></li>
</ul></div>

