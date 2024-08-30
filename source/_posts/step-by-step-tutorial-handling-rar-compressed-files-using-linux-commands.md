---
title: "Step-by-Step Tutorial: Handling RAR Compressed Files Using Linux Commands"
date: 2024-08-26 11:57:21
updated: 2024-08-29 10:58:53
tags:
  - desktop
categories:
  - tech
thumbnail: https://thmb.techidaily.com/667b327336657b37d917ada8179b0c23c67339c9f07504ad9ddbf600b0c76aae.jpg
---

## Step-by-Step Tutorial: Handling RAR Compressed Files Using Linux Commands

### Key Takeaways

* Create RAR files on Linux by adding files or directories to the archive using the "rar a <RAR file name> <file and directory list>" command.
* Extract files from an existing RAR file on Linux using the "unrar e <RAR file name>" command. You can also list the archive content using the "unrar l <RAR file name>" command.
* To add files to an existing RAR file, use the "rar u <existing RAR file name> <new file name>" command.

 Did you end up with a RAR file that needs extracting, or is a colleague asking for files archived in a RAR format? Though RAR files are rare on Linux, you can do most of the operations such as creating, extracting, and splitting RARs on Linux from your terminal.

 In this article, we'll explore how you can create RAR files and extract content from existing ones, and discuss other ways to deal with them. For demonstration purposes, we're using Ubuntu 22.04 LTS.

##  Install rar and unrar Commands on Linux

 To work with RAR files on Linux, you need two commands known as rar and unrar. Installing them is pretty straightforward. Simply follow your specific Linux distribution's installation command(s).

 To install these command-line utilities on Ubuntu and its derivatives, run:

sudo apt install rar unrar

![The Linux terminal displaying the installation of the rar and unrar commands on Linux](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/12/1-13.png) 

 For Debian-based distributions, use:

sudo apt-get install unrar-free

 If you're using an Arch Linux-based distro, then install them using:

sudo pacman -S rar unrar

 For all the RHEL-based distros, run:

sudo yum install epel-release && sudo yum install rar unrar

 To install rar and unrar on openSUSE, the command is:

sudo zypper install rar unrar

 If you'd rather [build the tools from source](https://facebook-videos.techidaily.com/new-in-2024-signal-id-video-overview-width-x-height-encoding-minutes/), you can download the TAR file from the [downloads page of the official website](https://www.rarlab.com/download.htm). Once you've installed rar and unrar, move on to creating RAR files and performing other actions on them.

##  How to Create RAR Files on Linux

 Creating a RAR file requires having one or more files or directories you want to archive. For testing purposes, we're creating some text files and adding a line to them. If you already have the files you want to archive, then you don't need to do this.

 Create the files with this command:

touch test1.txt test2.txt test3.txt test4.txt test5.txt

 Add text to them using the echo command:

echo "This is a text file" >> test1.txt

 Now we will add these files to our RAR archive using:

rar a test.rar test1.txt test2.txt test3.txt test4.txt test5.txt

 The "a" option is used for adding files or directories to the archive. Then you specify the name of the RAR file you want to create. Lastly, list all the files and directories you want to add to the archive.

 If you'd like to confirm if the RAR file was created, use [the ls command](https://extra-tips.techidaily.com/in-2024-capturecraft-hd-top-10-freepaid-filters-list/) to list the contents of the current directory.

![The Linux terminal showing the creation of a RAR file using several text files on Linux](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/12/2-7.png) 

##  How to Extract RAR Files on Linux

 The rar command lets you create an archive. To extract an existing RAR file, you use the unrar command. The syntax is pretty simple. Let's use unrar to extract files from the archive we created earlier. To do that, run:

unrar e test.rar

 The "e" flag tells the system to extract files to the current directory. Then, you input the RAR file name.

![The Linux display showcasing how to extract files from a RAR archive on Linux](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/12/3-7.png) 

###  How to Extract RAR Files to a Specific Directory

 What if you don't want to extract the files to the current directory and instead need them in a different directory? You can easily accomplish that by adding the directory path to the previous command, like this:

unrar e test.rar /home/zunaid/rar/extract

![The Linux terminal showing the process of extracting a RAR archive to a specific directory on Linux](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/12/4-5.png) 

 Remember that the directory where you want to extract the archive must already exist on your system. Otherwise, the command won't work.

###  Extract RAR Files and List the Directory Structure

 Suppose you have several directories in your archive. If you extract it using the normal method, you can only see the files that were extracted. However, the "x" option from the unrar command lets you see the directory structure as well. That is, you can see which file is inside which directory in the archive. Let's see that in action.

unrar x Files.rar

![The Linux terminal displaying the process of extracting files from a RAR archive with the directory structure on Linux](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/12/5-7.png) 

 As you can see, the output includes the directories in the RAR archive and the files each folder contains. So if you have directories in your RAR file, extracting archives using the "x" option can be more helpful.

##  How to List RAR Files on Linux

 So you download a RAR file and want to know its contents without extracting it. That's where listing the files can help you. By adding the "l" option to the unrar command, you can list all the files and directories in your RAR file. In our case, we'll run:

unrar l Files.rar

![The Linux terminal displaying the contents of a RAR archive file without extracting it on Linux](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/12/6-5.png) 

 What's more, you can see the file sizes, permissions, date and time of creation, and the total number of files.

##  How to Check the Integrity of RAR Files on Linux

 The unrar command lets you test the files in the archive for errors. If a file looks good, the command displays an "OK" status for that. To check the integrity of the files in an archive, use:

unrar t Files.rar

![The Linux terminal showing the integrity of all the files of a RAR archive on Linux](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/12/7-5.png) 

 In our case, all files are good to go.

##  How to Add Files to an Existing RAR File

 If you already have a RAR file, and you want to add more files to that, you can do that as well. The "u" option of the rar command is for that purpose. It updates your archive and lets you add new files. Use the command like this:

rar u test.rar test6.txt​​​​​

![The Linux terminal displaying the process of adding a new file to a RAR file on Linux](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/12/8-5.png) 

 You can confirm the success of the operation by listing the files in the archive.

##  How to Repair and Delete Files in a RAR File

 You've seen how to add new files to a RAR file. But how do you repair or delete them? For repairing or deleting, you have the "r" and "d" options, respectively. To repair a RAR file, run:

rar r test.rar

 The above command first creates a "fixed.test.rar" file. It then scans for data recovery records, reconstructs the RAR file, and finally creates a "rebuilt.test.rar" file in the current directory.

![The Linux terminal showing the process of fixing a RAR file on Linux](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/12/9-5.png) 

 Deleting files is simple. Simply specify the name of the files you want to delete from the archive. In our case, we want to delete "test6.txt" from the "test.rar" file. For that, we use:

rar d test.rar test6.txt

![The Linux terminal displaying the deletion of a single file from a RAR archive on Linux](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/12/10-5.png) 

 You can see if the file was deleted by listing the archive contents.

##  How to Split a RAR File Using rar

 Another cool thing you can do with your RAR files is to split them into several parts. You can also specify the size of each part. Say, we want to split an archive into several 1MB archives. For that, we run:

rar a -v1M Files.part.rar test1.txt test2.txt

 The "a" option adds new files to the archive. We specify the size of each archive with the "-v" option. The naming of the RAR file is important here. After creating the RAR archive, you'll notice that each file is named "Files.part.rar", "Files.part2.rar", "Files.part3.rar", and so on. Finally, add the file and directory names you'd like to include in the archive.

##  Protecting Your RAR File on Linux

 The last thing we'll cover is how you can make your RAR files more secure by adding a password or locking the file.

###  How to Password-Protect RAR Files

 To set a password for your RAR file, run:

rar a -p Files.rar

![The Linux terminal showing how to add a password on a RAR archive on Linux](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/12/11-3.png) 

 If you try to extract the RAR file now, it will ask you to enter a password.

###  How to Lock RAR Files

 Apart from using a password, you can also prevent someone from modifying the RAR file. Use the "k" option to lock the file:

rar k Files.rar

![The Linux terminal displaying how to lock a RAR archive on Linux](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/12/12-5.png) 

 Now, if you try to add or delete files from the archive, you'll receive an error.

---

 And that covers most operations you can do on RAR files on Linux. If you'd like to learn more, you can always refer to [the rar](https://manpages.ubuntu.com/manpages/focal/en/man1/rar.1.html) and [unrar command manual pages](https://manpages.ubuntu.com/manpages/jammy/man1/unrar-nonfree.1.html).

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
