# Creating New Flows (Inkscape extension)

_________________

## The point of this extension is to
Demonstrate some of the UI capabilities of InDesign and also engage with the software in a way that we dont know yet.

## You install it by doing
1. You will need to have Inkscape and a code editor installed. Inkscape extensions are written in Inkscape XML and python.
2. In Inkscape go to Edit > Preferences > System > User Extensions > Open
3. Download or clone this repository to the User Extensions folder.
4. Relaunch Inkscape. 
5. Sip coffee.
6. Launch the extension from Extensions > Render > create new flows 🐟
7. Edit the other files of the plugin in your code editor. template.inx is a good place to start which is the panel of the plugin, or template.py where the plugin functions are described.

## Other funny things when you make plugins for this software

_________________

Inkscape_extension_template
===========================
This plugin is based on https://github.com/Neon22/inkscape_extension_template An explicit inkscape template to be modified to make new extensions.

Making a new extension in inkscape requires a UI.
There are many fine extensions to use as examples but no single extension shows all the useful features.
This extension shows example parameters to cut and paste as well as a useful tab layout incorporating help.

Includes:

- differences between enums and optiongroups
- int, float
- color
- various forms of help text
- language conversion
etc.
