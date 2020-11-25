# cs:go, cs:s, tf2 & cod 4 config installation 
1. Download the CFGs and name it autoexec.cfg
2. Move the CFGs to the respective game's CFG folder

``\Steam\steamapps\common\Counter-Strike Global Offensive\csgo\cfg``

``\Steam\steamapps\common\Counter-Strike Source\cstrike\cfg``

``\Steam\steamapps\common\Team Fortress 2\tf\``

``\Steam\steamapps\common\Call of Duty 4\players\profiles\yourprofile``

3. (for tf2) Extract all the folders and replace files if prompted
4. Open the CFGs and change whatever you'd like

# launch options (cs:go and cs:s are included in their .cfgs)

tf2 ``-dxlevel 81 -window -noborder -w 1920 -h 1080 -console -novid +exec autoexec.cfg``

cs:s ``-novid -noborder -high -threads 8 -freq 75 +exec autoexec.cfg``

cs:go ``-noborder -high -novid -console -freq 75 -refresh 75 -nojoy -noforcemparms -noforcemaccel +exec autoexec.cfg``

open steam -> open library -> right click cs:go/cs:s/tf2 -> properties -> set launch options

• set freq/refresh to your monitor's hz which you can find in settings -> system -> display -> advanced display settings -> display adapter properties

• set threads to number of threads your cpu hsa which you can find in task manager -> performance -> cores x2 = threads (ex. 4 cores = 8 threads)

• novid removes valve intro

• noborder removes borders from windowed mode

# black ops 3 low graphics config installation
1. Download the CFG and name it config.ini
2. Replace the config.ini in the players folder
``\Steam\steamapps\common\Call of Duty Black Ops III\players``
3. Enjoy high framerates :p
