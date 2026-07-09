# Adeotype Font-Subset Templates
A set of Python scripts for generating subset font files. Works for both static and variable fonts.

## Dependencies
 - [fonttools](https://github.com/fonttools/fonttools)
 - [brotli](https://github.com/google/brotli)

## Scripts Overview
There are 3 different scripts for you to choose from:
1. Static fonts
2. Variable fonts (weight only)
3. Variable fonts (weight and width)

All scripts contain fallback code that places any extra, non-defined glyph ranges into an orphaned `others` font. If you do not wish to use this font, simply delete the `FONTFAMILY_others.woff2` file and any references to it in the generated `font.css` file.
