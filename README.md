# NPP_KSPlang
Hosting an XML file for KSP config syntax. Works in Notepad++ and potentially other IDEs that allow XML style imports. Currently it's only available for NPP's default light theme but you can customize for yourself by editing the hex values for `fgColor` and `bgColor` in the `<Styles> --> <WordsStyle>` nodes.
The 8 `<Keywords>` nodes contain all the recorded KSP syntax things as folows:
* (Root) Node Names
* PartModule Names
* Stock tech Tree Nodes
* Community tech Tree Nodes
* <Empty>
* ModuleManager Passes
* Resources
* Key Names

## Dark Mode
An alternate styles file now exists (from 0.36) for use with NPP's dark themes. Things to note: It only changes the text colors but you must change NPP's theme separately. Go to `Settings` > `Style Configurator` and choose **Black board** from the dropdown menu. if you choose another dark theme, hit the checkmark for `Enable global background color` then hit `Save & Close`.

## Supporting:
* (Most of?) Stock
* B9 Part Switch
* KerbalKonstructs
* RealPlume

### In progress:
?

## Suggestions
It may be worth your while to install the [Plugin Manager](https://github.com/bruderstein/nppPluginManager
) for Notepad++ and the following plugins to crank up the UX (user experience) a few notches. These names can be found in the Plugin Manager's index once it is installed, rather than visiting the linked websites.

* [CodeAlignment](http://codealignment.com/ForNotepadPlusPlus.html)
* [Elastic Tabstops](http://nickgravgaard.com/elastic-tabstops/)
* [Compare (two files)](https://github.com/jsleroy/compare-plugin)
* [TopMost](https://sites.google.com/site/fstellari/nppplugins)
* [Lua Script](https://github.com/dail8859/LuaScript) (for RPM to MAS prop converting)
