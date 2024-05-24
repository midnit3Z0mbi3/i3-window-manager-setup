# i3-Tiling-Window-Manager-Setup

 <img src="https://y.yarn.co/6ab88429-c1a0-493e-b404-640179ce6378_text.gif" alt="prometheus movie gif">
 


**Install:**

Install Debian or Kali Linux. Do not install a desktop environment.

update and upgrade

chmod +x *.sh

sudo bash i3_install_setup.sh

reboot

bash i3_customized.sh

Reload the configuration file and open lxapperance

sudo nano /etc/lightdm/lightdm-gtk-greeter.conf

reboot

 <img src="debian_i3_thunar.png" alt="debian i3 desktop displaying dracula color theme. terminal and thunar."> 


<img src="debian_i3_cava_thunar.png" alt="debian i3 desktop displaying dracula color theme. thunar and cava."> 



**Login Screen/Lightdm:**

edit the /etc/lightdm/lightdm-gtk-greeter.conf file to change the background of the login screen.

background= hex color code or path to image

userbackground= false (to use a solid color for the background)

userbackground= true (to use an image for the background)

font= monospace (you can place any font you want here)

If you would like the login page the same color as the desktop wallpaper, use hex code #1e1e2e

other neutral colors https://www.color-name.com/neutral-blue.color

sudo nano /etc/lightdm/lightdm-gtk-greeter.conf

reboot

**Wallpaper:**

edit i3 config options at the bottom of the configuration file

image - feh

solid color (hex code) - xsetroot

other neutral colors https://www.color-name.com/neutral-blue.color

wallpaper hd, 4k, 8k

https://pixlr.com

https://wall.alphacoders.com/

https://hdqwalls.com/

**Btop is installed. Btop is a terminal based resource monitor**

<img src="https://github.com/aristocratos/btop/blob/main/Img/normal.png" alt="gotop demo">


**Key Bindings:**

Web Browser mod+b

File Manager mod+Shift+Return  

Password Manager mod+p  

Lock screen mod+x 

