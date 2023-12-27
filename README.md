# Notepad++ Curated Look

Custom color schemes, both themes and language definitions, for Notepad++.

I upload here themes and color schemes I love to use with Notepad++, including some definitions for not-so-popular languages I use often (full list below)

## Installation

User-defined languages in Notepad++ are mostly (painfully) handcrafted. UDL styler files will override your theme colors, in many instances (see the [official reference](https://npp-user-manual.org/docs/user-defined-language-system/#udl-and-themes) for more details).
For this reason, this repository is structured in folders organized by supported themes.

You may install all themes without conflict.

You may want to choose to install only the UDLs of your go-to theme. All UDLs in this repository indicate which theme they are compatible with.

### Installing themes

If in trouble, consult the [official guide](https://github.com/notepad-plus-plus/nppThemes) on how to install Notepad++ themes.

1. Close Notepad++;
2. Clone this repository locally, or download a copy;
3. Import the xml files from this repository `themes\` by placing them in your `themes\` folder:
 - For most installations, copy the content of the `themes` folder to `%APPDATA%\Roaming\Notepad++\themes`
 - If you have multiple users on the same computer, and want the theme available to all users on that machine, put it into `C:\Program Files\Notepad++\themes\` (or `C:\Program Files (x86)\Notepad++\themes for a 32-bit Notepad++`)
 - For portable installations, instead put the themes in the `themes\` sub-folder under the directory where your portable `notepad++.exe` resides
4. Restart Notepad++
5. Select your newly installed theme from Preferences > Style Configurator

### Installing User Defined languages (UDL)

If in trouble, consult the [official guide](https://github.com/notepad-plus-plus/userDefinedLanguages?tab=readme-ov-file#using-a-udl-from-this-collection) on how to install Notepad++ UDLs.

1. Close Notepad++;
2. Clone this repository locally, or download a copy;
3. Import the xml files from this repository `userDefinedLangs` by placing them in your local `userDefinedLangs` folder:
 - For most installations, copy the content of the `userDefinedLangs` to `%APPDATA%\Roaming\Notepad++\userDefinedLangs`:
4. Restart Notepad++.


## Supported Themes

- [Material Dark](https://github.com/naderi/material-theme-for-npp): I loved ths theme a lot, here you can find some languages extensions.

- [Cydonia](https://github.com/daemonPainter/npp_custom_colors/tree/master/Cydonia): Customized theme based on vanilla Blackboard npp theme. Comes with several languages extensions.

## Supported Languages

- GAWK/AWK
- DXL
- VSQ
