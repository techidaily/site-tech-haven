---
title: "Simplifying Windows CMD: A Step-by-Step Guide to Modifying the PATH Environment Variable"
date: 2024-11-13T19:10:20.051Z
updated: 2024-11-18T20:41:57.083Z
tags:
  - deals
categories:
  - tech
thumbnail: https://thmb.techidaily.com/2a75585c706bda1c98b7ca78005e810cc4fa04565ec0bfaa1522a3466ddc9fcb.jpg
---

## Simplifying Windows CMD: A Step-by-Step Guide to Modifying the PATH Environment Variable

### Quick Links

* [What Is the Windows System PATH?](https://facebook-record-videos.techidaily.com/updated-harmonizing-youtube-content-a-guide-to-blending-files/)
* [How to Add a Folder to Your PATH](https://fox-cloud.techidaily.com/new-quirky-creations-your-guide-to-no-cost-memes/)

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139122/17108" target="_top" id="2139122">
  <img src="//a.impactradius-go.com/display-ad/17108-2139122" border="0" alt="https://techidaily.com" width="468" height="60"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139122/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Key Takeaways

 The PATH tells Windows where it should look for executables, making them accessible via command-line interfaces or scripts. To add a new folder to PATH, navigate to Advanced System Settings > Environment Variables, select PATH, click "Edit" and then "New."

 Have you ever wondered why you can just type ipconfig into a command prompt and it works, but when you want to use a command line program you downloaded you have to navigate to its directory first? Here's how to fix that using the Windows System PATH on Windows 10 and Windows 11.

##  What Is the Windows System PATH?

 The Windows System PATH tells your PC where it can find specific directories that contain executable files. Ipconfig.exe, for example, is found in the C:\\Windows\\System32 directory, which is a part of the system PATH by default. When you type ipconfig into a Command Prompt, Windows doesn't need to know where that EXE is—it'll check all the folders in its PATH until it finds the right one.

 If you've downloaded a program that uses a command-line interface—like ADB, the [Android Debug Bridge](https://techtrends.techidaily.com/how-to-successfully-obtain-a-refund-for-your-purchased-games-on-steam/)—you can't just type adb in the Command Prompt or PowerShell to run it, like you can with Windows' built-in commands (e.g.ipconfig). Instead, you have to tell Command Prompt where to find that file, by typing in the full path of the EXE:

C:\Android\platform-tools\adb.exe

 If you don't, you'll get an error message like this.

![ADB is not recognized since it is not on the system PATH.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/03/adb-error.png) 

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135353/19272" target="_top" id="2135353">
  <img src="//a.impactradius-go.com/display-ad/19272-2135353" border="0" alt="https://techidaily.com" width="180" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135353/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 That's a lot of typing, especially for something you have to run often.

 If you want the same convenience with a program you downloaded (like ADB), you need to add its folder to Windows' system PATH. That way, when you need to run adb, you can just run:

adb

 No extra typing necessary.

##  How to Add a Folder to Your PATH

 These steps are basically the same on Windows 10 and Windows 11\. There are just some minor differences in the user interface.

 Start by pressing the Windows key to open up the Start Menu, then search for "advanced system settings." You can alternatively browse through Control Panel to System and Security > System and click on the "Advanced system settings" hyperlink in the left-hand pane.

![Search for and open "Advanced System Settings."](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/11/advanced-system.png) 

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1868499/19272" target="_top" id="1868499">
  <img src="//a.impactradius-go.com/display-ad/19272-1868499" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1868499/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Once the System Properties window opens, click on the "Environment Variables" button.

![Click &quot;Environment Variables.&quot;](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/03/environmental-variables.png) 

 In the "System Variables" box, look for a variable called _Path._ Select that and click on the "Edit" button.

 You can modify the PATH for only the current user by changing the PATH variable under "User Variables." It won't affect other users, however. In many cases, it is better and more convenient to add something to the system PATH, so it is universally accessible on your PC.

![Select &quot;PATH&quot; under &quot;System Variables,&quot; then click &quot;Edit.&quot;](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/03/system-variables.png) 

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075471/7443" target="_top" id="2075471">
  <img src="//a.impactradius-go.com/display-ad/7443-2075471" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075471/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 This process is both easier and less confusing in Windows 10 and Windows 11 than it was in earlier versions of Windows. Once you've clicked the edit button, a new dialog box will appear with each location in the PATH on a separate line. This is a dramatic improvement over the way previous versions of Windows handled PATH locations and makes easy work of adding a new one.

![The current PATH.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/03/PATH-Stuff.png) 

 First, click the 'new' button, which will add a line at the end of the list. Add your location—"C:\\AndroidSDK" in our example—and hit Enter. Click the "OK" button and you're finished.

 Older versions of Windows required each line end with a semi-colon, but Windows 10 and 11 do not if you use the user interface like we are here. If you use a command-line interface to edit the PATH, you'll still find them there.

![Click &quot;New,&quot; enter the path to ADB, then click &quot;OK.&quot;](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/03/android-SD.png) 

 The Android Debugging Bridge should now be accessible from any Command Prompt, PowerShell, or Windows Terminal, with no need to specify its directory.

![ADB now works in PowerShell without specifying the path manually.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/03/adb-on-path.png) 

 You can add as many locations as you like to PATH. However, convention and best practice dictate that you try to avoid cluttering up your PATH with unnecessary executables.

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
<li><a href="https://instagram-clips.techidaily.com/updated-2024-approved-degrees-matter-rotating-videos-for-social-glory/"><u>[Updated] 2024 Approved Degrees Matter Rotating Videos for Social Glory</u></a></li>
<li><a href="https://some-guidance.techidaily.com/pcmac/"><u>効率的なビデオエンコーディングプロセス: 迅速かつクリアな動画変換法（PCとMac両方対応） -高速・高品質</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/el-choices-youtube-vs-tiktok-battle-for-2024/"><u>Channel Choices Youtube vs TikTok Battle for 2024</u></a></li>
<li><a href="https://tech-haven.techidaily.com/chatgpts-game-time-discover-the-six-most-exciting-playable-options/"><u>ChatGPT's Game Time! Discover the Six Most Exciting Playable Options</u></a></li>
<li><a href="https://tech-haven.techidaily.com/crafting-conversations-using-chatgpts-wolframalpha-feature/"><u>Crafting Conversations Using ChatGPT's WolframAlpha Feature</u></a></li>
<li><a href="https://data-safeguard.techidaily.com/guaranteed-privacy-protection-the-best-way-to-remove-files-and-folders-in-windows-using-steller-tool/"><u>Guaranteed Privacy Protection: The Best Way to Remove Files and Folders in Windows Using Steller Tool</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-data-from-iphone-15-drfone-by-drfone-ios-data-recovery-ios-data-recovery/"><u>How To Recover Data from iPhone 15? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-registry-editor-access-control-in-win11/"><u>Mastering Registry Editor Access Control in Win11</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/mastering-technology-a-deep-dive-into-toms-hardware-findings/"><u>Mastering Technology: A Deep Dive Into Tom's Hardware Findings</u></a></li>
<li><a href="https://tech-haven.techidaily.com/privacy-centric-ai-messaging-unleashed-by-duckduckgo-experience-secure-smart-talks/"><u>Privacy-Centric AI Messaging Unleashed by DuckDuckGo – Experience Secure, Smart Talks</u></a></li>
<li><a href="https://tech-haven.techidaily.com/the-core-of-7-gpt-4-applications-an-analysis/"><u>The Core of 7 GPT-4 Applications: An Analysis</u></a></li>
<li><a href="https://tech-haven.techidaily.com/the-next-level-for-gaming-exploring-the-impact-of-artificial-intelligence-on-game-design-and-development/"><u>The Next Level for Gaming: Exploring the Impact of Artificial Intelligence on Game Design and Development</u></a></li>
<li><a href="https://tech-haven.techidaily.com/top-5-limitations-of-using-chatgpt-for-analyzing-cryptocurrency-markets/"><u>Top 5 Limitations of Using ChatGPT for Analyzing Cryptocurrency Markets</u></a></li>
</ul></div>

