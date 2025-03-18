# WeiDU Syntax Highlighting for Kate

This package contains syntax highlighting definitions for the [Kate Text Editor](https://kate-editor.org/). Kate for the KDE Frameworks version 5.79 (released in February 2021) or later is required.

## Installation

This package provides three different flavors of syntax highlighting definitions:
1. A set of **neutral syntax definitions** using the built-in color schemes of the text editor. It can be found in the "syntax" folder. (**Preview: [dark](https://raw.githubusercontent.com/Argent77/Kate-WeiDU/refs/heads/master/preview/neutral-dark.webp), [light](https://raw.githubusercontent.com/Argent77/Kate-WeiDU/refs/heads/master/preview/neutral-light.webp)**)
2. A predefined **dark color scheme** based on the dark [WeiDU color scheme for Notepad++](https://github.com/Argent77/NotePad_PlusPlus_WeiDU). It can be found in the "syntax-colored-dark" folder. (**[Preview](https://raw.githubusercontent.com/Argent77/Kate-WeiDU/refs/heads/master/preview/npp-dark.webp)**)
3. A predefined **light color scheme** based on the light [WeiDU color scheme for Notepad++](https://github.com/Argent77/NotePad_PlusPlus_WeiDU). It can be found in the "syntax-colored-light" folder. (**[Preview](https://raw.githubusercontent.com/Argent77/Kate-WeiDU/refs/heads/master/preview/npp-light.webp)**)

Place the definition files from the folder of your choice into the directory as specified below. All of the files must be installed together as they cross-reference each other.

### Linux/Unix

#### For local users

Navigate to `$HOME/.local/share/org.kde.syntax-highlighting/syntax/`. Create the directory if it doesn't exist yet. Place the files `weidu-tp2.xml`, `weidu-baf.xml`, `weidu-d.xml`, and `weidu-tra.xml` from this package into the folder and restart the text editor.

#### For Flatpak packages

Navigate to `$HOME/.var/app/<package-name>/data/org.kde.syntax-highlighting/syntax/` where `<package-name>` specifies the fully qualified package name of the text editor (e.g. *org.kde.kate*). Create the directory if it doesn't exist yet. Place the files `weidu-tp2.xml`, `weidu-baf.xml`, `weidu-d.xml`, and `weidu-tra.xml` from this package into the folder and restart the text editor.

#### For Snap packages

Navigate to `$HOME/snap/package-name/current/.local/share/org.kde.syntax-highlighting/syntax/` where `<package-name>` specifies the package name of the text editor. Create the directory if it doesn't exist yet. Place the files `weidu-tp2.xml`, `weidu-baf.xml`, `weidu-d.xml`, and `weidu-tra.xml` from this package into the folder and restart the text editor.

### Windows

Navigate to `%USERPROFILE%\AppData\Local\org.kde.syntax-highlighting\syntax\`. Create the directory if it doesn't exist yet. `%USERPROFILE%` usually expands to `C:\Users\<your-user-name>\`. Place the files `weidu-tp2.xml`, `weidu-baf.xml`, `weidu-d.xml`, and `weidu-tra.xml` from this package into the folder and restart the text editor.

### macOS

Navigate to `$HOME/Library/Application Support/org.kde.syntax-highlighting/syntax/`. Create the directory if it doesn't exist yet. Place the files `weidu-tp2.xml`, `weidu-baf.xml`, `weidu-d.xml`, and `weidu-tra.xml` from this package into the folder and restart the text editor.

## Usage

A suitable syntax highlighter is automatically selected if the opened file contains any of the supported file extensions.
- WeiDU TP2: `.tp2`, `.tpa`, `.tph`, or `.tpp`. Select menu *Tools > Highlighting > Scripts > WeiDU TP2* to enable the syntax highlighter manually.
- WeiDU BAF: `.baf`. Select menu *Tools > Highlighting > Scripts > WeiDU BAF* to enable the syntax highlighter manually.
- WeiDU D: `.d`. Select menu *Tools > Highlighting > Scripts > WeiDU D* to enable the syntax highlighter manually.
- WeiDU TRA: `.tra`. Select menu *Tools > Highlighting > Other > WeiDU TRA* to enable the syntax highlighter manually.

## Changelog
