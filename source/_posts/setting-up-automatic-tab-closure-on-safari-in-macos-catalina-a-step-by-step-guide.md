---
title: "Setting up Automatic Tab Closure on Safari in macOS Catalina: A Step-by-Step Guide"
date: 2025-02-09T20:36:17.728Z
updated: 2025-02-16T16:59:57.161Z
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/ZLb1ViO4WR8?si=g_aiHGNCd7eAvmDM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### **ZDNET** Recommends

[The best Macs Apple's Mac lineup can be confusing as the company transitions from Intel processors to its own Apple Silicon processors. But we're here to help.  Read now](https://www.zdnet.com/article/best-mac/)

For the general-purpose network, I can just have MacOS accept an IP address from the DHCP server. However, for the container network, I prefer assigning a static IP address.

Is this possible?

It certainly is. With the help of MacOS Network Locations, you can assign specific configurations for specific networks (or locations) and even define a particular network you want to connect to within a location.

Let me show you how it works.

**Also:** [**How to manage SSH connections on MacOS with Termius**](https://www.zdnet.com/article/how-to-manage-ssh-connections-on-macos-with-termius/) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/PD0vq5qAYkw?si=5H3KWtCfUOYg1Nlv" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to create different network locations in MacOS

## Requirements

The only thing you'll need is a device running an updated version of MacOS. This feature works with both wired and wireless connections.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/MmTJlcwgyrQ?si=x3hba82M0tT57fj7" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/umvX4ZdWbxk?si=tPXL0-Kzf9SQaY8z" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 4\. Configure the new location

Make sure to select the new location you created from the Location drop-down. Click Advanced to open the location configuration window, where you can configure the location to meet your specific needs. For example, you can select the network to be used and then configure that network for a static IP address using the Cloudflare DNS servers.

Configuring a network for the new location in MacOS.

Image: Jack Wallen

Once you've configured the location exactly how you need it, click Apply to save everything.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/nmj7aVvEeAs?si=OcR7USXKGyLcn09q" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://fox-friendly.techidaily.com/new-in-2024-boxed-insights-unpacking-effective-strategy/"><u>[New] In 2024, Boxed Insights Unpacking Effective Strategy</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/new-lol-factory-robotic-deadwalkers-for-2024/"><u>[New] LOL Factory Robotic Deadwalkers for 2024</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-transform-your-videos-with-the-right-dimension-proportions/"><u>[New] Transform Your Videos with the Right Dimension Proportions</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-2024-approved-pc-sound-logging-simplified-install-x-recorder-app/"><u>[Updated] 2024 Approved Pc Sound Logging Simplified - Install X-Recorder App</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/updated-seamless-video-conferencing-with-zoom-and-gmail/"><u>[Updated] Seamless Video Conferencing with Zoom & Gmail</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-innovative-interaction-integrating-watch-with-macos/"><u>2024 Approved Innovative Interaction Integrating Watch with MacOS</u></a></li>
<li><a href="https://tech-haven.techidaily.com/24-next-gen-pos-applications-beyond-openais-innovations/"><u>24 Next-Gen POS Applications Beyond OpenAI's Innovations</u></a></li>
<li><a href="https://tech-haven.techidaily.com/5-key-techniques-for-transforming-chatgpt-into-your-ideal-dungeon-master-tool/"><u>5 Key Techniques for Transforming ChatGPT Into Your Ideal Dungeon Master Tool</u></a></li>
<li><a href="https://tech-haven.techidaily.com/agv-installation-woes-heres-how-to-tackle-top-6-issues-effectively/"><u>AGV Installation Woes? Here's How to Tackle Top 6 Issues Effectively</u></a></li>
<li><a href="https://tech-haven.techidaily.com/ai-powered-resume-building-unleashing-the-potential-of-chatgpt-for-job-applications/"><u>AI-Powered Resume Building: Unleashing the Potential of ChatGPT for Job Applications</u></a></li>
<li><a href="https://win-workspace.techidaily.com/aufschlussreiche-artikel-und-ratschlage-zur-aomei-backupsoftware-losungen-finden-fur-alle-bedurfnisse/"><u>Aufschlussreiche Artikel Und Ratschläge Zur AOMEI-Backupsoftware: Lösungen Finden Für Alle Bedürfnisse</u></a></li>
<li><a href="https://tech-haven.techidaily.com/behind-the-scenes-of-truthgpt-exposed-police-probe-into-mullvad-vpns-secrets-leading-free-pc-games-listed-and-best-practices-in-mechanical-keyboards/"><u>Behind the Scenes of TruthGPT Exposed! Police Probe Into Mullvad VPN's Secrets | Leading Free PC Games Listed & Best Practices in Mechanical Keyboards</u></a></li>
<li><a href="https://tech-haven.techidaily.com/1722033621810-eagerly-awaiting-chatgpts-desktop-launch-heres-an-excellent-open-source-substitute-to-try/"><u>Eagerly Awaiting ChatGPT's Desktop Launch? Here’s an Excellent Open-Source Substitute to Try!</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-change-location-on-tiktok-to-see-more-content-on-your-xiaomi-redmi-note-12t-pro-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change Location on TikTok to See More Content On your Xiaomi Redmi Note 12T Pro | Dr.fone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-what-is-a-sim-network-unlock-pin-get-your-lava-yuva-3-pro-phone-network-ready-by-drfone-android/"><u>In 2024, What Is a SIM Network Unlock PIN? Get Your Lava Yuva 3 Pro Phone Network-Ready</u></a></li>
<li><a href="https://tech-haven.techidaily.com/1722116938832-malicious-chromium-app-mimicking-chatgpt-protect-your-facebook-login-details-now/"><u>Malicious Chromium App Mimicking ChatGPT: Protect Your Facebook Login Details Now!</u></a></li>
<li><a href="https://tech-haven.techidaily.com/1721957618836-secure-accounts-on-messaging-platforms-with-just-your-email-learn-how/"><u>Secure Accounts on Messaging Platforms with Just Your Email - Learn How!</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/unveiling-tech-secrets-with-toms-hardware-wisdom/"><u>Unveiling Tech Secrets with Tom's Hardware Wisdom</u></a></li>
<li><a href="https://tech-haven.techidaily.com/whats-inside-chatgpt-understanding-how-this-pioneering-tool-leverages-powerful-generative-ai-techniques/"><u>What's Inside ChatGPT? Understanding How This Pioneering Tool Leverages Powerful Generative AI Techniques</u></a></li>
</ul></div>

