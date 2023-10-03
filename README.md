GUIDE TO NAVIGATING GAME OBFUSCATION FOR MODDING PURPOSES 

SETUP:
1. DOWNLOAD MelonLoader & Realmstock to folder
C:\Users\mimi\Documents\RealmOfTheMadGod\Production

2. Launch the game. Wait for the metadata error to appear, then close it.

3. Create a new folder and name it Fix.

4. COPY everything from the Production folder into your new Fix folder.

5. DOWNLOAD the toolkit from: https://github.com/mimination/MelonLoader

6. EXTRACT all contents from MelonLoader-master and place them inside
C:\Users\mimi\Documents\RealmOfTheMadGod\Production\Fix\MelonLoader

MPORTANT NOTES:
- Make sure your new folder is specifically named Fix.
- If you run into issues, try uninstalling MelonLoader from the Production folder and reinstalling it in the Fix folder.
- All interactions with MelonLoader should occur within the Fix directory. Leave the RotMG content in the Production folder untouched.

WHY THIS WORKS:
- MelonLoader wasn't designed to handle obfuscation. By creating the Fix folder, we direct MelonLoader to access the non-obfuscated metadata from our "Fix" directory, bypassing the issues present in the "Production" folder.
