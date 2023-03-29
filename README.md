# File Browser

# ***INSTALLATION NOTES***  
If you are on linux, 32bit or 64bit or are using wsl or ssh, vscode for some reason does not download the correct version. There are windows builds, and linux builds because of binary dependencies, and vscode will just download the windows version. IDK why. The check which version is installed, there are 2 ways. You can either navigate to where you extensions are installed, and make sure that linux is at the end of the extension folder name, or if it deoesnt open, toggle dev tools and reload. If there is an error that states something like "Invalid ELF header" then it installed the windows version.


Fixes:  
* If using remotes(wsl/ssh)
    * Install the extension both locally and on the remote
    * In the extension tab, navigate to the extensions installed on the remote
    * Click the dropdown next to uninstall and click install a different version
    * Select an older version, reload, then repeat the steps with the newer version
    * Or install the vsix direct from the github release page [here](https://github.com/atariq11700/vscode-file-browser/releases)
* If using native linux
    * This should hopefully work better than when using a remote
    * If it doesnt try ^
    * Otherwise install the vsix from the github release page [here](https://github.com/atariq11700/vscode-file-browser/releases)



## About

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

