# 2006 Toshiba Sattelite A100-709 Retro Web Revival Machine.

Hi and Welcome To My Repo!

Considering You're Seeing This You Probably Also Want To Repurpose A Really Old Laptop/Computer Into A Retro-Themed 1990s/2000s Web Revival Machine, and If So, This Is the Correct Guide For you!

I will Be Documenting The Entire Process Along The Way. 

## Specs

Intel Core(R) Core 2 Duo T2500 @2.0 Ghz 

1038976KB or Roughly 1GB (1,014.625 MB) DDR2 and a 500GB HDD.

Haiku R1beta6 (x86_gcc2h)

## Main Goals:
*PS: I Might add or remove goals along the process. However until I have the machine described, I will live update this repo and readme.
I also might upgrade to an SSD, add RAM, upgrade CPU, a new higher-capacity battery, and a better screen. There is no Limit to how much I mod this*


Make A Fully Function Retro Late 1990s/Early 2000s Themed Machine With HaikuOS 


Install a Suitable Browser To Be Used For Web Browsing Creative & Cool Web Revival Personal Websites, Homepages, and Chat Rooms.


Setup a Smooth Media Playing Experience For Watching Movies&Tv From My Old DVD Collection


Setup and Configure a Lightweight IDE For a Smooth and Lightweight Programming Experience. 

## Why HaikuOS?
Haiku OS is the perfect fit for this project because it combines a fast, lightweight retro aesthetic with modern capabilities, allowing our vintage computer to smoothly browse web revival sites, play DVDs, and run efficient programming tools.


For further info, see [haiku-os.org.about](https://www.haiku-os.org/about/) for an overview of haikuOS and [haiku-os.org/about/faq/](https://www.haiku-os.org/about/faq/) for frequently asked questions.


## OS Install Guide:
Go to the [download page](https://www.haiku-os.org/get-haiku/r1beta6/) on your main computer and scroll down to the torrent section.


If you're computer is low speced and very old like mine, download the haiku-r1beta6-x86_gcc2h.torrent. Otherwise, if you're sure your computer supports 64bit operating systems well, download haiku-r1beta6-x86_64.torrent.


If you haven't already, download qbittorrent to download the ISO. Don't forget to seed afterwards.


Now that the download is complete and you seeded it, you can flash the iso onto your USB flash drive through something like Balena Etcher or the terminal if you're on linux:

    sudo dd if=./haiku-r1beta6-x86_gcc2h-anyboot.iso of=/dev/sda bs=4M conv=fsync status=progress

When you're done flashing, simply plug in the flash drive into the computer you want to renew, enter the boot selection menu, and select the flash drive.


Next, select your preferred language of choice, and after you can try it out through the live system or just directly download it on your hard drive by following this simple [guide](https://www.haiku-os.org/get-haiku/installation-guide/)


*Note: installing haikuOS on your hard drive/SSD will delete everything you had on it so make sure all your important data is backed up*


If you chose to test the live system and you're looking to install it on your hard drive, simply click the top right blue feather icon, go to "Applications", and open "Installer". 


Simply follow the [haiku install guide](https://www.haiku-os.org/get-haiku/installation-guide/).


## Post Install Guide:
