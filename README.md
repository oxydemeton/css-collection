# CSS Collection
## Links
- [CSS Files](/css)
- [Color Schemes](/css/color-schemes)
- [Live Test](https://mabla.name/css-collection)

## General
This CSS collection is a combination of different CSS files to simplify basic website design. They use modern CSS and try to represent modern standards. This can lead to unexpected behavior on older browsers!<br>
This reposetory also includes the examples/tests/comparisons live on my [website](https://mabla.name/css-collection).

## File Overview
### [base.css](/css/base.css)
Default values to standardize different the behavior of browsers and improve basic visuals on basic websites.<br>
Also includes custom properties for variable font sizes.
### [fonts.css](/css/fonts.css)
Addition of variable fonts to use on your website.<br>
Fonts can be found in their [folder](/css/fonts).<br>
Those fonts are not small and may lead to some traffic in compromise for them being variable in font weight.
This file does not depend on other files beside those fonts.
### [util.css](/css/util.css)
This file includes multiple utility classes. In the future, they might be separated into more files to reduce file size when not needing all classes.
The type and variations of those classes are work in progress and might change in the near future!
### [color-scheme.css](/css/color-scheme.css)
This file uses dark/light mode as the user has set in his settings. It also adds a basic grayscale color scheme to your website. Those main and accent colors are applied to most HTML elements and react to a switch of dark and light mode.<br>
Different color schemes can be found in their [folder](/css/color-schemes).<br>
The way classes to force or switch dark and light mode are work in progress and might change, especially to reduce file size.<br>
The different color schemes from this repository can be compared with the [color-scheme.html](/color-scheme.html) or live on my [website](https://mabla.name/css-collection/color-scheme.html).

## Plans
- Addition of common layouts to the utility classes or a new file.
- Additional Test and comparisons of for example layouts.
- Small adjustments to color schemes
- Reduction of file sizes
- Addition of fonts
- Addition of static font (for compatibility and file sizes)
