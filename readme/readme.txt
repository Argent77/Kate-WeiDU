WeiDU Syntax Highlighting for the Kate Text Editor
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Version:    1
Author:     Argent77
Download:   https://github.com/Argent77/Kate-WeiDU/releases/latest


Overview
~~~~~~~~

This package contains syntax highlighting definitions for the Kate Text Editor (https://kate-editor.org). Kate for the
KDE Frameworks version 5.79 (released in February 2021) or later is required.

The following file types are covered:
- WeiDU installation scripts (*.tp2, *.tpa, *.tph, *.tpp)
- WeiDU translation tables (*.tra)
- Dialogue scripts (*.d)
- Game scripts (*.baf)


Installation
~~~~~~~~~~~~

This package provides three different flavors of syntax highlighting definitions:

1. A set of neutral syntax definitions using the built-in color schemes of the text editor. It can be found in the
   "syntax" folder.
2. A predefined dark color scheme based on the dark WeiDU color scheme for Notepad++
   (https://github.com/Argent77/NotePad_PlusPlus_WeiDU). It can be found in the "syntax-colored-dark" folder.
3. A predefined light color scheme based on the light WeiDU color scheme for Notepad++
   (https://github.com/Argent77/NotePad_PlusPlus_WeiDU). It can be found in the "syntax-colored-light" folder.

Screenshots for all flavors can be found in the "preview" folder. "neutral-dark.webp" and "neutral-light.webp"
show previews for the neutral syntax definitions with the default "Breeze" color scheme. "npp-dark.webp" and
"npp-light.webp" show previews of the dark and light color schemes based on the WeiDU color schemes for Notepad++.

Place the definition files from the folder of your choice into the directory as specified below. All of the files must
be installed together as they cross-reference each other.


Linux/Unix
~~~~~~~~~~

For local users:

Navigate to "$HOME/.local/share/org.kde.syntax-highlighting/syntax/". Create the directory if it doesn't exist.
Place the files weidu-tp2.xml, weidu-baf.xml, weidu-d.xml, and weidu-tra.xml from this package into the folder
and restart the text editor.

For Flatpak packages:

Navigate to "$HOME/.var/app/<package-name>/data/org.kde.syntax-highlighting/syntax/" where <package-name> specifies
the fully qualified package name of the text editor (e.g. org.kde.kate). Create the directory if it doesn't exist.
Place the files weidu-tp2.xml, weidu-baf.xml, weidu-d.xml, and weidu-tra.xml from this package into the folder
and restart the text editor.

For Snap packages:

Navigate to "$HOME/snap/package-name/current/.local/share/org.kde.syntax-highlighting/syntax/" where <package-name>
specifies the package name of the text editor. Create the directory if it doesn't exist.
Place the files weidu-tp2.xml, weidu-baf.xml, weidu-d.xml, and weidu-tra.xml from this package into the folder
and restart the text editor.


Windows
~~~~~~~

Navigate to "%USERPROFILE%\AppData\Local\org.kde.syntax-highlighting\syntax\". Create the directory if it doesn't exist.
%USERPROFILE% usually expands to "C:\Users\<your-user-name>\".
Place the files weidu-tp2.xml, weidu-baf.xml, weidu-d.xml, and weidu-tra.xml from this package into the folder
and restart the text editor.


macOS
~~~~~

Navigate to "$HOME/Library/Application Support/org.kde.syntax-highlighting/syntax/". Create the directory if it doesn't
exist. Place the files weidu-tp2.xml, weidu-baf.xml, weidu-d.xml, and weidu-tra.xml from this package into the folder
and restart the text editor.


Usage
~~~~~

A suitable syntax highlighter is automatically selected if the opened file contains any of the supported file extensions:
- WeiDU TP2: .tp2, .tpa, .tph, or .tpp. Select menu "Tools > Highlighting > Scripts > WeiDU TP2" to enable the syntax
  highlighter manually.
- WeiDU TRA: .tra. Select menu "Tools > Highlighting > Other > WeiDU TRA" to enable the syntax highlighter manually.
- WeiDU D: .d. Select menu "Tools > Highlighting > Scripts > WeiDU D" to enable the syntax highlighter manually.
- WeiDU BAF: .baf. Select menu "Tools > Highlighting > Scripts > WeiDU BAF" to enable the syntax highlighter manually.


Credits
~~~~~~~

Syntax Highlighting definitions: Argent77

Predefined dark color scheme: Originally provided by WillScarlettOhara for the WeiDU Syntax Highlighters for Notepad++.


Copyright Notice
~~~~~~~~~~~~~~~~

WeiDU Syntax Highlighting for the Kate Text Editor is licensed under the MIT license. See the LICENSE file for more
information.


Changelog
~~~~~~~~~

Version 1
- Initial release
