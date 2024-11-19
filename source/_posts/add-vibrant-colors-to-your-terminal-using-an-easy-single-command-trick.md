---
title: Add Vibrant Colors to Your Terminal Using an Easy Single-Command Trick
date: 2024-11-13T01:01:22.132Z
updated: 2024-11-19T02:03:21.909Z
tags:
  - desktop
categories:
  - tech
thumbnail: https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/08/a-scene-with-clouds-and-a-rainbow-featuring-a-linux-terminal-on-a-podium-with-tux-standing-behind-it.jpg
---

## Add Vibrant Colors to Your Terminal Using an Easy Single-Command Trick

### Quick Links

* [What Is the lolcat Command?](https://extra-lessons.techidaily.com/dissecting-the-utility-of-sns-hdr-for-hdri-tasks/)
* [lolcat Command Options](https://facebook-video-footage.techidaily.com/updated-in-2024-expert-audio-adjustments-for-youtube-content-makers/)
* [Get Colored Terminal Output](https://android-frp.techidaily.com/full-guide-to-bypass-oppo-reno-11-pro-5g-frp-by-drfone-android/)
* [Animate Your Text Using lolcat](https://android-pokemon-go.techidaily.com/in-2024-best-pokemons-for-pvp-matches-in-pokemon-go-for-lava-storm-5g-drfone-by-drfone-virtual-android/)
* [Create Colorful ASCII Text Banner](https://unlock-android.techidaily.com/in-2024-top-15-apps-to-hack-wifi-password-on-infinix-hot-40i-by-drfone-android/)
* [Make Things Interesting With cowsay](https://youtube-docs.techidaily.com/024-approved-optimal-video-posting-frequency-for-increased-youtube-popularity/)

### Key Takeaways

* You can use the lolcat command to add vibrant rainbow colors to terminal text output for a playful touch.
* Apply lolcat to any Linux command to get colored output, such as listing files and directories with ls, displaying system information with neofetch, and more.
* Additionally, you can animate text, create colorful ASCII text banners, and combine lolcat with cowsay for fun displays.

 Any Linux enthusiast will tell you all the fun takes place in the terminal. Unfortunately, the standard terminal text or output text from commands can often feel dull and boring. But not anymore. With the delightful lolcat tool, you can now change your terminal output into a colorful rainbow display.

##  What Is the lolcat Command?

 lolcat is a command-line tool that works much like the [cat command](https://instagram-videos.techidaily.com/updated-sneak-peeks-into-instagrams-latest-hacks-for-2024/). However, it adds a fun twist by applying the vibrant rainbow effect to your terminal text. In short, lolcat reads your standard input, character by character, and assigns a rainbow color to each.

 With lolcat, you can turn your simple text into something that really pops, adding a playful touch or highlighting key details in your terminal output.

 To get started with lolcat, you need to install it first. You can use your default package manager to set it up on your Linux system.

 However, be aware that there are two different versions available to you. The original, which includes more features such as the animation flag, is available as a Snap package or through the apt package manager on Debian-based systems. If you [have snapd installed](https://ai-driven-video-production.techidaily.com/in-2024-create-a-stunning-video-resume-top-4-makers-with-free-resources/), you can open your terminal and type:

sudo snap install lolcat

 If you are an Ubuntu or Debian-based user, you can install the original using this command:

sudo apt install lolcat

 The more widely available version, however, uses less space and functions basically the same but lacks some of the extra features. You can also install it as a snap by typing:

sudo snap install lolcat-c

 If you're running Fedora or CentOS, you'll want to use:

sudo dnf install lolcat

 And for those of you rocking Arch Linux or Manjaro:

sudo pacman -S lolcat

 Once you've installed lolcat, you're ready to use it and apply rainbow colors to your output text.

<!-- affiliate ads begin -->
<a href="https://review-au.sjv.io/c/5597632/2098700/14409" target="_top" id="2098700">
  <img src="//a.impactradius-go.com/display-ad/14409-2098700" border="0" alt="https://techidaily.com" width="160" height="90"/>
</a>
<img height="0" width="0" src="https://review-au.sjv.io/i/5597632/2098700/14409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

##  lolcat Command Options

 While the default lolcat behavior is already pretty awesome, there are a few options to tweak the output to your liking. For example, with these various flags, you can adjust the pattern of rainbow colors, modify the speed, and change a few other settings.

 Now, let's look at some of the most useful options in the original version:

| **Option**        | **Description**                                                                                       |
| ----------------- | ----------------------------------------------------------------------------------------------------- |
| \-a or --animate  | Animate the colors so that they move across the text over time.                                       |
| \-p or --spread   | Adjust the spread of the color gradient.                                                              |
| \-d or --duration | Set the duration of the animation. For example, -d 0.1 will make the colors change every 0.1 seconds. |
| \-s or --speed    | Controls how fast your text grooves across the screen. A higher number means faster color changes.    |
| \-f or --freq     | Use this flag to specify the frequency of the color pattern. (default: 0.1)                           |
| \-S or --seed     | Use this option to set a random seed and get a whole new color pattern.                               |

 You can view all these and other options of lolcat (and the newer version's differing flags) by running this:

lolcat --help

 Alternatively, you can use the [man page](https://video-capture.techidaily.com/in-2024-masterclass-flawless-powerpoint-screen-recordings/) of lolcat to find out all the important details.

man lolcat

##  Get Colored Terminal Output

 Now that you're familiar with the lolcat command and its options, let's see how you can use it to get colored terminal output. One of the easiest ways to use lolcat is to [pipe the output](https://review-topics.techidaily.com/how-to-transfer-whatsapp-from-iphone-11-pro-to-other-iphone-11-pro-devices-drfone-by-drfone-transfer-whatsapp-from-ios-transfer-whatsapp-from-ios/) of another Linux command through lolcat. For instance, if you want to colorize the output of the [ls command](https://extra-tips.techidaily.com/in-2024-capturecraft-hd-top-10-freepaid-filters-list/), you can run this:

ls | lolcat

![Listing files and directories of Ubuntu Linux in colored output using lolcat.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/08/ls-lolcat-command.png) 

<!-- affiliate ads begin -->
<span id="1484963">
					<video width="864" height="864" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1484963.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/16446-1484963">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1484963.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Flaganoo.pxf.io%2Fc%2F5597632%2F1484963%2F16446'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1484963/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 This will display the list of files and directories in a beautiful, rainbow-colored format. In the same way, you can apply lolcat to any command, such as [grep](https://screen-recording.techidaily.com/updated-10-superior-choices-high-end-video-conferencing-software-for-2024/) or man, and colorize its output text.

 Let's display the contents of a file in a rainbow spectrum using lolcat:

lolcat file.txt

![Displaying file content in colored output on Linux terminal using lolcat command.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/08/lolcat-file-output.png) 

 Want to see your system information using [neofetch](https://facebook-videos.techidaily.com/updated-2024-approved-easy-steps-for-achieving-facebooks-prestigious-blue-badge/) in rainbow glory? Try running this:

neofetch | lolcat

![Getting system information in rainbow colored format using neofetch and lolcat.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/08/neofetch-lolcat.png) 

 You can also [create a permanent alias](https://hardware-help.techidaily.com/download-the-latest-logitech-camera-drivers-at-no-cost-for-windows-users/) for a frequently used command to automatically output in vibrant colors. For example, you can permanently set up an alias for the ls -l command by adding the following line to the [\~/.bashrc file](https://phone-solutions.techidaily.com/3-easy-solutions-to-hard-reset-nokia-xr21-drfone-by-drfone-reset-android-reset-android/):

alias lolls="ls -l | lolcat"

 Simply open the \~/.bashrc file in Vim:

vim ~/.bashrc

![Setting up an alias for the ls -l command in the ~/.bashrc file.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/08/alias-lolcat.png) 

<!-- affiliate ads begin -->
<a href="https://united.elfm.net/c/5597632/2139563/4704" target="_top" id="2139563">
  <img src="//a.impactradius-go.com/display-ad/4704-2139563" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://united.elfm.net/i/5597632/2139563/4704" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 After creating the alias, don’t forget to log out and back in to apply the changes.

 Now, when you type **lolls**, the system will execute the command ls -l and pipe its output to lolcat for a colorful display.

lolls

![Displaying files and directories in long colored format using the alias lolls.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/08/lolls-lolcat.png) 

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118320/7443" target="_top" id="2118320">
  <img src="//a.impactradius-go.com/display-ad/7443-2118320" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118320/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135419/19272" target="_top" id="2135419">
  <img src="//a.impactradius-go.com/display-ad/19272-2135419" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135419/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

##  Animate Your Text Using lolcat

 Why settle for static colors when you can animate them? One of the most entertaining features of lolcat is its ability to animate text, making it feel like the colors are dancing across your terminal. To animate the output, simply add the -a or --animate flag:

echo "Welcome to HTG" | lolcat --animate

 Unfortunately, the animate flag only works in the original lolcat. If you're using the newer version, this flag will result in a "No such file or directory" error.

 The text will remain static, but the colors will continuously shift across the text, creating a mesmerizing effect.

 However, the color-changing animation will last only for a short time due to its default settings. You can also extend the animation duration using the -d flag of lolcat:

echo "Welcome to HTG" | lolcat --animate -d 500

 Furthermore, if the animation is too fast or too slow for your liking, you can adjust the speed with the -s option:

echo "Welcome to HTG" | lolcat --animate -s 5

 This command slows down the animation, giving you a more relaxed visual experience.

##  Create Colorful ASCII Text Banner

 Want to create a colorful ASCII text banner in your terminal? Look no further than lolcat. By combining lolcat with the figlet command, you can create a beautiful, rainbow-colored banner that'll make your terminal stand out.

 First, you’ll need to install figlet if it’s not already on your system. You can get figlet using your default package manager, such as [apt](https://fake-location.techidaily.com/prank-your-friends-easy-ways-to-fake-and-share-google-maps-location-on-tecno-camon-20-premier-5g-drfone-by-drfone-virtual-android/) on Ubuntu or Debian-based distro:

sudo apt install figlet

 For RHEL/CentOS/Fedora Linux, run:

sudo dnf install figlet

 On Arch Linux:

sudo pacman -S figlet

 Now, you can pipe figlet output with lolcat to display a colorful ASCII text banner with some text:

figlet "Welcome to HTG" | lolcat

![Displaying ASCII text banner in rainbow colored format using figlet and lolcat command.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/08/figlet-lolcat.png) 

 You can also adjust the fonts used by figlet to create different styles of text. For example, to get the same previous banner with a different font, run this:

figlet -f slant "Welcome to HTG" | lolcat

![Displaying an ASCII text banner in the terminal with a rainbow-colored format and using a slant font.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/08/figlet-lolcat-font-differnet.png) 

<!-- affiliate ads begin -->
<a href="https://wigfever.sjv.io/c/5597632/2014853/22899" target="_top" id="2014853">
  <img src="//a.impactradius-go.com/display-ad/22899-2014853" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://wigfever.sjv.io/i/5597632/2014853/22899" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

##  Make Things Interesting With cowsay

 Want to make things more funny? Let's combine lolcat with [cowsay](https://github.com/cowsay-org/cowsay). This fun command allows you to create speech bubbles with cute animal characters that display a message you provide.

 But first, install cowsay from your default package manager if you don't already have it. To get it on Ubuntu or Debian, type this:

sudo apt install cowsay

 For RHEL or CentOS Linux, run:

sudo dnf install cowsay

 If you are an Arch Linux user:

sudo pacman -S cowsay

 Next, combine it with lolcat to get a rainbow-colored cow:

cowsay "Linux is Funny" | lolcat

![Displaying a rainbow-colored cow in the terminal window with some text.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/08/cowsay-linux-lolcat.png) 

 But why stop at cows? Cowsay comes with a whole menagerie of ASCII animals. Let's see what a rainbow tux has to say:

cowsay -f tux "Linux is cool" | lolcat

![Displaying a rainbow-colored tux in the terminal window.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/08/tux-lolcat-cowsay.png) 

 Tux has never looked so fabulous!

---

 Similar to the lolcat command, the Linux terminal also [offers a variety of entertaining commands](https://fox-friendly.techidaily.com/updated-2024-approved-podcastpathfinder-charting-new-courses/) and tricks to explore when you're looking to have a bit of fun. Whether you're [customizing your terminal](https://fox-friendly.techidaily.com/updated-expert-guide-to-screen-zooming-on-microsoft-teams-for-2024/) or just passing the time, there's always something new to find out.

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
<li><a href="https://vp-tips.techidaily.com/new-amplify-your-iphone-films-with-free-audio-additions-discover-three-ways/"><u>[New] Amplify Your iPhone Films with Free Audio Additions – Discover Three Ways</u></a></li>
<li><a href="https://extra-hints.techidaily.com/new-capturing-and-crafting-your-essential-guide-to-gopro-4k-edits/"><u>[New] Capturing and Crafting Your Essential Guide to GoPro 4K Edits</u></a></li>
<li><a href="https://fox-glue.techidaily.com/new-in-2024-quality-overload-top-10-hd-video-apps-for-your-android/"><u>[New] In 2024, Quality Overload Top 10 HD Video Apps for Your Android</u></a></li>
<li><a href="https://discover-cheats.techidaily.com/beliebteste-faqs-zur-datenwiederherstellung-mit-aomei/"><u>Beliebteste FAQs Zur Datenwiederherstellung Mit AOMEI</u></a></li>
<li><a href="https://tech-haven.techidaily.com/enhancing-security-change-your-email-through-proton-vpn-add-on-for-chrome-and-detecting-fake-chatgpt-apps-for-pc/"><u>Enhancing Security: Change Your Email Through Proton VPN Add-On for Chrome and Detecting Fake ChatGPT Apps for PC</u></a></li>
<li><a href="https://technical-tips.techidaily.com/essential-guide-the-top-6-journaling-apps-you-cant-miss/"><u>Essential Guide: The Top 6 Journaling Apps You Can't Miss</u></a></li>
<li><a href="https://youtube-help.techidaily.com/hasty-instruction-saving-your-photos-as-youtube-channel-thumbnails-for-2024/"><u>Hasty Instruction Saving Your Photos as YouTube Channel Thumbnails for 2024</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-fix-oppo-reno-11-pro-5g-find-my-friends-no-location-found-drfone-by-drfone-virtual-android/"><u>How to Fix Oppo Reno 11 Pro 5G Find My Friends No Location Found? | Dr.fone</u></a></li>
<li><a href="https://tech-haven.techidaily.com/insights-from-scripting-a-podcast-using-chatgpt-what-you-need-to-know/"><u>Insights From Scripting a Podcast Using ChatGPT: What You Need to Know</u></a></li>
<li><a href="https://extra-support.techidaily.com/leading-steadicam-choices-for-improved-dslr-footage-for-2024/"><u>Leading Steadicam Choices for Improved DSLR Footage for 2024</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/navigating-your-roku-television-sans-remote-tips-and-tricks/"><u>Navigating Your Roku Television Sans Remote - Tips and Tricks</u></a></li>
<li><a href="https://tech-haven.techidaily.com/numeric-excellence-excel-surpasses-gpt-in-complex-calculations/"><u>Numeric Excellence: Excel Surpasses GPT in Complex Calculations</u></a></li>
<li><a href="https://tech-haven.techidaily.com/seamless-siri-chatgpt-synergy-for-iphone-enthusiasts-tips-and-tricks/"><u>Seamless Siri-ChatGPT Synergy for iPhone Enthusiasts: Tips & Tricks</u></a></li>
<li><a href="https://tech-haven.techidaily.com/the-role-of-vector-databases-in-accelerating-advanced-ai-applications/"><u>The Role of Vector Databases in Accelerating Advanced AI Applications</u></a></li>
</ul></div>

