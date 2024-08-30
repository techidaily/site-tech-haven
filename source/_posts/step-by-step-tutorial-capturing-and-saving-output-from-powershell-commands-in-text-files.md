---
title: "Step-by-Step Tutorial: Capturing and Saving Output From PowerShell Commands in Text Files"
date: 2024-08-27 10:37:42
updated: 2024-08-29 12:10:29
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

### Key Takeaways

* To save a PowerShell command's output to a TXT file, type the command, press Spacebar, type the > (greater than) symbol, press Spacebar, and type the full path to the TXT file.
* To generate a CSV file from a PowerShell command, type your command, press Spacebar, type the | (pipe) sign, press Spacebar, type "Export-CSV", press Spacebar, enter the full path to the CSV file, press Spacebar, type "-NoTypeInformation", and press Enter.

 Do you want to save your PowerShell command’s result in a TXT (text) or CSV (comma-separated values) file on your computer? If so, it's easy to do, and we'll show you how on your Windows 11 or Windows 10 PC.

##  Send a PowerShell Command's Output to a Text File

 To write your PowerShell command’s output to a text (TXT) file, first [launch a PowerShell window](https://techtrends.techidaily.com/what-are-the-stages-in-a-game-of-royal-match/). Here, type whatever command you need, the output of which you want in a text file. After you’ve typed the command, press Spacebar, type the > (greater than) symbol, press Spacebar, enter the full path to the text file where you want to save the output, and press Enter.

 For example, if you want to save the “[systeminfo](https://tech-haven.techidaily.com/has-chatgpt-simplified-or-compromised-academic-writings/)” command’s output to a file named "SystemInfo.txt" on your desktop, your command will look something like the following:

systeminfo > C:\Users\mahes\Desktop\SystemInfo.txt

!['systeminfo' command highlighted on a PowerShell window.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/10/1-systeminfo-command-output-txt-file.jpg) 

 As soon as you press Enter, PowerShell creates your specified file and adds your command’s result to it. When that’s done, access your specified path, and you’ll find your newly created file there.

##  Send a PowerShell Command's Output to a CSV File

 If you want to create a CSV file containing the output of your specified PowerShell command, use the tool’s "Export-CSV" [cmdlet](https://extra-guidance.techidaily.com/new-prophotomaster-the-ai-enhanced-editing-edge/).

 To do that, launch PowerShell. Here, enter your command (the results of which you want in a CSV file). Then, press Spacebar, enter the | (pipe) sign, press Spacebar, enter "Export-CSV", press Spacebar, enter the full path to the CSV file you want to create, press Spacebar, type "-NoTypeInformation", and press Enter.

 For example, if you want to save the current directory’s item list in a file called "List.csv" on your desktop, you’d use a command that looks like the following. Note that the "NoTypeInformation" parameter here tells the command not to include the #TYPE information header in your CSV file.

Get-ChildItem | Export-CSV C:\Users\mahes\Desktop\List.csv -NoTypeInformation

!['Get-ChildItem' cmdlet highlighted in PowerShell.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/10/2-directory-item-csv-file.jpg) 

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
