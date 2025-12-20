# SunarMC
## Development progress: in progress
### The changelogs might have not recorded all changes but most.
<img width="1920" height="1080" alt="Screenshot_20251211_224902" src="https://github.com/user-attachments/assets/f404fb8d-6f1f-4037-b71d-58a77d0eb27e" />
total recorded changelogs:
adds Mojang API skins but falling back to a different faster API
-weather changer <br>
-scrollable chat <br>
-option for unlimited chat history <br>
-EXPORTING CHAT <br>
-custom setting for chat history <br>
-Server list fix from button suddenly taking you to the menu <br>
-fixed the leave bed button not working <br>
-fixed the sending a message while in a bed crash <br>
-NEW DEBUG MENU LAGOMETER VISUALS <br>
-Added multiplayer mob jitter fix <br>
-more info to the f3 debug menu <br>
-removed the LAGGY lagometer from vanilla <br>
-Fixed music slider not updating live <br>
*-fixed weather changer  <br>
Attachment file type: unknown <br>
*-Fixed pressing escape now resets chat scroll <br>
-Chunk borders <br>
-multi-key binds saving and loading. <br>
-F3 MENU UPDATE <br>
-Another QOL f3 menu update to change facing direction from 0 1 2 3 into North (-Z) etc <br>
-Does not download the assets.zip when not needed, MASSIVELY speeds up the game. <br>
-sha256-checksum checking so even if my hosted version of the assets.zip gets hacked or malicously changed the clients will NOT apply it. <br>
-showcase of the new f3 menu I have modified with the new compass addition. <br>
-Rewrote the keybinding system to support multi-key keybinding <br>
-added chunk borders (slightly scuffed but usable.) <br>
-Changed the control gui to be a double click and have  sub gui where you can optionally type they keybind you wish to set. <br>
-Changed every textbox in the game to be of convenience. Allowing select, edit, different text cursor, copy and paste. <br>
-removed random square in the f3 menu <br>
-ADDED VSYNC <br>
-taking a screenshot and clicking it now opens it <br>
-added proper 1.10-like chunk borders (had to code from scratch) <br>
-F3 debug cursor <br>
-fist inertia (interpolated) Also this applies for items as well. <br>
-fist is no longer affected by the FOV slider. (by rendering in screen space.) <br>
-fixed the fist inertia to apply while swinging and items STILL being affected by FOV slider <br>
-3D cursor does not show in third person since it is not usefull in 3rd person <br>
-3D dropped items <br>
-visually stacked and collected items <br>
-fist lerping/interpolation is toggleable <br>
-music gui has a new open music folder for ease of access <br>
-texturepacks button is moved into <br>
CONVENIENCE FEATURE ALERT!!!! ⚠️  You can now hold SPACE ON LADDERS!!! 👏 <br>
-crosshair no longer appears in non first person camera since there is no point. <br>
-ACTUALLY fixed the lerping STILL applying WHILE DISABLED. for the fist and items. <br>
-2nd layer while sneaking not moving has been patched <br>

-coming with a NEW UI design, dynamic also interacts with the mouse, <br>
-confirm to quit <br>
-f3 debug menu save state option <br>
-etc!!!! <br>

-Actually fixed the version number for fix 1 <br>

-light dark theme toggle <br>
-custom cursor since some people report broken cursor on screenshare or etc <br>
-option to disable the V2 ui <br>
-skin fetching slightly faster. (tried my best to async it.) <br>
-toggleable custom mouse cursor and slider for size <br>

-improved keybind support and fixed chunkborders initializing as null <br>

-fixed armor rendering <br>

-AGAIN fixed the keybinding system. <br>

-Fixed the 3D cursor X and Z being inverted. <br>

-AFTER 18 LOCAL PATCHES Finally the first Release 2 Fix 7 Best Effort Red Blue Inversion patch <br>
-Class rewrites for macos having R and B swaps 😭 <br>

-main menu flicker fix for the old gui users, <br>
-V2 ui works in the world loading ui but also toggles with the same option to disable/enable V2 ui <br>
-Mining fix and placement fix only for white listed servers. <br>
--this list is public at: https://github.com/MikaSukie/b1.7.3-Assets/blob/main/fixblacklist.txt <br>
--the same repo that supplies the assets for the client. <br>
-fixed the holding left click delay timer that was SO ANNOYING (this.leftClickCounter = 10; now being this.leftClickCounter = 0;) <br>
-new splash screen complete with making the loading screen WAIT for resource downloads to prevent crashes that should have not been happening at all.  <br>

-Modern crafting using right click dragging <br>
-improved the loading screen preventing GL state overflowing <br>

-ACUTALLY implemented a working fix and feature for hotbar swapping number number. <br>
-Chat logging on/off seting and open chat exports folder <br>
-Reorganized the sunarmc gui settings. <br>
-ALSO HOLY!!!! 2ND LAYER SKINS WORK!!!!  <br>
-ALSO NEW FEATURE! I MANUALLY added the minimap 😭 it works!!!! <br>
-Chat visual settings for configuring chat opacity, width, and the typing box opacity <br>

forgot "GL11.glDepthMask(true);" so now rendering should be fixed. <br>
fixed the minimap textboxes not being clickable 😅  <br>
and NEW FIST FOV SLIDER! <br>

Minor bug fixes so version number not incremented but fixID has been changed. <br>
Rewrote the entire model renderer class and etc for the player since there was a bug where skeletons and zombies had the same model as the player 💀  <br>
also some ui redesign and changes <br>
-tried to remove herobrine but bro duplicated and become 45 <br>

fixed slider formatting <br>
also added fps counter, AAAND proper minimap memory protections <br>
default will show on default slider values <br>

-Added Discord RPC <br>
-Massive Backend changes including a new instance system for the client. <br>
--basically a lot of the structure, client code has been rewritten and organized. <br>
-this will ship as a minor update even though its the biggest update. <br>
