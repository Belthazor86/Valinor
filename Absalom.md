# **Absalom: Makes Emulation Portable**

Absalom is a portable emulator and ROM launcher that is designed to launch ROMs with compatible emulators.. 

**Key Features**

+ 100% Portable: Runs directly without installation perfect for USB drives.
+ Emulators: Add any emulators in the emulators folder
+ ROMS: Add ROMS in respective folders
+ Renders: Add renders in respective folder to have a manual sliodeshow 


**Instructions**

1. Add emulators and ROMS in respective folders .
2. To save space ROMS should be in zip format expect the ones below
3. 3DS and Switch must be in their original format
4. PSP. PS2, PS3 and GameCube must be in iso format
5. Select game and emulator form drop down menu and then assign
6. Select only the emulator and assign   


```mermaid
graph TD
    Absalom["Absalom/"] --> folder1["emulators/"]

    Absalom --> folder2["roms/"]

    Absalom --> folder3["renders/"]

    folder1 --> file1["GBA/"]
    folder1 --> file2["NDS/"]
    folder1 --> file3["PSP/"]


    folder2 --> file4["DeSmuME/"]
    folder2 --> file5["Dolphin/"]
    folder2 --> file6["DuckStation/"]


    folder3 --> file7["Image1.jpg"]
    folder3 --> file8["Image2.jpg"]
    folder3 --> file9["Image3.jpg"]

```



> 🚀 **Continuous improvement :** An ongoing effort to enhance Balrog.
> 
> 📝 **Usage:** Absalom is for personal use only.
>
> 🆘 **Support:** If you have any issues with Balrog please reach out politely in GitHub Discussions






