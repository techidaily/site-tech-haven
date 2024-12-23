---
title: "Setting up Automatic Tab Closure on Safari in macOS Catalina: A Step-by-Step Guide"
date: 2024-12-15T21:31:19.300Z
updated: 2024-12-22T23:24:02.036Z
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/LaGNHfAT92w?si=bvHo1iYK2JBIPtRo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### **ZDNET** Recommends

[The best Macs Apple's Mac lineup can be confusing as the company transitions from Intel processors to its own Apple Silicon processors. But we're here to help.  Read now](https://www.zdnet.com/article/best-mac/)

For the general-purpose network, I can just have MacOS accept an IP address from the DHCP server. However, for the container network, I prefer assigning a static IP address.

Is this possible?

It certainly is. With the help of MacOS Network Locations, you can assign specific configurations for specific networks (or locations) and even define a particular network you want to connect to within a location.

Let me show you how it works.

**Also:** [**How to manage SSH connections on MacOS with Termius**](https://www.zdnet.com/article/how-to-manage-ssh-connections-on-macos-with-termius/) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/oB9V7rZzotw?si=d4xrCbq1jKHXGAWN" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to create different network locations in MacOS

## Requirements

The only thing you'll need is a device running an updated version of MacOS. This feature works with both wired and wireless connections.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/_1g4U13PBk0?si=xJLJtlc4hKBTBH8M" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Open System Preferences

Click the Apple menu at the top right of your display and select System Preferences from the menu.

## 2\. Open Network

From within System Preferences, click the Network icon to open the Network section.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/epKTCSREjhI?si=Ez_hObK1FZrmEE7f" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. Create a new network location

From the Location drop-down, select Edit Locations. In the resulting pop-up, click + (the plus sign). You will be prompted to name the location, so type a new name and hit Enter on your keyboard, and then click Done.

Creating a new Network Location in MacOS Monterey.

Image: Jack Wallen

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/U_aNKnMTPjo?si=Og_mEt7NP3Fbsg2n" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://fox-friendly.techidaily.com/new-cutting-edge-easy-to-use-mastering-magix-vpxs-capabilities/"><u>[New] Cutting Edge, Easy to Use Mastering Magix VPX's Capabilities</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/updated-2024-approved-unveiling-modernity-discover-these-top-10-digital-realms-for-artistic-font-styles/"><u>[Updated] 2024 Approved Unveiling Modernity Discover These Top 10 Digital Realms for Artistic Font Styles</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-strategies-to-alleviate-vr-motion-woes/"><u>[Updated] Strategies to Alleviate VR Motion Woes</u></a></li>
<li><a href="https://tech-haven.techidaily.com/four-instances-proving-the-untrustworthiness-of-zerogpt-and-other-artificeial-intelligence-detectors/"><u>Four Instances Proving the Untrustworthiness of ZeroGPT and Other Artificeial Intelligence Detectors</u></a></li>
<li><a href="https://tech-haven.techidaily.com/gpt-4-is-now-free-for-everyone-but-there-are-still-6-reasons-to-keep-using-chatgpt-plus/"><u>GPT-4 Is Now Free for Everyone, but There Are Still 6 Reasons to Keep Using ChatGPT Plus</u></a></li>
<li><a href="https://tech-haven.techidaily.com/gpt-powered-text-interaction-for-paper-files/"><u>GPT-Powered Text Interaction for Paper Files</u></a></li>
<li><a href="https://tech-haven.techidaily.com/how-chatgpt-pales-when-it-comes-to-nuanced-writing-tasks/"><u>How ChatGPT Pales When It Comes to Nuanced Writing Tasks</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/in-2024-igniting-passion-creating-a-trending-solo-podcast/"><u>In 2024, Igniting Passion Creating a Trending Solo Podcast</u></a></li>
<li><a href="https://tech-haven.techidaily.com/join-openais-quest-track-and-report-software-glitches/"><u>Join OpenAI's Quest: Track and Report Software Glitches!</u></a></li>
<li><a href="https://tech-haven.techidaily.com/mapping-ais-emergence-in-modern-times/"><u>Mapping AI's Emergence in Modern Times</u></a></li>
<li><a href="https://tech-haven.techidaily.com/master-the-marketplace-10-ways-chatgpt-enhances-your-linkedin-job-search-strategy/"><u>Master the Marketplace: 10 Ways ChatGPT Enhances Your LinkedIn Job Search Strategy</u></a></li>
<li><a href="https://fox-zaraz.techidaily.com/mastering-flippdf-a-complete-tutorial-for-dynamic-digital-books-on-flipbuildercom/"><u>Mastering FlipPDF: A Complete Tutorial for Dynamic Digital Books on FlipBuilder.com</u></a></li>
<li><a href="https://tech-haven.techidaily.com/mastering-image-generation-using-chatgpt-step-by-step-tips-and-tricks/"><u>Mastering Image Generation Using ChatGPT: Step-by-Step Tips and Tricks</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/optimizing-youtube-performance-crafting-perfect-titles-and-tags/"><u>Optimizing YouTube Performance Crafting Perfect Titles and Tags</u></a></li>
<li><a href="https://win11.techidaily.com/proven-strategy-batch-convert-heic-to-jpeg-in-windows-11/"><u>Proven Strategy: Batch Convert HEIC to JPEG in Windows 11</u></a></li>
<li><a href="https://driver-download.techidaily.com/step-by-step-tutorial-on-getting-the-latest-epson-et-3760-printer-software-for-windows-computers/"><u>Step-by-Step Tutorial on Getting the Latest Epson ET-3760 Printer Software for Windows Computers</u></a></li>
<li><a href="https://win11.techidaily.com/zero-entry-workstation-access-the-hidden-side-of-rdp-in-win-11/"><u>Zero-Entry Workstation Access: The Hidden Side of RDP in Win 11</u></a></li>
</ul></div>

