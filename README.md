#Sublime 3

##First steps
The first thing you'll need to do is to get PHP 7, MySQL, Python & [Node.js](https://docs.npmjs.com/getting-started/installing-node) installed in order to use some useful add-ons for Sublime 3.

##Tuning up Sublime 3
Sublime has a [package control](https://packagecontrol.io) repository where you can find a lot of add-ons to boost ST capabilities. The following ones have been selected to improve productivity, including web, PHP and MySQL features.

* **[Package Control](https://packagecontrol.io/)**: The very 1st you'll need to install for ST3. Here you can find its [installation instructions](https://packagecontrol.io/installation). Once installed, you can install/uninstall packages. Run **cmd + shift + p** on MacOS X (**ctrl + shift + p** on Windows/Linux) and type "install", select **Package Control : Install Package** option. Then type the package you want to install.


###Themes
---

* **[Boxy Theme](https://github.com/ihodev/sublime-boxy)**: A full-featured theme manager for SB3.
	* **[Boxy font-face add-on](https://packagecontrol.io/packages/Boxy%20Theme%20Addon%20-%20Font%20Face)**: Change the font face of the Sublime Text UI. 
	* **[Boxy widget font](https://packagecontrol.io/packages/Boxy%20Theme%20Addon%20-%20Widget%20Font%20Size)**: Change the font size of the panel input and console text (to 13 px by default).

###Add-ons
---

* **[Sublime Linter](https://packagecontrol.io/packages/SublimeLinter)**: It's a SB3 framework itself for code hinting. *Linters*, like *JSHint*, must be installed separatelly. Your code can be linted as you type (before saving your changes) and any errors are highlighted immediately.

	* **[JSHint](https://packagecontrol.io/packages/JSHint)**: Lint for JS files.
	* **[CSSLint](https://github.com/CSSLint/csslint)**: Lint for CSS files.
	* **[Gutter themes](http://www.sublimelinter.com/en/latest/gutter_themes.html)**: When linting is done, SublimeLinter marks errors in two ways: the suspect code itself is marked, and the line on which the code occurs is marked in the gutter.