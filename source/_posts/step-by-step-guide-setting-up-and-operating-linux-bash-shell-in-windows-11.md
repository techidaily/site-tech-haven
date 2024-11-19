---
title: "Step-by-Step Guide: Setting Up & Operating Linux Bash Shell in Windows 11"
date: 2024-11-16T01:28:14.491Z
updated: 2024-11-18T19:47:21.933Z
tags:
  - deals
categories:
  - tech
thumbnail: https://thmb.techidaily.com/ebbfde368b81e7f396fe512ace44b149bef6fef394a1d6fd8cfa20e2c4a0b6c3.jpg
---

## Step-by-Step Guide: Setting Up & Operating Linux Bash Shell in Windows 11

### Quick Links

* [What You Need to Know About Windows 10's Bash Shell](https://hardware-tips.techidaily.com/toms-tech-corner-the-ultimate-guide-to-computer-components/)
* [How to Install Bash on Windows 10](https://android-unlock.techidaily.com/in-2024-the-ultimate-guide-to-samsung-galaxy-a54-5g-pattern-lock-screen-everything-you-need-to-know-by-drfone-android/)
* [How to Use The Bash Shell and Install Linux Software](https://remote-screen-capture.techidaily.com/new-leveraging-streamlabs-obs-for-engaging-live-streams-for-2024/)
* [Install the Ubuntu Font for a True Ubuntu Experience](https://some-approaches.techidaily.com/updated-toontech-complete-insight-2024-edition/)
* [Use the Ubuntu Monospace Font in the Console](https://facebook-record-videos.techidaily.com/new-in-2024-diy-youtube-openers-technique-one-and-technique-two/)
* [Use the Ubuntu Monospace Font in the Terminal](https://screen-video-capture.techidaily.com/in-2024-picking-the-right-software-bandicam-versus-camtasia/)

### Key Takeaways

 First, enable the Windows Subsystem for Linux (WSL) from the Features window or via the "wsl --install" command. After rebooting your PC, install Ubuntu or any other Linux distribution of your choice from the Microsoft Store.

 The Windows Subsystem for Linux, introduced in the [Anniversary Update](https://twitter-videos.techidaily.com/2024-approved-clear-obstacle-youtube-tweets-on-google-chrome/), became a stable feature in the [Fall Creators Update](https://phone-solutions.techidaily.com/does-samsung-support-mkv-video-files-by-aiseesoft-video-converter-play-mkv-on-android/). You can now run Ubuntu, openSUSE, a remix of Fedora, and plenty of others on Windows, with more Linux distributions coming soon.

##  What You Need to Know About Windows 10's Bash Shell

###  How Windows Subsystem for Linux 1 (WSL1) Works

 Windows 10 offers a full Windows Subsystem intended for Linux (WSL) for running Linux software. This isn't a [virtual machine](https://remote-screen-capture.techidaily.com/2024-approved-essential-guide-video-recording-with-vlc/), a container, or Linux software compiled for Windows (like [Cygwin](https://tech-savvy.techidaily.com/global-network-ai-versus-closed-system-deployment/)). It's based on Microsoft's abandoned Project Astoria work for running Android apps on Windows.

 Think of it as the opposite of [Wine](https://some-guidance.techidaily.com/updated-ultimate-list-best-no-cost-lut-downloads/). While Wine allows you to run Windows applications directly on Linux, the Windows Subsystem for Linux allows you to run Linux applications directly on Windows.

 Microsoft worked with Canonical to offer a full Ubuntu-based Bash shell environment that runs atop this subsystem. Technically, this isn't Linux at all. Linux is the underlying operating system kernel, and that isn't available here. Instead, this allows you to run the Bash shell and the exact same binaries you'd normally run on Ubuntu Linux. Free software purists often argue the average Linux operating system [should be called "GNU/Linux"](https://tiktok-video-recordings.techidaily.com/perfecting-your-digital-doppelganger-a-complete-guide-to-cloning-oneself-on-tiktok-for-2024/) because it's really a lot of GNU software running on the Linux kernel. The Bash shell you'll get is really just all those GNU utilities and other software.

 While this feature was originally called "Bash on Ubuntu on Windows," it also allows you to [run Zsh and other command-line shells](https://extra-support.techidaily.com/2024-approved-master-iphone-cams-with-these-hacks/). It now supports other Linux distributions, too. You can choose openSUSE Leap or SUSE Enterprise Server instead of Ubuntu, and there is a remix of Fedora available.

 There are some limitations here. It won't officially work with [graphical Linux desktop applications](https://instagram-video-recordings.techidaily.com/updated-2024-approved-mastering-instagram-profit-the-ultimate-strategy-blueprint/). Not every command-line application works, either, as the feature isn't perfect.

###  How Windows Subsystem for Linux 2 (WSL2) Works

 Windows Subsystem for Linux 2 (WSL2) is designed to provide the exact same user experience as its predecessor, but the similarities mostly end there.

 WSL2 runs a full Linux Kernel in [an extremely efficient virtual machine.](https://facebook-record-videos.techidaily.com/updated-the-infographic-index-youtubes-surprising-stat-treasury-2017/) Just like WSL1, WSL2 allows you use a range of different Linux Distros including, Ubuntu, Debian, Kali, openSUSE, Fedora, and others. That also means that most any Linux application, package, or command will work without an issue.

 WSL2 supports GUI applications on Windows 11.

##  How to Install Bash on Windows 10

 This feature doesn't work on the 32-bit version of Windows 10, so [ensure you're using the 64-bit version of Windows](https://extra-tips.techidaily.com/acclaimed-websites-for-google-pixel-tonal-sounds-for-2024/). It's time to [switch to the 64-bit version of Windows 10](https://facebook-record-videos.techidaily.com/understanding-filmoras-creative-certification-protocol-for-2024/) if you're still using the 32-bit version, anyway.

 Assuming you have 64-bit Windows, to get started, head to Control Panel > Programs > Turn Windows Features On Or Off. Enable the "Windows Subsystem for Linux" option in the list, and then click the "OK" button.

![Open up the Windows Features menu, scroll down until you find &quot;Windows Subsystem for Linux,&quot; then tick the box and click &quot;OK.&quot;](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/03/img_5a985001e7f37.png) 

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1868495/19272" target="_top" id="1868495">
  <img src="//a.impactradius-go.com/display-ad/19272-1868495" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1868495/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Click "Restart now" when you're prompted to restart your computer. The feature won't work until you reboot.

 Alternatively, you can also install it using PowerShell. [Launch PowerShell as an Administrator](https://win11.techidaily.com/a-guide-to-quickly-opens-sticky-notes-in-windows-11/), then enter:

wsl --install

 It'll take a few minutes to download and install all of the required components --- after it does, you need to restart your computer.

![PowerShell running WSL install command successfully.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/03/WSL-install.png) 

<!-- affiliate ads begin -->
<span id="1424531">
					<video width="864" height="NaN" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1424531.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/16446-1424531">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1424531.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Flaganoo.pxf.io%2Fc%2F5597632%2F1424531%2F16446'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1424531/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 After your computer restarts, open the Microsoft Store from the Start menu, and search for "Linux" in the store.

![Linux distros available on the Microsoft Store.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/11/ms-store-linux.png) 

 You'll see a list of every Linux distribution currently available in the Windows Store.This includes [Ubuntu, openSUSE Leap, and openSUSE Enterprise](https://location-social.techidaily.com/how-to-activate-and-use-life360-ghost-mode-on-nokia-c300-drfone-by-drfone-virtual-android/), Debian, Kali, and others. You can even find a few remixes of Fedora, though there isn't an official version available as of November 2023.

 If you want a specific distro, search for that rather than "Linux." You'll get better results.

 To install a Linux distribution, click it, and then click the "Get" or "Install" button to install it like any other Store application.

 If you're not sure which Linux environment to install, we recommend Ubuntu. This popular Linux distribution was previously the only option available, but other Linux systems are now available for people who have more specific needs.

![Installing Debian through the Microsoft Store.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/11/installing-debian.png) 

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135396/19272" target="_top" id="2135396">
  <img src="//a.impactradius-go.com/display-ad/19272-2135396" border="0" alt="https://techidaily.com" width="160" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135396/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 You can also install multiple Linux distributions and they'll each get their own unique shortcuts. You can even run multiple different Linux distributions at a time in different windows.

##  How to Use The Bash Shell and Install Linux Software

 You now have a full command-line bash shell through Ubuntu, or whichever other Linux distribution you installed.

 Because they're the same binaries, you can [use Ubuntu's apt or apt-get command](https://iphone-unlock.techidaily.com/8-safe-and-effective-methods-to-unlock-your-iphone-12-mini-without-a-passcode-drfone-by-drfone-ios/) to install software from Ubuntu's repositories if you're using Ubuntu. Just use whatever command you'd normally use on that Linux distribution. You'll have access to all the Linux command line software out there, although some applications may not yet work perfectly.

 To open the Linux environment you installed, just open the Start menu and search for whatever distribution you installed. For example, if you installed Ubuntu, launch the Ubuntu shortcut.

 You can pin this application shortcut to your Start menu, taskbar, or desktop for easier access.

![Searching for "Ubuntu" in the Start Menu.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/11/ubuntu-search.png) 

 The first time you launch the Linux environment, you're be prompted to enter a UNIX username and password. These don't have to match your Windows username and password, but will be used within the Linux environment.

 For example, if you enter "bob" and "letmein" as your credentials, your username in the Linux environment will be "bob" and the password you use inside the Linux environment will be "letmein" --- no matter what your Windows username and password are.

![Enter a username and password for your Linux distro.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/03/img_5a985a5c26989.png) 

 You can launch your installed Linux environment by running the `wsl` command. If you have multiple Linux distributions installed, you can [choose the default Linux environment](https://howto.techidaily.com/8-ultimate-fixes-for-google-play-your-infinix-note-30-vip-isnt-compatible-drfone-by-drfone-fix-android-problems-fix-android-problems/) this command launches.

 If you have Ubuntu installed, you can also run the `ubuntu` command to install it. For openSUSE Leap 42, use `opensuse-42` . For SUSE Linux Enterprise Sever 12, use `sles-12` . These commands are listed on each Linux distribution's page on the Windows Store.

 You can still launch your default Linux environment by running the `bash` command, but Microsoft says this is deprecated. This means the `bash` command may stop functioning in the future.

![Running &quot;bash&quot; in the Command Prompt will launch your default Linux environment.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/03/img_5a985b14e9795.png) 

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134497/18498" target="_top" id="2134497">
  <img src="//a.impactradius-go.com/display-ad/18498-2134497" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134497/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If you're experienced using a Bash shell on Linux, Mac OS X, or other platforms, you'll be right at home.

 On Ubuntu, you need to prefix a command with `sudo` to [run it with root permissions](https://extra-support.techidaily.com/maximize-your-listening-experience-ios-podcast-mastery-for-2024/). The "root" user on UNIX platforms has full system access, like the "Administrator" user on Windows. Your Windows file system is located at `/mnt/c` in the Bash shell environment.

 Use the same Linux terminal commands you'd use to get around. If you're used to the standard Windows Command Prompt with its DOS commands, here are a few basic commands common to both Bash and Windows:

* Change Directory: `cd` in Bash, `cd` or `chdir` in DOS
* List Contents of Directory: `ls` in Bash, `dir` in DOS
* Move or Rename a File: `mv` in Bash, `move` and `rename` in DOS
* Copy a File: `cp` in Bash, `copy` in DOS
* Delete a File: `rm` in Bash, `del` or `erase` in DOS
* Create a Directory: `mkdir` in Bash, `mkdir` in DOS
* Use a Text Editor: `vi` or `nano` in Bash, `edit` in DOS

 It's important to remember that, unlike Windows, the Bash shell and its Linux-imitating environment are case-sensitive. In other words, "File.txt" with a capital letter is different from "file.txt" without a capital.

 For more instructions, consult [our beginner's guide to the Linux command-line](https://facebook-clips.techidaily.com/downloading-facebook-gifs-pc-android-and-ios-guide/) and other similar introductions to the Bash shell, Ubuntu command line, and Linux terminal online.

![The command &quot;ls&quot; run in the C:\ directory to list files and folders.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/03/img_5a985d46b3c57.png) 

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135348/19272" target="_top" id="2135348">
  <img src="//a.impactradius-go.com/display-ad/19272-2135348" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135348/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 You'll need to [use the apt command](https://screen-sharing-recording.techidaily.com/updated-best-practices-in-winning-tv-recording-with-software/) to install and update the Ubuntu environment's software. Be sure to prefix these commands with `sudo` , which makes them run as root--the Linux equivalent of Administrator. Here are the apt-get commands you'll need to know:

* Download Updated Information About Available Packages: `sudo apt update`
* Install an Application Package: `sudo apt install packagename` (Replace "packagename" with the package's name.)
* Uninstall an Application Package: `sudo apt remove packagename` (Replace "packagename" with the package's name.)
* Search for Available Packages: `sudo apt search word` (Replace "word" with a word you want to search package names and descriptions for.)
* Download and Install the Latest Versions of Your Installed Packages: `sudo apt upgrade`

 If you installed a SUSE Linux distribution, you can use the [zypper command](https://doc.opensuse.org/documentation/leap/reference/html/book-reference/cha-sw-cl.html#sec-zypper) to install software instead.

 After you've downloaded and installed an application, you can type its name at the prompt, and then press Enter to run it. Check that particular application's documentation for more details.

![Installing GNU Compiler Collection with apt.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/03/img_5a985e7d80a6b.png) 

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2144277/7443" target="_top" id="2144277">
  <img src="//a.impactradius-go.com/display-ad/7443-2144277" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144277/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

##  Install the Ubuntu Font for a True Ubuntu Experience

 If you want a more accurate Ubuntu experience on Windows 10, you can also install the Ubuntu fonts and enable them in the terminal. You don't have to do this, as the default Windows command prompt font looks pretty good to us, but it's an option.

 Here's what it looks like:

![The default font, Consolas.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/03/img_5a9864cb2035c.png) 

 To install the font, first download the [Ubuntu Font Family](http://font.ubuntu.com/) from Ubuntu's website. Open the downloaded .zip file and locate the "UbuntuMono-R.ttf" file. This is the Ubuntu monospace font, which is the only one used in the terminal. It's the only font you need to install.

![Open the font ZIP file, then double-click the font you want to preview or install.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/03/img_5a985eba01a04.png) 

 Double-click the "UbuntuMono-R.ttf" file and you'll see a preview of the font. Click "Install" to install it to your system.

![Click &quot;Install&quot; near the top if you want to use the font.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/03/img_5a985ee273570.png) 

##  Use the Ubuntu Monospace Font in the Console

 To make the Ubuntu monospace font become an option in the console, you'll need to add a setting to [the Windows registry](https://facebook-record-videos.techidaily.com/new-economical-mic-options-for-youtube-vloggers-for-2024/).

 Open a registry editor by pressing Windows+R on your keyboard, typing `regedit` , and then pressing Enter. Navigate to the following key or copy and paste it into the Registry Editor's address bar:

HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows NT\CurrentVersion\Console\TrueTypeFont

![Navigate to the &quot;TrueTypeFont&quot; key.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/03/img_5a986517b1bec.png) 

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2094415/7443" target="_top" id="2094415">
  <img src="//a.impactradius-go.com/display-ad/7443-2094415" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2094415/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Right-click in the right pane and select New > String Value. Name the new value `000` .

 Double-click the "000" string you just created, and then enter `Ubuntu Mono` as its value data.

![Create a new string named &quot;000&quot;, then set the value to &quot;Ubuntu Mono&quot;.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/03/img_5a98652a926c4.png) 

 Launch an Ubuntu window, right-click the title bar, and then select the "Properties" command. Click the "Font" tab, and then select "Ubuntu Mono" in the font list.

![Right-click the title bar of the terminal application you're using, go to &quot;Properties,&quot; then click &quot;Font.&quot; Select &quot;Ubuntu Mono&quot; from the list.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/03/img_5a986560320a0.png) 

##  Use the Ubuntu Monospace Font in the Terminal

 If you're using the Windows Terminal—and you should be, it is [a big improvement in most ways](https://video-screen-grab.techidaily.com/updated-2024-approved-effortless-screen-saving-on-android-devices/)—changing fonts is easier. After you've installed the Ubuntu font, open up the Terminal, click the small downward facing arrow, and select "Settings."

![Open the Terminal Settings.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/11/open-settings-terminal.png) 

 Open to Defaults > Appearance, then select "Ubuntu Mono" from the list of available fonts.

 The Terminal automatically expands or collapses the labels in the left sidebar depending on the size of your window, much like the Settings app does. You may not see the "Default" text label depending on the size of your window.

![Enable the Ubuntu Mono font.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/11/font-ubuntu-mono.png) 

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075472/7443" target="_top" id="2075472">
  <img src="//a.impactradius-go.com/display-ad/7443-2075472" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075472/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Remember: software you install in the Bash shell is restricted to the Bash shell. You can access these programs from the Command Prompt, PowerShell, or elsewhere in Windows, but only if you [run the bash -c command](https://vp-tips.techidaily.com/building-a-brand-with-captivating-haul-videos-and-edits/).

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
<li><a href="https://article-helps.techidaily.com/new-2024-approved-gopro-showdown-full-review-and-ratings/"><u>[New] 2024 Approved GoPro Showdown Full Review and Ratings</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-in-2024-comprehensive-app-exploration-az-capture-essentials/"><u>[Updated] In 2024, Comprehensive App Exploration AZ Capture Essentials</u></a></li>
<li><a href="https://common-error.techidaily.com/dealing-with-ftdi-interface-errors-resolving-memory-compromise-due-to-driver-mismatches/"><u>Dealing with FTDI Interface Errors: Resolving Memory Compromise Due to Driver Mismatches</u></a></li>
<li><a href="https://tech-haven.techidaily.com/improving-chatgpts-plugins-hub-four-essential-developments/"><u>Improving ChatGPT's Plugins Hub: Four Essential Developments</u></a></li>
<li><a href="https://apple-account.techidaily.com/iphone-or-samsung-navigating-the-best-mobile-device-for-your-needs/"><u>IPhone or Samsung: Navigating the Best Mobile Device for Your Needs</u></a></li>
<li><a href="https://tech-haven.techidaily.com/leveraging-ai-assistance-how-chatgpt-transforms-personal-training-program-development/"><u>Leveraging AI Assistance: How ChatGPT Transforms Personal Training Program Development</u></a></li>
<li><a href="https://tech-haven.techidaily.com/redefining-ai-interaction-groundbreaking-upgrades-to-chatgpt/"><u>Redefining AI Interaction: Groundbreaking Upgrades to ChatGPT</u></a></li>
<li><a href="https://win-community.techidaily.com/revive-lost-data-a-comprehensive-guide-to-retrieving-removed-files-without-cost/"><u>Revive Lost Data: A Comprehensive Guide to Retrieving Removed Files Without Cost</u></a></li>
<li><a href="https://tech-haven.techidaily.com/revolutionize-your-slides-the-ultimate-list-of-7-ai-presentation-assistants/"><u>Revolutionize Your Slides: The Ultimate List of 7 AI Presentation Assistants</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/subscribe-bonanza-thousands-acquired-for-just-5/"><u>Subscribe Bonanza Thousands Acquired for Just $5</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/the-evolution-continues-discover-appleamo-new-phone-release/"><u>The Evolution Continues: Discover Apple'amo New Phone Release</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/thorough-assessment-of-the-kootek-portable-air-blower-ideal-for-any-laptop/"><u>Thorough Assessment of the Kootek Portable Air Blower: Ideal for Any Laptop!</u></a></li>
<li><a href="https://tech-haven.techidaily.com/top-4-enhancements-we-anticipate-in-gpt-5/"><u>Top 4 Enhancements We Anticipate in GPT-5</u></a></li>
<li><a href="https://tech-haven.techidaily.com/unlock-creative-writing-for-youtube-how-to-leverage-chatgpt-for-engaging-scripts/"><u>Unlock Creative Writing for YouTube: How to Leverage ChatGPT for Engaging Scripts</u></a></li>
</ul></div>

