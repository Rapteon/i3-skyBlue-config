# i3-skyBlue-config

![Image1](/screenshots/1.png)
![Image2](/screenshots/2.png)
![Image3](/screenshots/3.png)

## Recommendations:
	You may change the keyboard shortcuts to suit your needs.
	I have provided configuration files for both (dmenu and roxi) && (i3status and i3blocks).
	*You only need one from each, i.e one of dmenu/roxi and one of i3status/i3blocks*

### These are the dependencies for the best experience:

	*	dmenu  
	*	i3status
	*	rofi
	*	i3blocks
	*	Font-Awesome font ==> <a href="https://github.com/FortAwesome/Font-Awesome">here</a>
	*	feh (to set wallpaper)
	*	Arc-Dark-Theme ==> <a href="https://github.com/horst3180/Arc-theme">here</a>
	*	Moka Icons ==> <a href="https://snwh.org/moka">here</a>
	*	Firefox Theme ==> <a href="https://github.com/elibroftw/matte-black-theme">here</a>
	*	Chrome Theme ==> Search "Material Theme Dark [blue-grey]"
	*	picom(a fork of compton)
	*	Some useful tips included. Take a look in case you are using ArchLinux.

## Installation(on ArchLinux)

`pacman -S dmenu`

`pacman -S i3status`

`pacman -S rofi`

`pacman -S i3blocks`

`pacman -S feh`

`pacman -S picom`
	
+	Create a folder named ".config" in your home directory.
+	Inside this folder, create 4 sub-directories- "i3", "i3status", "i3blocks", "rofi".
+	Inside each of these directories, create a file named "config" using a text editor of your choice.
+	Create a ".fonts" folder in your home directory. Download the following fonts:

	+	<a href="https://fontawesome.com/how-to-use/on-the-web/setup/hosting-font-awesome-yourself">FontAwesome</a>
	+	FreeFont .otf and .ttf files <a href="https://ftp.gnu.org/gnu/freefont/">from here</a> in case they aren't available
	
+	Unzip the downloaded file.
+	Copy the contents of each of the "config" files from the respective directories into the above created ones.
+	Example: Copy the file .config/i3/config to $YOUR_HOME/.config/i3/config
	
Wallpaper Credit: Photo by Kumiko SHIMIZU on Unsplash
