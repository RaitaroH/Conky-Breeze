# Conky-Breeze
Conky inspired by Gotham and configured for KDE. For some reason Conky is a bit more `interesting` on KDE. This will work.

I also changed the colors so it works with the Breeze Themes.

In the screenshots bellow you can see this displays the most demanding process, the RAM used, the CPU used, downloaded data and also the temperatures for the CPU and GPU.

# Installation
```
git clone https://github.com/RaitaroH/Conky-Breeze.git ~/.conky/
```
After this simply choose the themes in conky manager.

```
sudo add-apt-repository ppa:teejee2008/ppa -y
sudo apt-get update
sudo apt-get install conky-manager -y
```
Also you will need to add sensors, for the temperateures to be showned.
```
sudo apt-get install sensors -y
```

# Screenshots
GothamDarkKDE better for dark wallpapers:
![alt-tag](https://raw.githubusercontent.com/RaitaroH/Conky-Breeze/master/GothamKDE/GothamDarkKDE.png)

GothamLightKDE better for white wallpapers:
![alt-tag](https://raw.githubusercontent.com/RaitaroH/Conky-Breeze/master/GothamKDE/GothamLightKDE.png)
