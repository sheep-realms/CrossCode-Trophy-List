[中文](README.md) | **English**

# CrossCode Trophy List

This project lists the internal names of all achievements in CrossCode.  
The data is sourced from the `database.json` file in the game's asset folder.

Achievements in this game have actual gameplay effects and can significantly improve the New Game+ experience. However, I couldn't find any shared 100% completion save files or a list of achievement internal names, so I created this repository.

## Save Editing Guide

**It is strongly recommended that you back up your save file before editing it!**

1. Locate the game's save file (on Windows, it is usually located at `<SystemDrive>:\Users\<Username>\AppData\Local\CrossCode\cc.save`).
2. Open the save file and extract the value of the `globals` field.
3. Use a save editor (for example, [CCSaveEdit](https://insyg.github.io/CCSaveEdit/)) to decode the extracted data.
4. Open the `trophy.json` file in this project, copy the value of the `feats` field, and replace the `feats` field value in the save data with it.
5. Apply the changes in the save editor and output the encoded data, then replace the value of the `globals` field in the save file.