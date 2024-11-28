---
title: "Setting up Automatic Tab Closure on Safari in macOS Catalina: A Step-by-Step Guide"
date: 2024-11-21T16:01:47.262Z
updated: 2024-11-28T16:03:52.409Z
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/QPAKth3O_5c?si=3YDfzJAZMDp1gFRz&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### **ZDNET** Recommends

[The best Macs Apple's Mac lineup can be confusing as the company transitions from Intel processors to its own Apple Silicon processors. But we're here to help.  Read now](https://www.zdnet.com/article/best-mac/)

For the general-purpose network, I can just have MacOS accept an IP address from the DHCP server. However, for the container network, I prefer assigning a static IP address.

Is this possible?

It certainly is. With the help of MacOS Network Locations, you can assign specific configurations for specific networks (or locations) and even define a particular network you want to connect to within a location.

Let me show you how it works.

**Also:** [**How to manage SSH connections on MacOS with Termius**](https://www.zdnet.com/article/how-to-manage-ssh-connections-on-macos-with-termius/) 

## How to create different network locations in MacOS

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/jvwX82j3ci0?si=gAWoovjXgs3m1d7S&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Requirements

The only thing you'll need is a device running an updated version of MacOS. This feature works with both wired and wireless connections.

## 1\. Open System Preferences

Click the Apple menu at the top right of your display and select System Preferences from the menu.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/_O8m9KphYzs?si=jITthzeyX_Kmt9X2&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Open Network

From within System Preferences, click the Network icon to open the Network section.

## 3\. Create a new network location

From the Location drop-down, select Edit Locations. In the resulting pop-up, click + (the plus sign). You will be prompted to name the location, so type a new name and hit Enter on your keyboard, and then click Done.

Creating a new Network Location in MacOS Monterey.

Image: Jack Wallen

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/uSfA74aeYeA?si=HdJSMdeS7HVtS6-j&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 4\. Configure the new location

Make sure to select the new location you created from the Location drop-down. Click Advanced to open the location configuration window, where you can configure the location to meet your specific needs. For example, you can select the network to be used and then configure that network for a static IP address using the Cloudflare DNS servers.

Configuring a network for the new location in MacOS.

Image: Jack Wallen

Once you've configured the location exactly how you need it, click Apply to save everything.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/KKFdFHaVIJg?si=x2vLw7ty3FtHX-9T&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://instagram-video-recordings.techidaily.com/2024-approved-essential-aspects-ignored-by-instagram-story-observers/"><u>2024 Approved Essential Aspects Ignored by Instagram Story Observers</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/boost-your-iphone-efficiency-with-top-secret-voice-triggers-revealed-by-zdnet/"><u>Boost Your iPhone Efficiency with Top-Secret Voice Triggers Revealed by ZDNet</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-remove-forgotten-pin-of-your-samsung-galaxy-a34-5g-by-drfone-android/"><u>How to Remove Forgotten PIN Of Your Samsung Galaxy A34 5G</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/repairing-a-broken-wi-fi-link-with-your-surface-pro-a-comprehve-guide/"><u>Repairing a Broken Wi-Fi Link with Your Surface Pro - A Comprehve Guide</u></a></li>
<li><a href="https://novels-ebooks.techidaily.com/211252805-9782898640209-the-13-keys-to-happiness/"><u>The 13 Keys to Happiness | Free Book</u></a></li>
<li><a href="https://extra-information.techidaily.com/tune-up-the-mundane-how-to-add-custom-ringtones-and-sounds-for-a-unique-auditory-experience-on-android/"><u>Tune Up the Mundane How to Add Custom Ringtones & Sounds for a Unique Auditory Experience on Android</u></a></li>
<li><a href="https://tech-haven.techidaily.com/1721955708309-turn-by-turn-navigation/"><u>Turn-by-Turn Navigation</u></a></li>
<li><a href="https://driver-error.techidaily.com/understanding-the-legacy-how-usb-composite-devices-shaped-modern-connectivity/"><u>Understanding the Legacy: How USB Composite Devices Shaped Modern Connectivity</u></a></li>
<li><a href="https://tech-haven.techidaily.com/unveiling-impostor-gpt-through-mention-driven-inspection/"><u>Unveiling Impostor GPT Through Mention-Driven Inspection</u></a></li>
<li><a href="https://tech-haven.techidaily.com/unveiling-the-practical-use-cases-for-chatgpt-a-look-at-seven-key-areas/"><u>Unveiling the Practical Use Cases for ChatGPT: A Look at Seven Key Areas</u></a></li>
<li><a href="https://tech-haven.techidaily.com/unveiling-the-truth-the-top-7-reasons-why-chatgpt-jailbreak-attempts-fail/"><u>Unveiling the Truth: The Top 7 Reasons Why ChatGPT Jailbreak Attempts Fail</u></a></li>
<li><a href="https://tech-haven.techidaily.com/vacation-internet-tips-maximize-your-experience/"><u>Vacation Internet Tips: Maximize Your Experience</u></a></li>
<li><a href="https://tech-haven.techidaily.com/voice-enabled-chatgpt-on-your-android-device-the-ultimate-how-to/"><u>Voice-Enabled ChatGPT on Your Android Device - The Ultimate How-To</u></a></li>
<li><a href="https://tech-haven.techidaily.com/why-artificial-intelligence-isnt-a-one-size-fits-all-solution-for-content-creators/"><u>Why Artificial Intelligence Isn't a One-Size-Fits-All Solution for Content Creators</u></a></li>
<li><a href="https://win-answers.techidaily.com/why-your-pcs-frame-rate-drops-by-two-fps-explained/"><u>Why Your PC's Frame Rate Drops by Two FPS - Explained</u></a></li>
</ul></div>

