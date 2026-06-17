# Make NV "4GB-Aware"
This allows the game to consume over 4GB memory (a good thing)
- https://www.nexusmods.com/newvegas/mods/625524
- Extract the exe
- Put the exe in the FalloutNV folder (`...\SteamLibrary\steamapps\common\Fallout New Vegas`)
- Run the patcher exe
  

# Get NV Running Smoothly
- Download and install Wabbajack
  - https://www.wabbajack.org/
- Begin installation of Viva New Vegas modpack. It will require clicking a "download" like button over and over. Use the script below to automate clicking
  - Install Autohotkey and run this script. Take a screenshot of the "slow download" button and change "ImagePath" to the path of that screenshot.
```ahk
#NoEnv
#Persistent
CoordMode, Pixel
CoordMode, Mouse

; Change this to the exact path where you save your screenshot of the button
ImagePath := "X:\Users\Tony\Pictures\Screenshots\Screenshot 2026-06-16 221206.png"

; Coordinates to move your mouse back to so it doesn't obstruct the button
HomeX := 50 
HomeY := A_ScreenHeight - 50 

Loop 
{
    ; Scan the entire monitor for the slow download button (*50 allows for variations in lighting/shading)
    ImageSearch, FoundX, FoundY, 0, 0, A_ScreenWidth, A_ScreenHeight, *50 %ImagePath%
    if (ErrorLevel = 0) 
    {
        ; Button found! Move, click, wait half a second, then reset mouse position
        MouseClick, left, FoundX + 10, FoundY + 10
        Sleep, 500
        MouseMove, %HomeX%, %HomeY%
        Sleep, 4000 ; Wait 4 seconds for the next browser loop tab to open
    }
    else 
    {
        Sleep, 1000 ; If not found, wait 1 second and check again
    }
}
return

; Emergency stop shortcut: Press Ctrl + Alt + P to close the script instantly
^!p::ExitApp
```
- Follow the guide for Viva New Vegas
  - https://vivanewvegas.moddinglinked.com/intro.html
  - NOTE: All mods are already installed in the mod manager via wabbajack. You will still need to install these from the Utilities section in the guide directly into the Fallout NV folder:
  - New Vegas Script Extender (NVSE xNVSE)
  - FNV BSA Decompressor
  - Ultimate Edition ESM Fixes Remastered
  - 4GB Patch