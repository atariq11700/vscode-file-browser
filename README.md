# File Browser

An integrated, keyboard driven file selector for VS Code, inspired by Emacs's
[Helm](https://emacs-helm.github.io/helm/) file selector. Originally written by Bodil Stokke, forked and expanded on by [me](https://github.com/atariq11700)

![screenshot](images/file-browser.gif)

## Features

This is what this extension gives you:

-   A fully keyboard driven file open dialog: bind `file-browser.open` to `Ctrl+O` (or `C-x C-f` if
    you're an Emacs expat) and enjoy the lack of OS file dialog clutter.
-   Start typing a file name to quickly find it in the current folder. Use `Tab` to autocomplete.
-   Automatically create files and folders just by typing their names and selecting the option that
    appears.
-   Easy navigation in and out of folders by using the left and right arrow keys.
-   Navigate to your home folder by typing `~/` into the search box, or step up to the parent folder
    by typing `../`.
-   Perform file operations like rename and delete by stepping into a file with the right arrow key,
    or by hitting `Ctrl+A` on any file or folder.

-   Navigate between files and folders on different drive for windows machines

## Notes

-   This should work with linux. If you are having issues, make sure you have nodejs >= 16, udev installed and util-linux installed.

## Features Todo  

-   Add the ability to open a file in your editor of choice
-   Add support to open notebook files as notebooks or text files

## Licence

This program is free software: you can redistribute it and/or modify it under the terms of the GNU
Lesser General Public License as published by the Free Software Foundation, either version 3 of the
License, or (at your option) any later version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without
even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU
General Public License for more details.

You should have received a copy of the GNU Lesser General Public License along with this program. If
not, see <https://www.gnu.org/licenses/>.

## Original Repository and Readme
[Original Repository](https://github.com/bodil/vscode-file-browser)  
[Original Readme](original-readme.md)

