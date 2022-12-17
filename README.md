# NikkeTools
Encryption/Decryption of assets for NIKKE: Goddess of Victory for purposes of modding of graphical assets  

If you don't own a Spine Pro license for modification of skeletons, you may consider using https://github.com/FZFalzar/skel2json_v4.0 to convert these skel files to the Spine JSON format, which can then be modified with 3rd-party editors such as DragonBones.  
Note: json2skel is planned but there are no planned timelines yet.  

If you like this tool and wish to support future development, consider buying me a coffee @ https://ko-fi.com/fzfalzar or use the sponsor button!

## Special Thanks  
dimbreath, yretenai, Bugs Bunnay and whoever I may have forgotten to mention.  

## Disclaimer
Shiftup/Level Infinite owns the original assets to the game, all credits go to its rightful owner.  
I am not liable for any damages caused if you get banned from using a mod created by this tool, or its derivatives.  

WARNING: Don't be that guy that decides to use this solely for the purpose of clout-farming/karma-farming with leak nonsense or game hacking.  
If Shiftup/Level Infinite decides to crack down on modding because of your stupid actions, you deserve the trouble coming for you.  

## Requirements
.NET Core 3.1 or later - https://dotnet.microsoft.com/en-us/download/dotnet/3.1  

## Usage
Drag drop folder onto exe containing encrypted for default decryption mode, decrypted assets will have "_dec.bundle" added to the back of name, which can then be opened with your favorite asset bundle viewer  

To encrypt, append _MOD to each modded asset bundle's filename, then drag drop folder containing these modded asset bundle files onto exe. After encryption, a new file with _MOD_ENC in the filename will be created, strip this from the filename and replace file in /eb
