# Conky-Breeze
Conky inspired by Gotham and configured for KDE. For some reason Conky is a bit more `interesting` on KDE. This will work.

I also changed the colors so it works with the Breeze Themes.

In the screenshots bellow you can see this displays the most demanding process, the RAM used, the CPU used, downloaded data and also the temperatures for the CPU and GPU.

# Dependencies
You will need conky(duh), sensors (for the temps), acpi (for the battery) and [Hack Nerd Font](https://github.com/ryanoasis/nerd-fonts/tree/master/patched-fonts/Hack).

```
sudo add-apt-repository ppa:teejee2008/ppa -y
sudo apt-get update
sudo apt-get install conky-manager -y

sudo apt-get install sensors -y
sudo apt-get install acpi -y
```

# Installation
```
cd ~/.conky/
git clone https://github.com/RaitaroH/Conky-Breeze.git
```
After this simply choose the themes in conky manager.

If you want, you can use the script I provide to change between dark and light. Simply put the script in your bin, bind it to some keyboard shortcut. Make sure you edit the location of the conky file itself and you are set.

# Screenshots
GothamDarkKDE better for dark wallpapers:
![alt-tag](https://raw.githubusercontent.com/RaitaroH/Conky-Breeze/master/GothamKDE/GothamDarkKDE.png)

GothamLightKDE better for white wallpapers:
![alt-tag](https://raw.githubusercontent.com/RaitaroH/Conky-Breeze/master/GothamKDE/GothamLightKDE.png)
