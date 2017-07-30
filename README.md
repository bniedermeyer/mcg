# Material Design Color Generator
A tool for generating a color palette for Material Design.
###<a href="http://mcg.mbitson.com/">Click here to view the tool!</a>

# What's New?
* 7/29/17 - Updated references to AngularJS 2 to match [current Angular naming convention](https://angularjs.blogspot.com/2016/12/ok-let-me-explain-its-going-to-be.html).
* 2/2/17 - Added support for Material UI's "Next" branch (React)
* 2/1/17 - Let the user select which color calculation algorithm they'd like to use. (constantin/traditional[mcg])
* 2/1/17 - Added the ability to link to a particular theme. URLs are now updated live as the theme is altered. Individual color alterations will not work with the URL method- use export/import.
* 2/1/17 - Added a "Demo" option that opens some basic AngularJS Material Design elements in the dynamic theme.
* 1/17/16 - Updated color calculation algorithms per the logic shared [here](http://stackoverflow.com/a/36229022/3525315). Thank you Constantin!
* 1/10/16 - Added support for Material UI (React)
* 1/10/16 - Added support for Ember Paper SCSS.
* 1/10/16 - Added support for AngularJS2 Material 2 Framework.
* 1/10/16 - Added ability to export in a format recognized for reimport by MCG. (Enables sharing of palettes)
* 12/18/15 - GitHub user Simon04 added support for automatic text-color contrast calculations. Thank you!
* 10/16/15 - Updated angular, it's dependencies, and other third party tools. Added SpeedDial from Material Design library.
* 10/9/15 - Import from AngularJS Material Design default palettes or from your own AngularJS Material Design Color Palette definition code!
* 10/9/15 - Added support for tinycolor.js instead of manual color manipulation.
* 7/22/15 - Improved Performance with more than 2 palettes.
* 7/14/15 - Support for <a href="http://www.COLOURlovers.com">COLOURlovers.com</a> palettes. You may now select a top palette and instantly have a material design theme!
* 4/16/15 - Modify any one palette color.
* 4/14/15 - Export your color choices to the AngularJS Material Design theme declaration code.

# Planned Future Enhancements
* (TOP) Determine which palette is primary, secondary, and so on. Drag and drop palettes.
* (MED) Remove individual color's hex details and create tooltip styled with all color details. (Hoverintent, populated only once it's opening, includes hex, rgb, cmyk, saturation, brightness. Possibly obtained using tinycolor)
* (MED) Improve performance by dynamically creating and destroying the color picker button and UI instead of loading a ton of Divs into the DOM for each color on the screen and hiding them.
* (LOW) Add reset buttons for each individual color in a palette (based on main palette color)
* (LOW) Create UI for more than 5 palettes (and/or alert user about dangers of using this many palettes)

# Bugs and Questions
* Should you encounter a bug/problem or have a question about the tool please report it using GitHub's "Issues" feature [here](https://github.com/mbitson/mcg/issues).

# Contributions
* fireflight1 - Initial concept, starting code base.
* tkh44 - Optimizations/fixes
* simon04 - Contrast detection, bug fixes.
* Constantin - Color algorithm logic per stack overflow answer [here](http://stackoverflow.com/a/36229022/3525315).