# Drivers for PS4 on Pop! OS 
Drivers for Pop OS running on PS4 (PlayStation 4). Drivers include the Mesa, Libdrm and Xorg drivers necessary to properly implement Vulkan on the PS4 and have Windows games running properly.

# Installing Drivers for Pop OS on PS4
1. Download the latest Release from the Releases section.
2. Extract.
3. Change directory into 64-bit and open a terminal there.
4. Run `sudo dpkg -i *`
5. If you run into errors, run `sudo apt-get --fix-broken install`.
6. Run `sudo dpkg -i *` It should be successful now.
7. Change directory into 32-bit and open a terminal there.
4. Run `sudo dpkg -i *`
5. If you run into errors, run `sudo apt-get --fix-broken install`.
6. Run `sudo dpkg -i *` 

If you need a more comprehensive and detailed tutorial, check [my blog article](https://ps4linux.com/make-ps4-linux-distro/#Step_4_Install_PS4_Linux_drivers_for_the_PS4_Linux_distro).
