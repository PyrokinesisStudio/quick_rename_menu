# Quick rename menu

alt+N bring a popup menu to quickly rename active object

### Description
Just click the name of the object to rename it right in the popup

According to the object name, some proposition might appears under the current name
Click to use it as new name.
(they appears only if the name is free)

Current proposition that may pop-up:  
Cube.002 > Cube

Cube.L > Cube.R

Cube.001 > Cube.L

Cube.L.001 > Cube.R


### why ?

When everything is well named and well ordered the project is better.
But naming is a long and boring task that stop you often in your workflow !
This mainly allow you to rename object even in fullscreen without opening 'n' sidebar or seaching in the outliner or properties.
The propositions are here only to be a bit more convenient.  
About the shortcut, I chose "Alt+N" because it's easy to remember, think "ALTernative Name".


### Updates & todo list:

#### update 04/08/2016
- heavy refactoring
- 2 new rules for propositions

#### update 28/07/2016

- better looking UI popup
- Works with bones name now


####Ideas of rules to add:

-AddRoot (armature_edit mode)
something >> Root if no 'Root' or 'root' detected

-IncrementPreviousNum
Cube_02.001 >> cube_03

-decreaseName
Cube.003 >> propose Cube.001 if Cube exist
