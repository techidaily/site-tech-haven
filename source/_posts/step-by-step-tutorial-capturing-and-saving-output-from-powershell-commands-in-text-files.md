---
title: "Step-by-Step Tutorial: Capturing and Saving Output From PowerShell Commands in Text Files"
date: 2024-11-15T18:31:11.019Z
updated: 2024-11-18T19:25:16.611Z
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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2151868/7443" target="_top" id="2151868">
  <img src="//a.impactradius-go.com/display-ad/7443-2151868" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151868/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Key Takeaways

* To save a PowerShell command's output to a TXT file, type the command, press Spacebar, type the > (greater than) symbol, press Spacebar, and type the full path to the TXT file.
* To generate a CSV file from a PowerShell command, type your command, press Spacebar, type the | (pipe) sign, press Spacebar, type "Export-CSV", press Spacebar, enter the full path to the CSV file, press Spacebar, type "-NoTypeInformation", and press Enter.

 Do you want to save your PowerShell command’s result in a TXT (text) or CSV (comma-separated values) file on your computer? If so, it's easy to do, and we'll show you how on your Windows 11 or Windows 10 PC.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135393/19272" target="_top" id="2135393">
  <img src="//a.impactradius-go.com/display-ad/19272-2135393" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135393/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

##  Send a PowerShell Command's Output to a Text File

 To write your PowerShell command’s output to a text (TXT) file, first [launch a PowerShell window](https://techtrends.techidaily.com/what-are-the-stages-in-a-game-of-royal-match/). Here, type whatever command you need, the output of which you want in a text file. After you’ve typed the command, press Spacebar, type the > (greater than) symbol, press Spacebar, enter the full path to the text file where you want to save the output, and press Enter.

 For example, if you want to save the “[systeminfo](https://tech-haven.techidaily.com/has-chatgpt-simplified-or-compromised-academic-writings/)” command’s output to a file named "SystemInfo.txt" on your desktop, your command will look something like the following:

systeminfo > C:\Users\mahes\Desktop\SystemInfo.txt

!['systeminfo' command highlighted on a PowerShell window.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/10/1-systeminfo-command-output-txt-file.jpg) 

 As soon as you press Enter, PowerShell creates your specified file and adds your command’s result to it. When that’s done, access your specified path, and you’ll find your newly created file there.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135348/19272" target="_top" id="2135348">
  <img src="//a.impactradius-go.com/display-ad/19272-2135348" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135348/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

##  Send a PowerShell Command's Output to a CSV File

 If you want to create a CSV file containing the output of your specified PowerShell command, use the tool’s "Export-CSV" [cmdlet](https://extra-guidance.techidaily.com/new-prophotomaster-the-ai-enhanced-editing-edge/).

 To do that, launch PowerShell. Here, enter your command (the results of which you want in a CSV file). Then, press Spacebar, enter the | (pipe) sign, press Spacebar, enter "Export-CSV", press Spacebar, enter the full path to the CSV file you want to create, press Spacebar, type "-NoTypeInformation", and press Enter.

 For example, if you want to save the current directory’s item list in a file called "List.csv" on your desktop, you’d use a command that looks like the following. Note that the "NoTypeInformation" parameter here tells the command not to include the #TYPE information header in your CSV file.

Get-ChildItem | Export-CSV C:\Users\mahes\Desktop\List.csv -NoTypeInformation

!['Get-ChildItem' cmdlet highlighted in PowerShell.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/10/2-directory-item-csv-file.jpg) 

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1885932/19272" target="_top" id="1885932">
  <img src="//a.impactradius-go.com/display-ad/19272-1885932" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1885932/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 When you’ve finished running the command, you’ll have a file called "List.csv" on your desktop containing the list of the items in your current directory.

##  View Your Text or CSV File’s Contents in PowerShell

 You can view your newly created text or CSV file’s contents right inside PowerShell. You don’t have to leave the tool and use another app to open your files.

 To do that, open a PowerShell window, type the following command, replacing "PATH" with the full path to your text or CSV file, and press Enter.

Type PATH

 For example, if you want to [read the contents of a file](https://tiktok-video-files.techidaily.com/updated-key-points-to-consider-when-navigating-tiktok-web-on-macos-for-2024/) named "SystemInfo.txt" placed on your desktop, you’d use the following command:

Type C:\Users\mahes\Desktop\SystemInfo.txt

![A TXT file's contents displayed in PowerShell using the 'Type' command.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/10/3-read-file-powershell.jpg) 

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
<li><a href="https://article-knowledge.techidaily.com/new-in-2024-direct-pathway-iphone-media-to-pc-transfer/"><u>[New] In 2024, Direct Pathway IPhone Media to PC Transfer</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-2024-approved-seamless-transfer-your-path-to-storing-instagram-videos-on-pc/"><u>[Updated] 2024 Approved Seamless Transfer Your Path to Storing Instagram Videos on PC</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/updated-curated-queries-for-spirited-conversations-in-podcasts/"><u>[Updated] Curated Queries for Spirited Conversations in Podcasts</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-learning-to-let-go-of-hurtful-comments/"><u>[Updated] Learning to Let Go of Hurtful Comments</u></a></li>
<li><a href="https://discover-blog.techidaily.com/asociarse-con-winx-dvd-mejorando-el-exito-de-tu-empresa/"><u>Asociarse Con WinX DVD - Mejorando El Éxito De Tu Empresa</u></a></li>
<li><a href="https://tech-haven.techidaily.com/chatgpt-and-data-protection-understanding-the-potential-threats-to-user-privacy/"><u>ChatGPT and Data Protection: Understanding the Potential Threats to User Privacy</u></a></li>
<li><a href="https://tech-haven.techidaily.com/content-creation-revolutionized-by-chatgpt-explore-the-9-most-impactful-features-for-writers/"><u>Content Creation Revolutionized by ChatGPT - Explore the 9 Most Impactful Features for Writers</u></a></li>
<li><a href="https://win11.techidaily.com/guide-setting-up-the-legacy-slamius-wizard-on-kodi-19-and-18-lasting-solutions/"><u>Guide: Setting up the Legacy Slamius Wizard on Kodi 19 & 18 – Lasting Solutions</u></a></li>
<li><a href="https://techidaily.com/how-to-transfer-whatsapp-from-apple-iphone-15-pro-to-other-iphone-14-pro-devices-drfone-by-drfone-transfer-whatsapp-from-ios-transfer-whatsapp-from-ios/"><u>How To Transfer WhatsApp From Apple iPhone 15 Pro to other iPhone 14 Pro devices? | Dr.fone</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-5-hassle-free-solutions-to-fake-location-on-find-my-friends-of-vivo-t2-pro-5g-drfone-by-drfone-virtual-android/"><u>In 2024, 5 Hassle-Free Solutions to Fake Location on Find My Friends Of Vivo T2 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://tech-haven.techidaily.com/innovative-ways-to-craft-unique-dandd-characters-by-leveraging-chatgpt-and-dall-e-technologies/"><u>Innovative Ways to Craft Unique D&D Characters by Leveraging ChatGPT and DALL-E Technologies</u></a></li>
<li><a href="https://tech-haven.techidaily.com/is-openais-grip-on-chatgpt-starting-to-slip-away/"><u>Is OpenAI's Grip on ChatGPT Starting to Slip Away?</u></a></li>
<li><a href="https://tech-haven.techidaily.com/next-level-ai-solutions-10-unique-gpt-variants-surpassing-chatgpts-functionality/"><u>Next-Level AI Solutions: 10 Unique GPT Variants Surpassing ChatGPT's Functionality</u></a></li>
<li><a href="https://tech-haven.techidaily.com/streamline-ai-tasks-beginning-with-auto-gpt/"><u>Streamline AI Tasks: Beginning with Auto-GPT</u></a></li>
<li><a href="https://tech-haven.techidaily.com/the-pros-and-cons-of-using-chatgpt-or-bard-for-informed-investment-decisions-do-they-really-work/"><u>The Pros and Cons of Using ChatGPT or Bard for Informed Investment Decisions - Do They Really Work?</u></a></li>
<li><a href="https://tech-haven.techidaily.com/the-ultimate-list-of-pos-alternatives-to-gpt-on-mobile-devices/"><u>The Ultimate List of POS Alternatives to GPT on Mobile Devices</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/updated-2024-approved-replace-sony-vegas-with-these-powerful-windows-video-editing-tools/"><u>Updated 2024 Approved Replace Sony Vegas with These Powerful Windows Video Editing Tools</u></a></li>
</ul></div>

