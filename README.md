# Sublime 3

## Considerations
The content of this repository is located in Sublime user folder. The path to this folder may vary depending on the OS the software is installed. 

This repository includes configurations that suit my preferences. You can clone/copy the content of this repo to your Sublime user folder and modify to suit your needs.

Sublime Text 3 comes with its own Python embedded interpreter that’s separate from your system’s Python interpreter (if available).

Some Sublime plugins require to have [PHP](http://php.net/downloads.php) and [Node.js](https://docs.npmjs.com/getting-started/installing-node) installed on your system.


## Running Sublime 3 from the command line
Sublime Text includes a command-line helper called `subl`. Using the command-line helper, you can open files and folders and perform other actions from the command line.

`subl` must be included in your `PATH` before it can be used. To put `subl` on your `PATH`, you may need to add directories to `PATH` or use [symbolic links](http://olivierlacan.com/posts/launch-sublime-text-3-from-the-command-line/).

Here you can find further info about [Sublime command-line helper](http://docs.sublimetext.info/en/latest/command_line/command_line.html).


## Tuning up Sublime 3
Sublime has a [package control](https://packagecontrol.io) repository where you can find a lot of add-ons to boost ST capabilities.

* **[Package Control](https://packagecontrol.io/)**: The very first you'll need to install for ST3. Here you can find its [installation instructions](https://packagecontrol.io/installation). Once installed, you can install/uninstall packages. Run **cmd + shift + p** on MacOS X (**ctrl + shift + p** on Windows/Linux) and type "install", select **Package Control : Install Package** option. Then type the package you want to install.


### Themes
---

* **[Boxy Theme](https://github.com/ihodev/sublime-boxy)**: A full-featured theme manager for SB3.
	* **[Boxy font-face add-on](https://packagecontrol.io/packages/Boxy%20Theme%20Addon%20-%20Font%20Face)**: Change the font face of the Sublime Text UI. 
	* **[Boxy widget font](https://packagecontrol.io/packages/Boxy%20Theme%20Addon%20-%20Widget%20Font%20Size)**: Change the font size of the panel input and console text (to 13 px by default).

This repository includes a theme, **custom-php-dark.tmTheme**, for a quick look at the different variables, constants, functions... in PHP.


### Plugins
---
In order to boost your productivity, you should install (some of) the following packages:

* **[Sublime Linter](https://packagecontrol.io/packages/SublimeLinter)**: It's a SB3 framework itself for code hinting. *Linters*, like *JSHint*, must be installed separatelly. Your code can be linted as you type (before saving your changes) and any errors are highlighted immediately.

	* **[JSHint](https://packagecontrol.io/packages/JSHint)**: Lint for JS files.
	* **[CSSLint](https://github.com/CSSLint/csslint)**: Lint for CSS files.
	* **[Gutter themes](http://www.sublimelinter.com/en/latest/gutter_themes.html)**: When linting is done, SublimeLinter marks errors in two ways: the suspect code itself is marked, and the line on which the code occurs is marked in the gutter.

* **[Emmet](https://packagecontrol.io/packages/Emmet)**: Previously known as Zen Coding, it can significantly accelerate the way you’re writing HTML & CSS. Write CSS like abbreviation, hit tab to expand… DONE! You can see a demo in its [official site](http://emmet.io/).

* **[HTML-CSS-JS-Prettify](https://packagecontrol.io/packages/HTML-CSS-JS%20Prettify)**: Run this and it will format your HTML, CSS, Javascript or JSON code.

* **[PrettyJSON](https://packagecontrol.io/packages/Pretty%20JSON)**: This plugin allows to Prettify/Minify/Query/Goto/Validate/Lint JSON files for Sublime Text 2 & 3

* **[SublimeCodeIntel](https://packagecontrol.io/packages/SublimeCodeIntel)**: Just start typing code as usual, autocomplete will pop up whenever it’s available. It also allows you to jump around symbol definitions even across files with just a click. It supports a great variety of languages like JavaScript, Mason, XBL, XUL, RHTML, SCSS, Python, HTML, Ruby, Python3, XML, Sass, XSLT, Django, HTML5, Perl, CSS, Twig, Less, Smarty, Node.js, Tcl, TemplateToolkit, PHP. A demo can be found [here](http://sublimecodeintel.github.io/SublimeCodeIntel/).

* **[SidebarEnhancements](https://packagecontrol.io/packages/SideBarEnhancements)**: It provides a few new things in the Sidebar menu including New File Creation in the current project folder, Moving File and Folder, Duplicating File and Folder, Open in Finder and Browser, Refresh, and a bunch more.

* **[Quick File Move](https://github.com/wulftone/sublime-text-quick-file-move)**: Plugin for renaming/moving selected file.

* **[PHPfmt](https://github.com/nanch/phpfmt_stable/)**: PHP code scanner and analyzer for code intelligence within PHP projects.

* **[CSSComb](https://github.com/csscomb/sublime-csscomb/)**: Sublime plugin for CSScomb—CSS coding style formatter.

* **[DashDoc](https://github.com/farcaller/DashDoc)**: Sublime plugin for app **Dash**. When installed, just type ```cmd+h``` to go to documentation in Dash.

You can view all the packages installed for this repo in the **Package Control.sublime-settings** file and install the ones you need with **Package Control**. Remember to install the packages in this file or delete the ones that you don't need.


## Key Bindings

The following key-bindings are taken from Sublime Text for MacOS X. Replace *cmd* key with *ctrl* when needed for Windows & Linux.

### Default (OSX).sublime-keymap - Default

Here are some common shortcuts defined by SublimeText by default:

* **cmd + shift + n**: Open new window
* **cmd + shift + n**: Close a window
* **cmd + n**: New file
* **cmd + s**: Save file
* **cmd + w**: Close file
* **cmd + o**: Prompt open
* **cmd + p**: Go to file
* **cmd + ctrl + p**: Select workspace
* **cmd + shift + p**: Command palette
* **cmd + r**: Go to function definition
* **ctrl + g**: Go to line X in file
* **cmd + f**: Find
* **cmd + g**: Find next
* **cmd + shift + g**: Find previous
* **cmd + ctrl + up**: Swap line up
* **cmd + ctrl + down**: Swap line down
* **cmd + alt + left**: Select previous file in tab bar
* **cmd + alt + right**: Select next file in tab bar
* **F12**: Go to definition

The complete list of shortcuts for MacOS X can be found on **[Sublime docs](http://docs.sublimetext.info/en/latest/reference/keyboard_shortcuts_osx.html)**.

### Plugin Key bindings
---
* **MoveTab**
	* **cmd+alt+shift+left**: Move current tab to the left.
	* **cmd+alt+shift+right**: Move current tab to the right.

### Default (OSX).sublime-keymap - User
---
The following shortcuts are defined in the User's ***.sublime-keymap*** file, and were chosen to suit my needs. Some of them are related to specific add-ons, so you must have them installed. Other plugins may have their own key bindings (see *.sublime-keymap* in the package folder). Feel free to change these key bindings your way:

* **alt + p**: Prompt select workspace.
* **alt + up**: Multi-select previous lines.
* **alt + down**: Multi-select next lines.
* **alt + shift + r**: Refresh folders.
* **alt + shift + w**: Close all files.
* **alt + shift + s**: Convert to snake_case.
* **alt + shift + c**: Convert to camelCase.
* **shift + delete**: Right delete.
* **cmd + shift + '**: Toggle between single/double quotes.
* **cmd + shift + c**: Toggle comment (single line).
* **cmd + shift + up**: Swap line up.
* **cmd + shift + down**: Swap line down.
* **F1**: Go to the documentation *(requires 'GoTo Documentation')*.
* **F3**: Rename (or move) current file *(requires 'Quick move file')*.
* **F8**: Toggle side bar.
* **F9**: Toggle tab menu.
* **F10**: Go to selected text *(requires 'goto _ selected _ text.py' included)*.
* **ctrl + F11**: Format code properly *(requires 'JsFormat')*.


## Acknowledges
Special thanks to **[Carlos Gant](https://github.com/adael)**. Included custom PHP theme for Sublime is based on one from him.