# WeiDU Syntax Highlighting for Kate

This package contains syntax highlighting definitions for the [Kate Text Editor](https://kate-editor.org/). Kate for the KDE Frameworks version 5.79 (released February 2021) or later is required.

## Installation

Place the definition files from the "syntax" folder of this package into the directory as specified below. All of the files must be installed together as they cross-reference each other.

### Linux/Unix

#### For local users

Navigate to `$HOME/.local/share/org.kde.syntax-highlighting/syntax/`. Create the directory if it doesn't exist yet. Place the files `weidu-tp2.xml`, `weidu-baf.xml`, `weidu-d.xml`, and `weidu-tra.xml` from the "syntax" folder of this package into the folder and restart Kate or KWrite.

#### For Flatpak packages

Navigate to `$HOME/.var/app/<package-name>/data/org.kde.syntax-highlighting/syntax/` where `<package-name>` specifies the fully qualified package name of Kate or KWrite (e.g. *org.kde.kate*). Create the directory if it doesn't exist yet. Place the files `weidu-tp2.xml`, `weidu-baf.xml`, `weidu-d.xml`, and `weidu-tra.xml` from the "syntax" folder of this package into the folder and restart Kate or KWrite.

#### For Snap packages

Navigate to `$HOME/snap/package-name/current/.local/share/org.kde.syntax-highlighting/syntax/` where `<package-name>` specifies the package name of Kate or KWrite. Create the directory if it doesn't exist yet. Place the files `weidu-tp2.xml`, `weidu-baf.xml`, `weidu-d.xml`, and `weidu-tra.xml` from the "syntax" folder of this package into the folder and restart Kate or KWrite.

### Windows

Navigate to `%USERPROFILE%\AppData\Local\org.kde.syntax-highlighting\syntax\`. Create the directory if it doesn't exist yet. `%USERPROFILE%` usually expands to `C:\Users\<your-user-name>\`. Place the files `weidu-tp2.xml`, `weidu-baf.xml`, `weidu-d.xml`, and `weidu-tra.xml` from the "syntax" folder of this package into the folder and restart Kate or KWrite.

### macOS

Navigate to `$HOME/Library/Application Support/org.kde.syntax-highlighting/syntax/`. Create the directory if it doesn't exist yet. Place the files `weidu-tp2.xml`, `weidu-baf.xml`, `weidu-d.xml`, and `weidu-tra.xml` from the "syntax" folder of this package into the folder and restart Kate or KWrite.

## Usage

A suitable syntax highlighter is automatically selected if the opened file contains any of the supported file extensions.
- WeiDU TP2: `.tp2`, `.tpa`, `.tph`, or `.tpp`. Select menu *Tools > Highlighting > Scripts > WeiDU TP2* to enable the syntax highlighter manually.
- WeiDU BAF: `.baf`. Select menu *Tools > Highlighting > Scripts > WeiDU BAF* to enable the syntax highlighter manually.
- WeiDU D: `.d`. Select menu *Tools > Highlighting > Scripts > WeiDU D* to enable the syntax highlighter manually.
- WeiDU TRA: `.tra`. Select menu *Tools > Highlighting > Other > WeiDU TRA* to enable the syntax highlighter manually.

## Changelog
