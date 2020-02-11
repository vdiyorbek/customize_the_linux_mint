# customize_the_linux_mint
Customize The Linux mint terminal
how to Customize the linux terminal?? 
We use lolcat and figlet.
first, we install lolcat and figlet.
#sudo apt-get install figlet lolcat

second, Download fonts of figlet.
#git clone https://github.com/vdiyorbek/figlet-fonts

third, Move fonts of figet to figlet, then delete downloaded fonts.
#mv figlet-fonts/* figlet && rm -rf figlet-fonts

gedit /etc/bash.bashrc
	figlet -f Bloody "Phoenix" |lolcat -a -d 50
  
 https://www.imageupload.net/upload-image/2020/02/11/Screenshot-at-2020-02-11-18-47-54.png
