``` If someone is interested in playing with your gnome and by mistake you came accross a situation where you uninstalled your gnome by mistake, then no need to worry or to reinstall the ubuntu system. You might run a command like " sudo apt purge python3 " then your gnome gets uninstalled as it is written in python3 so it will get deleted. You can recover that. you don't have to reinstall that. ```
### gnome-recovery-commands

` sudo apt-get gnome-shell ubuntu-gnome-desktop `
### if above command doesn't work, try the below one. The above one may give an error like "unknown command gnome-shell". 
` sudo apt gnome shell ubuntu-gnome-desktop `

` sudo apt install gnome-session gdm3 `

` sudo apt install tasksel `

` sudo tasksel install ubuntu-desktop `

` sudo reboot `
