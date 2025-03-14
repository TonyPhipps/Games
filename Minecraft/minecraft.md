# Resource Pack Setup
- Install Minecraft
- Install 7zip
- Navigate to ```%appdata%\.minecraft\versions\1.19.3``` (or the version you want)
- Extract ```1.19.3.jar``` to a folder. Use this folder as your "originals"
- Make a new folder for your mod and give it a name, then open it.
- Make a new text file, then rename it to ```pack.mcmeta```
- Put the following in the file:

```
{
  "pack": {
    "pack_format": 47,
    "description": "[Any description you want to give your pack]"
  }
}
```

Where "pack_format" is the version code, and "description" is the name displayed in the game.

- Next to your ```pack.mcmeta``` file, make a folder named after the game version, such as ```1.19.3```

Your resourcepack folder is now ready for modified files.

- Inside the folder named after the game version, replicate the folder and file structure for any files you wish to overwrite with your mod. Use the original folder as reference if needed.
- For each texture/file you want to change, copy it into a matching folder structure
- For example, make subfolders for ```\assets\minecraft\textures\block\```, then copy/paste the modified ```grass_block_side.png``` in the block folder.

## Resource Pack Preparation
Once you are done and have all the files in place for Minecraft to prioritize them over its own files...
- Go to your Resource Pack folder. You should see an ```assets``` folder and the ```pack.mcmeta``` file.
- Select both files
- Add to a zip
- Rename the zip to your mod name
- Copy or move the ```mod.zip``` to ```%appdatat%\.minecraft\resourcepacks```
- Open the game and turn on the mod via Options > Resource Packs

 
 ## Using NovaSkin (https://minecraft.novaskin.me/)
  - Save
  - Download tab
  - Right click the picutre > Save Image As
  - Referencing the URL bar, save the .png in the same path with the same name in your mod folder.
    - You may need to create folders first
    - If you are replacing or updating one, click the old file to overwrite it