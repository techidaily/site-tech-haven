---
title: "Setting up Automatic Tab Closure on Safari in macOS Catalina: A Step-by-Step Guide"
date: 2024-12-22T16:00:02.460Z
updated: 2024-12-28T16:00:21.443Z
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/Wy0uYNNdMDM?si=5ir7EHlr0CkpcYOT" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### **ZDNET** Recommends

[The best Macs Apple's Mac lineup can be confusing as the company transitions from Intel processors to its own Apple Silicon processors. But we're here to help.  Read now](https://www.zdnet.com/article/best-mac/)

For the general-purpose network, I can just have MacOS accept an IP address from the DHCP server. However, for the container network, I prefer assigning a static IP address.

Is this possible?

It certainly is. With the help of MacOS Network Locations, you can assign specific configurations for specific networks (or locations) and even define a particular network you want to connect to within a location.

Let me show you how it works.

**Also:** [**How to manage SSH connections on MacOS with Termius**](https://www.zdnet.com/article/how-to-manage-ssh-connections-on-macos-with-termius/) 

## How to create different network locations in MacOS

## Requirements

The only thing you'll need is a device running an updated version of MacOS. This feature works with both wired and wireless connections.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/odDOPrPjRYY?si=7QHzdUkTPNkHJiVj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Open System Preferences

Click the Apple menu at the top right of your display and select System Preferences from the menu.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/YpnYKIrpgZQ?si=94zicAHp1CH-0oso" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Open Network

From within System Preferences, click the Network icon to open the Network section.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/BmegThMdrJE?si=rILo1FJb9DgnPljV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. Create a new network location

From the Location drop-down, select Edit Locations. In the resulting pop-up, click + (the plus sign). You will be prompted to name the location, so type a new name and hit Enter on your keyboard, and then click Done.

Creating a new Network Location in MacOS Monterey.

Image: Jack Wallen

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/zWYVKFk3yPQ?si=Yu7xsjIYgRiq8zHk" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://screen-sharing-recording.techidaily.com/new-mov-files-saving-methods-for-windows-10-users/"><u>[New] .mov Files Saving Methods for Windows 10 Users</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-master-the-art-of-canvas-with-these-top-10-secrets/"><u>[New] Master the Art of Canvas with These Top 10 Secrets</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-the-future-of-sharing-videos-will-likes-outgrow-tiktoks-reach-in-2024/"><u>[New] The Future of Sharing Videos Will Likes Outgrow TikTok's Reach, In 2024</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-eye-catching-insta-highlights-unveiling-3-secrets-for-2024/"><u>[Updated] Eye-Catching Insta Highlights Unveiling 3 Secrets for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-fifas-favorite-footage-charted-on-youtube/"><u>[Updated] FIFA's Favorite Footage Charted on YouTube</u></a></li>
<li><a href="https://fox-helps.techidaily.com/updated-in-2024-demystifying-whatsapp-audio-talks/"><u>[Updated] In 2024, Demystifying WhatsApp Audio Talks</u></a></li>
<li><a href="https://tech-haven.techidaily.com/can-you-count-on-zerogpt-unraveling-the-reliance-issues-with-five-insightful-examples/"><u>Can You Count On ZeroGPT? Unraveling the Reliance Issues with Five Insightful Examples</u></a></li>
<li><a href="https://tech-haven.techidaily.com/diverging-pathways-of-ai-assistance-understanding-siri-and-chatgpts-unique-capabilities/"><u>Diverging Pathways of AI Assistance: Understanding Siri and ChatGPT's Unique Capabilities</u></a></li>
<li><a href="https://tech-haven.techidaily.com/futurists-unite-global-leaders-on-ai-prospects/"><u>Futurists Unite: Global Leaders on AI Prospects</u></a></li>
<li><a href="https://win-forum.techidaily.com/hoogtepunten-van-het-ontsnappen-van-ondergrondsounds-uit-videos-en-audios-3-handige-tijgers/"><u>Hoogtepunten Van Het Ontsnappen Van Ondergrondsounds Uit Video's en Audios - 3 Handige Tijgers</u></a></li>
<li><a href="https://tech-haven.techidaily.com/human-resources-transformed-by-chatai/"><u>Human Resources Transformed by ChatAI</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/inside-meta-ai-unraveling-the-secrets-of-advanced-machine-learning/"><u>Inside Meta AI: Unraveling the Secrets of Advanced Machine Learning</u></a></li>
<li><a href="https://buynow-info.techidaily.com/insiders-guide-to-the-family-oriented-maisto-off-road-rc-challenge-vehicle/"><u>Insider's Guide to the Family-Oriented Maisto Off-Road RC Challenge Vehicle</u></a></li>
<li><a href="https://tech-haven.techidaily.com/maximize-your-earnings-chatbot-hustles-ultimate-pc-assembly-guidance-and-classic-portable-games/"><u>Maximize Your Earnings: Chatbot Hustles, Ultimate PC Assembly Guidance & Classic Portable Games</u></a></li>
<li><a href="https://tech-haven.techidaily.com/navigating-through-the-upsides-and-downsides-of-ai-powered-creativity-with-chatgpt/"><u>Navigating Through the Upsides and Downsides of AI-Powered Creativity with ChatGPT</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/planning-to-use-a-pokemon-go-joystick-on-nokia-g310-drfone-by-drfone-virtual-android/"><u>Planning to Use a Pokemon Go Joystick on Nokia G310? | Dr.fone</u></a></li>
<li><a href="https://tech-haven.techidaily.com/say-goodbye-to-spreadsheet-woes-enhancing-excel-skills-with-chatgpt/"><u>Say Goodbye to Spreadsheet Woes: Enhancing Excel Skills with ChatGPT</u></a></li>
<li><a href="https://tech-haven.techidaily.com/the-future-of-coding-predicting-how-artificial-intelligence-may-transform-developer-workflows/"><u>The Future of Coding: Predicting How Artificial Intelligence May Transform Developer Workflows</u></a></li>
<li><a href="https://tech-haven.techidaily.com/unlocking-chatbot-potential-setting-up-the-chatgpt-widget-for-android-users/"><u>Unlocking Chatbot Potential: Setting Up the ChatGPT Widget for Android Users</u></a></li>
</ul></div>

