---
title: "Setting up Automatic Tab Closure on Safari in macOS Catalina: A Step-by-Step Guide"
date: 2024-12-02T17:23:10.928Z
updated: 2024-12-07T21:19:43.947Z
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/zWYVKFk3yPQ?si=Yu7xsjIYgRiq8zHk" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### **ZDNET** Recommends

[The best Macs Apple's Mac lineup can be confusing as the company transitions from Intel processors to its own Apple Silicon processors. But we're here to help.  Read now](https://www.zdnet.com/article/best-mac/)

For the general-purpose network, I can just have MacOS accept an IP address from the DHCP server. However, for the container network, I prefer assigning a static IP address.

Is this possible?

It certainly is. With the help of MacOS Network Locations, you can assign specific configurations for specific networks (or locations) and even define a particular network you want to connect to within a location.

Let me show you how it works.

**Also:** [**How to manage SSH connections on MacOS with Termius**](https://www.zdnet.com/article/how-to-manage-ssh-connections-on-macos-with-termius/) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/oySc0DiqmKc?si=8pynRzuhlq2RUPZ6" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to create different network locations in MacOS

## Requirements

The only thing you'll need is a device running an updated version of MacOS. This feature works with both wired and wireless connections.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/K7fATC_lI7o?si=UFotPJqflDRZr-mv" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Open System Preferences

Click the Apple menu at the top right of your display and select System Preferences from the menu.

## 2\. Open Network

From within System Preferences, click the Network icon to open the Network section.

## 3\. Create a new network location

From the Location drop-down, select Edit Locations. In the resulting pop-up, click + (the plus sign). You will be prompted to name the location, so type a new name and hit Enter on your keyboard, and then click Done.

Creating a new Network Location in MacOS Monterey.

Image: Jack Wallen

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/zAzTErKy6h8?si=vi5z3M9_7fW6qiAJ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 4\. Configure the new location

Make sure to select the new location you created from the Location drop-down. Click Advanced to open the location configuration window, where you can configure the location to meet your specific needs. For example, you can select the network to be used and then configure that network for a static IP address using the Cloudflare DNS servers.

Configuring a network for the new location in MacOS.

Image: Jack Wallen

Once you've configured the location exactly how you need it, click Apply to save everything.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/9Sj2QNA-JXI?si=V-_h73iE3VlE214k" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://fox-hovers.techidaily.com/updated-leading-drones-for-superior-gopro-camera-integration/"><u>[Updated] Leading Drones for Superior GoPro Camera Integration</u></a></li>
<li><a href="https://win-guides.techidaily.com/comment-restaurer-vos-signets-precieux-dans-google-chrome-5-methodes-simples/"><u>Comment Restaurer Vos Signets Précieux Dans Google Chrome - [5 Méthodes Simples]</u></a></li>
<li><a href="https://buynow-info.techidaily.com/exploring-torment-tides-of-numenera-in-depth-game-review-and-insights-into-its-unique-sci-fi-setting/"><u>Exploring 'Torment: Tides of Numenera' - In-Depth Game Review & Insights Into Its Unique Sci-Fi Setting</u></a></li>
<li><a href="https://extra-resources.techidaily.com/how-picshot-simplifies-photo-collage-creation/"><u>How Picshot Simplifies Photo Collage Creation</u></a></li>
<li><a href="https://ios-location-track.techidaily.com/in-2024-how-to-track-whatsapp-messages-on-apple-iphone-6-plus-without-them-knowing-drfone-by-drfone-virtual-ios/"><u>In 2024, How to Track WhatsApp Messages on Apple iPhone 6 Plus Without Them Knowing? | Dr.fone</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-spoofing-life360-how-to-do-it-on-apple-iphone-13-drfone-by-drfone-virtual-ios/"><u>In 2024, Spoofing Life360 How to Do it on Apple iPhone 13? | Dr.fone</u></a></li>
<li><a href="https://tech-haven.techidaily.com/innovative-non-chatgpt-options-for-coding-autonomy/"><u>Innovative Non-ChatGPT Options for Coding Autonomy</u></a></li>
<li><a href="https://tech-haven.techidaily.com/insights-into-artificial-intelligence-mastering-transfer-learning/"><u>Insights Into Artificial Intelligence: Mastering Transfer Learning</u></a></li>
<li><a href="https://tech-haven.techidaily.com/maximizing-efficiency-how-chatgpt-can-transform-your-schedule/"><u>Maximizing Efficiency: How ChatGPT Can Transform Your Schedule</u></a></li>
<li><a href="https://review-topics.techidaily.com/remove-frp-lock-on-a60s-by-drfone-android-unlock-remove-google-frp/"><u>Remove FRP Lock on A60s</u></a></li>
<li><a href="https://tech-haven.techidaily.com/strategies-to-unblock-full-capacity-windows/"><u>Strategies to Unblock Full Capacity (Windows)</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/synthetic-symmetry-crafting-ai-art-with-gpt-assistance/"><u>Synthetic Symmetry: Crafting AI Art with GPT Assistance</u></a></li>
<li><a href="https://tech-haven.techidaily.com/the-ultimate-guide-to-top-rated-free-pc-gaming-experiences-and-insights-into-mechanical-keyboard-tech/"><u>The Ultimate Guide to Top-Rated Free PC Gaming Experiences & Insights Into Mechanical Keyboard Tech</u></a></li>
<li><a href="https://tech-haven.techidaily.com/the-urgent-need-for-more-regulation-in-ai-understanding-openais-ceo-perspective/"><u>The Urgent Need for More Regulation in AI: Understanding OpenAI’s CEO Perspective</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/top-15-apps-to-hack-wifi-password-on-poco-c65-by-drfone-android/"><u>Top 15 Apps To Hack WiFi Password On Poco C65</u></a></li>
<li><a href="https://solve-howtos.techidaily.com/top-20-gratis-inspirationstools-for-video-arkitektur-2024-komplett-utbud/"><u>Top 20 Gratis Inspirationstools För Video Arkitektur 2024 - Komplett Utbud</u></a></li>
<li><a href="https://tech-haven.techidaily.com/transforming-your-polyglot-dreams-into-reality-with-chatgpt-plus/"><u>Transforming Your Polyglot Dreams Into Reality with ChatGPT Plus</u></a></li>
<li><a href="https://tech-haven.techidaily.com/utilizing-chatgpt-a-data-analysts-guide-to-6-innovative-approaches/"><u>Utilizing ChatGPT: A Data Analyst's Guide to 6 Innovative Approaches</u></a></li>
<li><a href="https://tech-haven.techidaily.com/why-choosing-chatgpt-could-be-a-smart-move-for-your-wellbeeing-a-seven-point-overview/"><u>Why Choosing ChatGPT Could Be a Smart Move for Your Wellbeeing: A Seven-Point Overview</u></a></li>
</ul></div>

