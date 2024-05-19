*Original project was archived due to the release of the graphical version of the game*
*This fork aims to continue to add colorschemes to the project for players who still use ASCII*

---


A simple colorscheme generator for Dwarf Fortress

Available to play with at https://manmademagic.github.io/DFColorGen

# DFColorGen
Features:
- Color picker - Using [jscolor](http://jscolor.com)
- Map Preview - Made using [izak1399's font](izaksmells.com/2012/06/dwarf-fortress-ttf-font-download), and a terribly formatted html table
- Creature Color Preview - Based information from DF wiki
- Colorscheme presets - Also from the DF wiki (Feel free to submit a PR if you want to contribute your own!)
- Easy Import/Export of your own colorschemes - Using some client-side javascript, so it stays on your machine

It's using some basic regex to extract the colour values, then using javascript to live update the colours on the page.
Should work in the latest Chrome/Firefox/Edge/IE, but I can't make any guarantees.


## Quick Guide to Adding Colorschemes

First you need to add your file to the Colorschemes folder. 

Next you need to edit colorschemes.js so your file gets loaded in as one of the options. 
