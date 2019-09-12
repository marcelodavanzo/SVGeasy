# svgeasy
Sketch Plugin to easily export SVGO optimised SVG files.

# Installation

1. Install svgo by running `$ npm install -g svgo` in Terminal
2. Download this repo, unzip it, and open the `.sketchplugin` file

# How it works

SVGeasy looks for Symbols named `icon / icon-name / icon-size` and exports them to a folder of your preference as optimised SVGs. The output filename will be `icon-name_icon-size.svg` (eg. delete_32.svg).