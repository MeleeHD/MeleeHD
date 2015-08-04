88b           d88              88                              88        88  88888888ba,    
888b         d888              88                              88        88  88      `"8b   
88`8b       d8'88              88                              88        88  88        `8b  
88 `8b     d8' 88   ,adPPYba,  88   ,adPPYba,   ,adPPYba,      88aaaaaaaa88  88         88  
88  `8b   d8'  88  a8P_____88  88  a8P_____88  a8P_____88      88""""""""88  88         88  
88   `8b d8'   88  8PP"""""""  88  8PP"""""""  8PP"""""""      88        88  88         8P  
88    `888'    88  "8b,   ,aa  88  "8b,   ,aa  "8b,   ,aa      88        88  88      .a8P   
88     `8'     88   `"Ybbd8"'  88   `"Ybbd8"'   `"Ybbd8"'      88        88  88888888Y"'    



             o      o o  .oPYo.                               o              
             8      8 8  8    8                                              
             8      8 8 o8YooP'   o    o .oPYo. oPYo. .oPYo. o8 .oPYo. odYo. 
             8  db  8 8  8        Y.  .P 8oooo8 8  `' Yb..    8 8    8 8' `8 
             `b.PY.d' 8  8        `b..d' 8.     8       'Yb.  8 8    8 8   8 
              `8  8'  8  8         `YP'  `Yooo' 8     `YooP'  8 `YooP' 8   8 











 ___       __ _                          ___      _    _     
/ __| ___ / _| |___ __ ____ _ _ _ ___   / __|_  _(_)__| |___ 
\__ \/ _ \  _|  _\ V  V / _` | '_/ -_) | (_ | || | / _` / -_)
|___/\___/_|  \__|\_/\_/\__,_|_| \___|  \___|\_,_|_\__,_\___|

	Dolphin

		Version:             4.0-5811
		Link (General):      https://dolphin-emu.org/download/dev/2e7a832c4da75474ce6d23f278fc43db66c9e3c9/
		Link (Win x64):      http://dl.dolphin-emu.org/builds/dolphin-master-4.0-5811-x64.7z
		Link (Mac OS X):     http://dl.dolphin-emu.org/builds/dolphin-master-4.0-5811.dmg
		Link (Ubuntu 13.04): http://dl.dolphin-emu.org/builds/dolphin-master-4.0-5809_amd64.deb
		Notes:               The textures are untested on later versions of Dolphin but may still work
                                     They may break pre-4.0-5234, which introduced a new custom texture format

	Super Smash Bros. Melee (SSBM)

		Game ID:  GALE01
		Maker ID: 0x01
		Revision: 2
		Notes:    The textures are untested on other versions of SSBM but may still work
                          To find the game ID, maker ID, and revision number, follow these steps:
				Launch the Dolphin emulator
				Click on "File"
				Click on "Browse for ISOs"
				Navigate to the directory in which SSBM is stored
				Press "Select Folder" to index the games in that folder as items in the list view
				Right-click on SSBM
				Click on "Properties"
				Click on the "Info" tab
				Check the fields for "Game ID," "Maker ID," and "Revision"




 _   _                ___      _    _     
| | | |___ ___ _ _   / __|_  _(_)__| |___ 
| |_| (_-</ -_) '_| | (_ | || | / _` / -_)
 \___//__/\___|_|    \___|\_,_|_\__,_\___|

	If you have not done so, download the textures from https://github.com/MeleeHD/MeleeHD/archive/master.zip
	Obtain Dolphin 4.0-5811 or an otherwise compatible version of the Dolphin emulator
	Unzip MeleeHD-master.zip to any location
	Enter the "MeleeHD-master" folder
	Right-click the "GALE01" folder
	Click "Cut"
	Navigate to the folder in which the Dolphin emulator exists
	Enter the "Load" folder
	Enter the "Textures" folder
	Right-click the blank space
	Click "Paste" to place the "GALE01" folder inside the "Load\Textures" directory
	Launch the Dolphin emulator
	Click on "Options"
	Click on "Graphics Settings"
	Click on the "Enhancements" tab
	Change "Internal Resolution" from "1x Native" to "Auto (Window Size)"
	Click on the "Advanced" tab
	Under the "Utility" group, check the "Load Custom Textures" box
	Click the "Close" button
	Configure other settings, like controls and other enhancements, to your preferences
	Double-click SSBM to run the game
	Either drag a window corner to increase the windowed resolution or press Alt + Enter to go full screen
        Proceed through any in-game message boxes
        If Melee HD is active, an indicator in the top left corner should change from "SD" to "HD"




 ___              _                      ___      _    _     
|   \ _____ _____| |___ _ __  ___ _ _   / __|_  _(_)__| |___ 
| |) / -_) V / -_) / _ \ '_ \/ -_) '_| | (_ | || | / _` / -_)
|___/\___|\_/\___|_\___/ .__/\___|_|    \___|\_,_|_\__,_\___|
                       |_|       
        Register to the forum
        
                The Melee HD forum will function as a communication point for texture work
                This forum can be found at the URL http://meleehd.boards.net

	Dumping textures

		Launch the Dolphin emulator
		Launch SSBM
		Proceed to the part of SSBM prior to where the textures to dump exist in the game
		Click on "Options"
		Click on "Graphics Settings"
		Click on the "Advanced" tab
		Under the "Utility" group, check the "Dump Textures" box
		Click the "Close" button
		Execute the action in the game that makes the textures appear on the screen
		Navigate to the folder in which the Dolphin emulator exists
		Enter the "Dump" folder
		Enter the "Textures" folder
		Enter the "GALE01" folder
		The dumped textures should appear in this folder
		Some programs on Smashboards may be able to extract textures from ROM instead of from RAM

	Remaking textures: specifications

                You should first make sure you are not working on a texture on which someone else is working
                You can make sure of this by checking http://meleehd.boards.net/thread/2/on-textures-working
                If your texture is unclaimed, it is most organized for everyone for you to claim it there
		Remade textures should be 16 times longer on each axis and enumerate at 256 times the pixels
		They should be placed in folders where the folder names describe the purpose of the textures
		These folders should be subfolders in a logical hierarchy to be determined by the developers
		In each folder for each texture should be both the remade texture and the original texture
		The remade texture should be given the name of the original texture as specified in the dump
		The original texture should retain its name but have the prefix "sd_"
		If an original texture has transparency the remade texture should have similar transparency
		Remade textures should be saved in PNG format
		Where possible their size should be optimized with FileOptimizer, which can be found below:
			http://nikkhokkho.sourceforge.net/static.php?page=FileOptimizer
		If the texture is first remade as SVG, consider also uploading the SVG to the texture folder
                Retextures should be faithful in design to the originals; artistic liberties should be few
		If you document notes on a texture series, consider dropping a readme in the series folder
		If these conventions cause confusion, cross-reference them with the files in MeleeHD-master

	Remaking textures: how-to

		Complex graphics:

			Raster editors like Photoshop (for pay), GIMP, Paint.NET, or Pixlr (for free)
			3D design programs like 3ds Max (for pay) or Blender (for free)

		Simple graphics:

			Vector editors like Illustrator (for pay) or Inkscape (for free)
			The comments below will go over starting points for Inkscape
			The Bezier curve tool (Shift + F6) and the Node tool (F2) are most important
			You can find tutorial videos for these tools both on YouTube and elsewhere
			To save the image, click on "File," then "Export PNG Image," then "Page"
			Make sure the width and height are 16 times those of the original texture
			Specify the file path to which to save the file and then click "Export"
		
		Typography:

			Do not start reproducing a font unless you know its typeface
			A typeface that is sufficiently indistinguishable (about 99% similar) may do
			If you do not know the typeface, put the subject to discussion
			If discussion bears no fruit, reproduce each character in a vector program
			If you also upload the original SVG, first convert the characters to a path

		Texture previewing:

			Move retextures into "Load\Textures\GALE01" as specified in the User Guide
			Follow the User Guide to load the remade textures into SSBM
			Go to the in-game location in which the new textures should appear
			Click on "Options"
			Click on "Graphics Settings"
			Click on the "Advanced" tab
			Under the "Utility" group, repeatedly toggle the "Load Custom Textures" box
			Preview the difference between the original and the retexture
			Note down mistakes in features like the geometry and positioning of the retexture
			If the game goes by too fast you may need more preview time
			To obtain this time, go to "Options" then "Configure" and lower the framelimit
			You may also wish to save and load states to skip gameplay and navigation
			Repeat the preview-toggle-fix cycle until the texture best maps to the original
			This process is best done when the game is rendered at a high resolution
			Please complete this process before submitting retextures to the repository
