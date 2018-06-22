* polybar folder, for its in ~/.config/polybar
Consist of config file which builds the bar, and launch.sh, which is called by i3 config file to kill previous existing polybars, and apply the current one.

To modify the polybar, edit the config file, save it, and check that it works runing the following command inside the polybar directory.
- $ polybar mybar

where mybar is the bar name that you have specified in the config file.
This command will try to draw your bar, and display useful warnings and errors.

