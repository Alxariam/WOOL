# Wojo's Oblivion Overhaul List
- [Wojo's Oblivion Overhaul List](#wojo's-oblivion-overhaul-list)
- [Introduction](#introduction)
- [Installation](#installation)
  - [Prerequisites](#prerequisites)
  - [Using Wabbajack](#using-wabbajack)
  - [Post-Installation](#post-installation)
- [FAQ](#faq)

# Introduction
This modlist was built with the idea of showcasing the creativity of the Oblivion modding community, specifically with the quest mods. That goal has evolved as I worked on this modlist, but that desire has not changed. As it is now, this modlist changes a bit of everything. However, the focus is still primarily on adding plenty of content for the player to discover as they explore. 

# Installation

## Prerequisites
A **vanilla copy of Oblivion**, with all of the DLCs, **installed outside of C:\Program Files.** The guide has been tested so far with the Steam version, but GOG and retail versions should be supported. Ensure the Documents/MyGames/Oblivion folder has been wiped, then **launch the game once in vanilla** to generate a fresh INI. Backup any save games you with to keep. I recommend starting with a fresh install of Oblivion before installing this modlist.
Ensure that any MO2 installations on your system are configured in ‘portable’ mode.
**87 GB of hard drive space** (not including Oblivion), reduced to 58 GB if the MO2/downloads folder is deleted after installation. If you decide to delete the MO2/downloads folder after installation, just remember that it will mean downloading everything again upon any future updates to this modlist.

## Using Wabbajack
1. **Download** the latest version of Wabbajack from the [Wabbajack Github](https://github.com/wabbajack-tools/wabbajack/releases/), and **extract the Wabbajack.exe** file to a new directory called **Wabbajack**, as close to the root of your drive as possible (e.g. C:\Wabbajack).
2. **Create a new folder** for the new installation, and call it **WOOL** - again place it close to the root of your drive, but not within the Wabbajack folder (this can cause errors). Ensure you have at least 87 GB of hard drive space. (Deleting the downloads after installation will reduce the setup size to 58 GB).
3. **Launch Wabbajack.exe** from within the Wabbajack folder. Select **Browse Modlists**.
4. **Download Wojo's Oblivion Overhaul List** from the gallery.
5. Under Installation Location, select the **WOOL** folder you created in step 2. Set the Download Location to WOOL\downloads. Click **Begin**.
6. Wabbajack will open a browser and ask for Nexus authorisation. Log in if necessary and then hit **Authorise.** (_If you get an error on authorisation, download and install [.Net Framework 4.8](https://dotnet.microsoft.com/download/dotnet-framework/net48) and run the installer again_)
7. Wabbajack will now download and install the mods specified in the installer. The download size is approximately 29 GB so this may take a little while depending on your internet speed. The installer should keep you informed of progress.
8. After the **installation complete** message appears, close the installer.

You should have now successfully installed Wojo's Oblivion Overhaul List! However, there are still some things you need to do to get things running smoothly.

## Post-Installation

### Copy Game Folder Files
Inside the **WOOL** folder you created for this installation, you should see a folder named **Game Folder Files**. Open that folder and copy every file, then paste them into your **Oblivion** folder. If you purchased Oblivion through Steam, you can find this folder by right-clicking The Elder Scrolls IV: Oblivion in your Steam library, then clicking **Manage** > **Browse local files**.

### Change resolution
This step is needlessly complicated by the fact that Oblivion's launcher will completely ruin the configuration if it's launched. To change the resolution, you need to: 

Open the **INI Editor in MO2**. (jigsaw/puzzle piece icon on the top bar)

Under **[Display]** at the very top of the .ini, change **iSizeW** and **iSizeH** to match your resolution. For example, 1920x1080 resolution would be iSizeW=1920 and iSizeH=1080

### Apply 4 GB Patch Steam and Retail Users

**This step is only applicable if you have a Steam or retail copy of Oblivion. GOG users can skip this step.**

Within the Oblivion directory, launch **4gb patch.exe**.
Target both the **Oblivion.exe** and **OblivionLauncher.exe** executables in your root Oblivion directory. Both executables will now have been patched to improve the memory that can be allocated to their processes.

## Running the game
You should now be finished with setting everything up! To play, just select **Oblivion** in the MO2 **executable** **dropdown** and hit **Run.** If you encounter an application error and use Steam, make sure Steam is running in the background and try again. For you Skyrim players out there wondering why I'm not having you run it through OBSE, that's because it doesn't work like that for Oblivion, so quit asking about it.

## Frequently Asked Questions

-Q: Wabbajack isn't downloading certain files!

  -A: Certain types of URLs give Wabbajack issues sometimes. Just manually download the files from these links and place them in your WOOL/downloads folder, then run the installation through Wabbajack again.

A Brotherhood Renewed - https://tesalliance.org/forums/index.php?/files/file/422-a-brotherhood-renewed/

Integration-OCOpatch - https://drive.google.com/file/d/1gktYkwN5oMexTmrKC_mru-SIYzoQ5KTj

meshes_LOD_trees - https://drive.google.com/file/d/1E93rBXxorwjCzfYuqMSRrPE11Gw5agsO

Music_Sound_Video - https://drive.google.com/file/d/14ibm_WU0zVVmtPxmQwQCmW2QQ3Z3d_0P

Textures - https://drive.google.com/file/d/1mwC8-_lDReee79l6OP_Ff2Gx4lG-rnl1

Optimized Oblivion Assets - https://drive.google.com/file/d/1Pw55xFC-8Nr53Mb-zlRSi8tUgrb1JEeC


-Q: I'm getting an error message that says "Failed to initiliaze renderer. Desired render mode not found on Adapter."

  -A: Please reread the Post-Installation section above where it asks you to change your resolution.
  

-Q: Why is the framerate dropping sometimes? I have a really good computer!

  -A: It doesn't really matter how good your computer is. To keep things simple, Oblivion does not use your resources very well. I've done everything humanly possible to improve this, but it's never going to be perfect. 


-Q: OK fine, but is there anything I can change to get better performance?

  -A: Yes there is! You can disable exterior shadows in Oblivion Reloaded Lite for a very large FPS boost, but at the cost of no longer having the pretty exterior shadows. If this is something you would like to do, then simply go into the OblivionReloaded.ini file located in the mods\Oblivion Reloaded Lite\OBSE\Plugins folder, locate ExteriorShadows under the [Shaders] section, then change the value from 1 to 0 and save.
  

-Q: Will you ever add Better Cities to this list?

  -A: No. I love Better Cities, but the fact is that it makes the game run terribly due to all the stuff it adds. Even in a mostly vanilla modlist, Better Cities just does not run well... and this is definitely not a mostly vanilla modlist. If there's ever a future update that addresses this issue, then I will revisit it then.


-Q: Can I add (insert mod here) without breaking anything?

  -A: Probably not. Unless you really know what you're doing when it comes to modding Oblivion, it's super easy to break. You're welcome to try anyways, but I won't support any issues this causes.
  
  
-Q: Can I add an ENB to this list?

  -A: No. Due to conflicts with one of the settings in Oblivion Display Tweaks, it simply will not work with one. I've achieved comparable results with my Oblivion Reloaded Lite preset and have no plans (or need) to add an ENB.


-Q: Why are water surfaces stuttering?

  -A: Disable your shader cache in your video card settings.


-Q: It's telling me that OBSE isn't installed and crashing!

  -A: Read the instructions above better. You have to drag the game folder files into your Oblivion directory.


-Q: The NPCs act weird and the dialog is awkward.

  -A: That's part of Oblivion's charm!
