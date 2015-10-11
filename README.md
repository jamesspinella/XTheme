# Xtheme

A Sketch template for quickly and easily designing new themes for Xcode.
--------------------------------------------------------------------------

**NOTE**: This is still a work in progress! Feel free to check it out, use it, or even contribute to it! Right now the Sketch template is missing sample code for a few of the Fonts & Colors text categories, but the most-common text categories are in there.
  
  
Adjust fonts and colors and immediately see each change in sample code so you'll know how your color and font combinations actually look in the wild.
  
NOTE: Xcode Theme colors are in RGBA Decimal format, and often go to as many as six (6) decimal places. It's best to paste in color codes from Sketch into Xcode's Colors & Fonts when editing and creating themes, rather than pasting in values directly to .dvtcolortheme (Xcode theme) files.   
  
All of this was made with Xcode 7.0.1, but should work as far back as Xcode 5 (?).
  
Breakpoint/Line number "sidebar" background color is automatic based on Source Editor background color (restart Xcode for change to take effect). The font in that area is set by Xcode and cannot be changed by the user (San Francisco on OS X 10.11). It may be possible that you can change by opening the theme file in a text editor and manually changing all instances of San Francisco (called ".SF....") to the font of your choice. 
  
  
And hey, some Xcode themes!
---------------------------

**Specials Board** - Based on Coda's Specials Board theme.  
**Atom** - Based on Atom's default color scheme. 
  
*More themes to come in future releases!*
