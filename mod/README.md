# Game-Mod-Quake4
IT266 with Prof DJ
Robert Diasio
March 2022
--------------
How To Install
--------------
Download the following folders and files from the Github from within the 'mod' folder
1. def FOLDER
	Contains - char_marine.def
			 - char_marine_medic.def
			 - char_marine_tech_armed.def
2. guis FOLDER
	Contains - hud.gui
			 - mainmenu.gui
3. strings FOLDER
	Contains - english_guis.lang
4. game0000.pk4
5. Quake4Config.cfg


not essential but recommend downloading as well

6. Quake4.exe - Shortcut
	Right Click
		Properties
			Put your file path for the game in the quotations. Everything after is for the mod
			"C:\Program Files (x86)\Steam\steamapps\common\Quake 4\Quake4.exe" +set fs_game mod +disconnect
7. README.md
	Always good to have a readme
-------------------------
What I did in Game Mod IS
-------------------------

Initially I was going to try and recreate TFT inside Quake but then realized I do not have that time.
I was able to achieve buying units, upgrading units, and placing units. Was not able to finish the AI to play against.

Things I finished:
Unit Placement 	    	 - Handled with I, O, P, K, L
Variety of 5 units  	 - Marines, Techs, Medics, Hyperblasters, Shotgunners
Resource Management 	 - Gold, you start with 10 and every full set of 3 rounds you get 5 gold
						 - 1 Gold is used to buy units
						 - 3 Gold is used to upgrade units
AI To PLay Against  	 - Not even close to done sorry chief
3 Levels of Unit Upgrade - Finished and able to be seen in the def files

Controls:
B:Start Game as well as switch phases
1:Upgrade Marines
2:Upgrade Techs
3:Upgrade Medics
4:Upgrade Hyperblasters
5:Upgrade Shotgunners
I:Buy Marines
O:Buy Techs
P:Buy Medics
K:Buy Hyperblasters
L:Buy Shotgunners
H:Open help menu
N:Undo the last unit placed
M:Switch between showing unit ammo and showing unit levels