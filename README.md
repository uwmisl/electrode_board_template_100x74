# electrode_board_template_100x74

This project provides a KiCad template project which can be used as a convenient
starting point for custom electrode boards. It includes connector footprints, 
placed at the correct locations, as well as the "standard" mounting hole placements
used by some other components. 

## Installation

To install the template, check out the project and place it into your 
KiCad user template directory. The location of this directory varies on 
different operating systems, but you can find it by runnign KiCad and selecting
"Preferences->Configure Paths..." in the menu. You are looking for the value of
`KICAD_USER_TEMPLATE_DIR`. On linux or MacOS, this is likely to be `$HOME/kicad/template`.

So, for example:

```
mkdir -p ~/kicad/template
cd ~/kicad/template
git clone https://github.com/uwmisl/electrode_board_template_100x74
```
