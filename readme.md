Sublime Text 3 Replacement Icon
=============
A replacement icon for [Sublime Text 3](http://sublimetext.com/3)

![Sublime Text 3 replacement icon preview](https://github.com/dmatarazzo/Sublime-Text-2-Icon/raw/master/st2_icon_preview.png "Preview")

Adapted by Daniel Matarazzo from an [icon](http://dribbble.com/shots/317512-Sublime-Text-2-Icon) by [Lindsay Mindler](http://lindsayburtner.com/)

Forked by Eric West (@edubkendo), converted to ruby script (`ubuntu_icons_script`), and added `sublime_text.desktop` and `subl` script.

Installation (Mac OS X)
------------

Open the following folder:

    open /Applications/Sublime\ Text\ 3.app/Contents/Resources/

Find the file `Sublime Text 3.icns` and replace with the one from this repository. The name needs to remain exactly the same.

If you want to replace the built-in document icons as well, copy all the .icns files from this project's `Document Icons` folder to the same folder as above. Doing so will overwrite the application's default icons, so you may want to back them up in case you'd like to restore them.`

Additionally, there's a bash script that will do all of the above, with a little trick to force reloading the application icons. With Sublime closed, from this project's folder, run:

    ./mac_replace_icons

You can also just double click on the 'mac_replace_icons' script, and it will run in terminal. Because it uses sudo, you'll need to put in your password.


Installation (Windows 7)
------------

Download [ResEdit](http://www.resedit.net/)

1.  Navigate to the installation folder for Sublime Text 3 (this should be in C:\Program Files\Sublime Text3). Copy `sublime_text.exe` to your desktop.*
2.  Run ResEdit, choose `File > Open Project ...`. Select the `sublime_text.exe` you copied to your desktop.
3.  In the Resources pane of ResEdit, right-click the Icon folder and choose `Add Resource > Icon...`.
4.  Navigate to the folder containing the `sublime_text.ico` file. Add it.
5.  Right-click the icon named `103 [English (Australia)]`, select `Remove from Project`.
6.  Save.
7.  Copy the `sublime_text.exe` on your desktop back to the Program Files folder from step 1.

---
* The Program Files folder is protected. You need to move the exe out of this folder to edit it.

Installation (Ubuntu)
------------
First: Ensure ruby is installed:

```
    ruby -v
```

If you don't see something like:

```
ruby 2.1.0dev (2013-09-22 trunk 43011) [x86_64-linux]
```

then [install ruby](https://github.com/postmodern/ruby-install)

1.  [Download this repository](https://github.com/edubkendo/sublime-text-update/zipball/master)
2.  Open a terminal, `cd` to wherever you downloaded the repository to.
3.  Unzip the repository: `unzip REPOSOITORY_NAME.zip`
4.  `cd` into the repository folder.
5.  Run the Ubuntu Installation Script `./ubuntu_icons_script`
6.  Ha! Run it as root.
