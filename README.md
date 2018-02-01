# bubblesconfig
Side project, attempting to make a simple, modular performance config for TF2, while retaining healthy looking graphics settings.
The purpose of this Github page is mostly to keep track of any changes.

Based on heavily editted versions of Mastercom's, Felik's, Chris', and Comanglia's configs.

Not meant for underpowered PCs.

Installation Instructions -

Right click on TF2 in your Steam library, head to Properties>Local Files> Browse Local Files.
Locate your "custom" folder, and delete any custom configs you may have previously installed.
Delete your "cfg" folder. NOTE: this will delete all your settings. Please back up any binds/scripts you may have set up.
Navigate to Properties>Local Files>Verify Integrity Of Game Files and wait for Steam to finish the process.
Place the "bubblesconfig" folder (This is the config) in your "custom" folder.
Navigate to Properties>General>Launch Options, remove any previously placed launch options, and paste in the following - 
"-novid -nojoy -nosteamcontroller -noff -w MONITORWIDTH -h MONITORHEIGHT -softparticlesdefaultoff -reuse -dxlevel 98"
- minus the quotations. Replace "MONITORWIDTH" / "MONITORHEIGHT" with your monitor's width/height dimensions. Example - if you 
have a 1080p monitor, replace width with 1920, and height with 1080.
Remove "dxlevel 98" after first launch.
And that's it, the config has been installed. Read "autoexec" file in bubblesconfig>cfg to enable/disable aspects of the config, and instructions on how to do so, with added info on other subjects.

Enjoy ^_^
