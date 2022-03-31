# Conky-Learn
#### This is a collection of files to help beginners use conky faster. The blog will be uploaded to linuxman.co soon. I will provide the link once it is published.
#
## Make directories and import default conky config
```
mkdir ~/.config/conky && cp /etc/conky/conky.conf ~/.config/conky/conkyrc
```
## Clone directory to the directory we made
```
git clone https://github.com/PyOfile/Conky-Learn.git && cd Conky-Learn && cp -r conky ~/.config
```
## Add to i3WM config
```
# Conky
exec --no-startup-id conky -d --config ~/.config/conky/config-nameplate
exec --no-startup-id conky -d --config ~/.config/conky/config-calender
exec --no-startup-id conky -d --config ~/.config/conky/config-network
exec --no-startup-id conky -d --config ~/.config/conky/config-system
```
#
![This is an, image of conky](i3-conky-conf.jpg "Conky")
