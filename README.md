# Conky-Learn
#### This is a collection of files to help beginners use conky faster. The blog will be uploaded to linuxman.co soon. I will provide the link once it is published.
#
## Make directories and import default conky config as copy
```
mkdir ~/.config/conky && cp /etc/conky/conky.conf ~/.config/conky/conkyrc.copy
```
## Clone directory to the directory we made
```
git clone https://github.com/PyOfile/Conky-Learn.git && cd Conky-Learn && cp -r conky ~/.config
```
## Add to i3WM config
```
# Conky
exec_always --no-startup-id conky -d --config ~/.config/conky/config-nameplate.conf
exec_always --no-startup-id conky -d --config ~/.config/conky/config-calender.conf
exec_always --no-startup-id conky -d --config ~/.config/conky/config-network.conf
exec_always --no-startup-id conky -d --config ~/.config/conky/config-system.conf
```
#
![This is an, image of conky](i3-conky-conf.jpg "Conky")
