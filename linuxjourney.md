# My Linux Journey
<p align="justify">
	I have been considering to switch to Linux for a long time. I hesitated because I had never installed an operating system before. I thought it was very difficult and time consuming job to do. However the annoucement of the end of support for windows 10 gave me the push I needed. I decided it was finally a time to move on to Linux. This all happened around the time I was considering of buying a new laptop because my old one was already eight years old. It worked just fine but it was just a matter of time for the battery to give out. For that very reason I bought myself a new laptop. It had a Windows 11 installed on it by default. I did not want anything to do with it. It was time to install Linux on it.
</p>

## Table of Contents
- <a href="#from-windows-to-linux">From Windows to Linux</a>
    - <a href="#choosing-the-distribution">Choosing the distribution</a>
    - <a href="#checking-the-integrity">Checking the integrity</a>
    - <a href="#flashing-the-iso">Flashing the ISO</a>
- <a href="#linux-mint">Linux Mint</a>
- <a>Manjaro</a>
    - <a>Problems with getting Latex to work</a>
    - <a>Problems with the journald stuck on activating state</a>
    - <a>Problems with getting Vulkan + Nvidia to work</a>

## From Windows to Linux
### Choosing the distribution
<p align="justify">
	Choosing the distribution was a little bit harder than I imagined. There are so many options to choose from and all the guides recommend completely different distributions for pretty much the same reasons. I obviously wanted something stable and somewhat easy to use. A few distributions I considered were Debian, Fedora, Manjaro and also Linux Mint. Stability was my reason to steer away from Manjaro. Another critical point of my decision was that there were a couple of applications I needed to get working, such as VSCode and IntelliJ. I found out that most of the software, that work on Linux, are available for Debian and so for Linux Mint as well. That dropped Fedora of my list of candidates. That leaves just Debian and Linux Mint left in the battle. I did some research on the internet on which distribution I should choose. Many people seemed to recommend Linux Mint for new users. I also found some evidence that Debian is supposedly quite difficult to install. After giving it a long thought I decided to go with Linux Mint.
</p>

### Checking the integrity
<p align="justify">
    I now have downloaded the Linux Mint ISO. There are still a lot of steps to take before I can actually install it on my machine. I learned that first thing I should do is to check the checksum of the ISO to see if it matches with the official checksum. I had no idea how does one do that. Luckily there was a great guide on the Linux Mint forums how to do that on Windows. I later came to realise that most of the distributions mainly have instructions for doing that on Linux. Another thing I needed to do was to check the integrity of the ISO which meant I needed to download the GPG program and the Linux Mint keyrings. The same guide helped me to do that and everything was fine so far. Next step is to flash the ISO to an USB stick.
</p>

### Flashing the ISO
<p align="justify">
    I had a look on how big should the USB be for flashing the ISO. I found that many recommended at least 8GB. I did not have any of those so I went to the local store to purchase two 16GB USB sticks. I then downloaded the Balena Etcher software in order to flash the ISO to the USB stick. However I could not get the Balena Etcher to work. I found that I needed to run the program with administrator privledges for it to work. After doing that I managed to flash the ISO to the USB. Now it was time to install my first ever Linux on a physical machine.
</p>

## Linux Mint
![LinuxMint](https://img.shields.io/badge/Linux_Mint-87CF3E?style=flat&logo=linux-mint&logoColor=white)

<p align="justify">
	I decided to go with the Cinnamon desktop. Linux Mint installer was exremely simple to use and the install succeeded without any issues. I absolutely love the look of the Cinnamon desktop. It look quite similar to the desktop on Windows 10 of which I am very familiar with. However Cinnamon has so much more customization options. There is also a graphical software manager on Linux Mint to make integrating very easy. There are quite a lot of applications available in single click of a button. All of the applications, I have installed so far from the software manager, have worked out of the box. However it naturally does come with drawbacks, that is that the versions of the applications can be quite old.
</p>

<p align="justify">
	Linux Mint is also a lot lighter in case of resources than Windows 10. Another thing I like very much is the updating. I always hated when Windows started updating suddenly without any warning when I was doing something else. That completely killed the performance of the computer for a hour in the worst case. There is nothing like that on Linux Mint, all the updates must be manually installed with admin priviledges. Also on Linux Mint the update manager explicitly tells you which packages are going to update. All in all Linux Mint is a very good distribution from someone coming from a Windows background. The installation process is very simple and there are good instructions for doing so. Linux Mint also has a big community, so solutions to most of the problems can be found on the internet straight away.
</p>

## Manjaro
![Manjaro](https://img.shields.io/badge/Manjaro-35BF5C?style=flat&logo=Manjaro&logoColor=white)

<p align="justify">
    My time has come to try out a distribution from the Arch family, Manjaro to be specific. I know I am not ready for Arch just yet so Manjaro seems like a good compromise. Basically at a first glance it seems that Manjaro has all the goodies from Arch and easiness from something like Linux Mint. But is that actually the case? That's what I want to find out because it sounds a little bit too good to be true.
</p>

<p align="justify">
    Manjaro is available with a few different desktop environments. I decided to go with KDE because I like the look of it very much. The installation process was extremely simple and it succeeded on the first try on my PC. However when I installed Manjaro on my laptop installation did not go smoothly at all. The actual install succeeded but when the system started to update, update process got stuck for hours. There was really nothing else to do than to force shutdown the laptop. When I tried to open the laptop again I got a message that there was no bootloader. I had a little look on the internet what was going on and found that the boot loader is deleted when the update process starts and is installed back after the update finishes. I obviously did not know this before hand and that meant I had to do the whole install process again. Luckily it succeeded on the second try without any difficulties. 
</p>

<p align="justify">
    Okay, now that Manjaro is installed successfully is it actually something I want to use? Manjaro is Arch based so it has access to very up-to-date software and there are a ton of them. Also what I personally like very much is that Manjaro has a graphical software manager. There are naturally drawbacks as well to the latest available software. All the software will simply not work out of the box. Luckily for me pretty much all the software I absolutely needed worked without much of a hassle. 
</p>

<p align="justify">
	Something I noticed while searching few little problems on Manjaro was that the community seems quite toxic. I found many threads were the only advice for a problem was "skill issue" or "go back to windows". Many of these cases where perfectly good questions in my opinion at least. Of course not all people all like that. There were a lot of incredibly helpful people as well using a lot their time to solve the problem for the asker. Even if there is no similar topic on the Manjaro forum, there most likely will be something on the Arch forum. I would say getting help is not going to be an issue since there are many very talented people using something from the Arch family.
</p>

### Problems with getting Latex to work
> [!ERROR]
> Did not find a working fix.

**Backstory**
<p align="justify">
    ...
</p>

**Issue**
<p align="justify">
	I could not get latex to work properly on manjaro. This is of course a quite a small problem and mostly due my limited knowledge. However by googling I found a lot of people having the exact same problem with manjaro/arch. I ran into a few solutions as well saying like "I installed these 30 different packages and it started to work". It might have worked for me as well but I did not need to get latex working that badly to install some random packages. Comparing to linux mint latex worked out of the box, just needed to install it.
</p>

**Aftermath**
<p align="justify">
    ...
</p>

### Problems with the journald stuck on activating state
> [!WARNING]
> Found a temporary fix.

**Backstory**
<p align="justify">
    I decided to install linux to my old windows 10 laptop as well. I tried Debian, tried Fedora tried Mint, nothing worked. After the linux mint install failed my laptop would not boot anymore from usb. Tried changes basically all the bios settings (secure boot, fast boot, csm, etc.) I simply could not get the laptop to boot anymore. So I completely dismantled it and put it back together to reset the bios. Miraculously I managed to get the laptop to boot and installed manjaro on it. However I noticed that the laptop would freeze everytime after a while. I had a look on the system monitor but saw nothing alarming execpt that the cpu was running around 50%. After it froze again I decided to shutdown the laptop right after it started. It did not work I got an error message saying something like journald could not be started. I had a look on the htop and found that journald had 100% cpu usage. I wondered what the **** is going on. I had a look on the internet and found a command to check the status of the journald. The status was activating.
</p>

**Issue**
<p align="justify">
    The journald got stuck on activating state and was using burning my cpu which caused freezes after awhile every single time. Also the system was unable to reboot or shutdown, only the power button worked for shutdown. Surprisingly it always booted right up but the same problem occured everytime. After doing some research I managed to find a temporary fix, which was to set "pci=nomsi" on the grub boot loader. I could not however get the grub to update so need to set the "pci=nomsi" on every boot.
</p>

**Aftermath**
<p align="justify">
    I am happy with the solution even though it is a little tedious to do everytime. However the laptop is usable (other distributions I have tried still do not work at all). A huge thank you to Manjaro for giving life back to my old laptop. Though I do have a feeling that Arch could work even better but that is something for the future.
</p>

### Problems with getting Vulkan + Nvidia to work
> [!ERROR]
> Did not find a working fix.

**Backstory**
<p align="justify">
    ...
</p>

**Issue**
<p align="justify">
	...
</p>

**Aftermath**
<p align="justify">
    ...
</p>