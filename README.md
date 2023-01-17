# Installing virtualbox and Debian linux on it

I began by going to https://www.virtualbox.org/wiki/Downloads and choosing "Windows hosts" then waiting for the file to install and running it

After running it I chose to install all dependencies and basically clicked yes until I was prompted with "install", I then proceeded. After the installation was complete I chose to Finish and launch the virtual box immediately.

After being done with that I navigated to https://terokarvinen.com/2021/install-debian-on-virtualbox/ where I found a direct download link for the linux version required for the course, the version was found from https://cdimage.debian.org/images/unofficial/non-free/images-including-firmware/current-live/amd64/iso-hybrid/debian-live-11.6.0-amd64-xfce+nonfree.iso 

After I had downloaded the iso file for the linux I opened the virtual box manager and clicked "new". I then clicked expert mode and chose the right name and ISO image (the one I had just downloaded) I then set the base memory and processors as 8gb and 4 cpus (these vary based on the computer) and set the hard disk memory as 60gb as dynamically allocated so it only uses as much memory as is required. I then moved on.

I then double clicked the vm I had installed and was prompted with a black screen for about 8 seconds, I was shown a desktop which included "install debian" that I double clicked. I made sure everything (mouse and keyboard) worked - they did. I chose american english as my language and set the correct timezone for Helsinki. I then chose the Finnish kebyoard layout and tested that it works. I chose to erase the disk and not encrypt it considering this is a vm on an already secured pc. I followed the instructions and chose the Master boot record considering it's required to actually boot.

I checked that everythinw as correct and pressed install. The installation took ~5 minutes after which I chose to restart, I then opened the vm and booted into linux successfully, which concluded the task. After I was done I wanted to still figure out how to change my resolution to make the screen bigger, I found it on settings>display>resolution.
