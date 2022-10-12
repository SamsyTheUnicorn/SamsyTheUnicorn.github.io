# Poser Hotkeys
Grab "Poser Hotkeys Plus SSE" from [here](https://www.nexusmods.com/skyrimspecialedition/mods/17743?tab=files), and install via MO2 as a FOMOD. Choose the following: Next, "English", Next, "Mfg Fix", Next, "Face Presets", Install.

Download the poser packs of your choice, I would recommend the following: Arsenic Pose SE ([LL](https://www.loverslab.com/files/file/4973-arsenic-pose-se/)), Yuih Poser SE ([LL](https://www.loverslab.com/files/file/3922-yuih-poser-se/)), and Collygon's Poser SSE ([LL](https://www.loverslab.com/files/file/16435-collygons-poser-sse/)). Install the packs as regular mods in MO2, and once installed, double-click each mod, go to the "Optional ESPs" tab, and hide any plugins contained in the poser packs. You should only have Poser Hotkeys.esp enabled.

Grab "PoserDataGen" from [here](https://www.nexusmods.com/skyrim/mods/72623?tab=files), and extract the application anywhere on your computer. In MO2, open the Modify Executables window and add a new executable from file, choosing PoserDataGen.exe from the location you extracted the application. <br>
![](https://github.com/SamsyTheUnicorn/SamsyTheUnicorn.github.io/blob/main/poserEdit.png?raw=true) <br>
Once you have PoserDataGen as an application in MO2, launch it and you will likely see red text where the app says "Skyrim Directory", change the directory to the "Stock Game" folder where you installed Arisen. Now clear the selections for Posers, and enable the poser packs you added, if you chose the same as me those will be ArsenicPose1, CollyPoser, and YuiHPose. Then hit Generate Pose Data.

For extra faces (and generally better ones), grab "Additional Expressions Project" from [here](https://www.nexusmods.com/skyrimspecialedition/mods/72337?tab=files) and install normally in MO2, this will net you around 100 new expressions to use from the Faces portion of PH+. <br>
You should now have some files in your Overwrite under SKSE\Plugins\Poserhotkeys, create a new mod titled "PoserDataGen Output" and enable this after your Poser Packs. All you have to do next is update the Nemesis engine and run it to generate anims. 

As with anything adding adding animations, make sure your Nemesis animation count does not exceed 20,000. Preferably, keep your animations below 15,000.
