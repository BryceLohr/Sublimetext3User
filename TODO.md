To-Do
=====

Features/changes to implement next.


1. `'.` normal-mode command to jump to last change
1. Change list and accompanying navigation
1. `ctrl+t` normal-mode command to go back to previous spot after jumping to tag (going to definition, actually). This means the default key binding for the "transpose" command would need to be remapped, though.
1. Fix bug in Vintage mode where 'gq' format command joins the formatted text with lines above and below the target text
1. `vintage_ctrl_keys`:
    a. Add normal-mode `ctrl+v` for visual block mode with multiple selections, like middle-mouse button selections
    a. Add insert-mode `ctrl+r` to put-from-register
    a. Add insert-mode `ctrl+y` and `ctrl+e` to insert character in same column from line above and below (respectively) on current line
1. Fix `gq` normal-mode command to only format within the same text scope (ie, a comment), instead of affecting the lines above & below
1. `gv` normal-mode command to re-select the previous selection after un-selecting
1. `;` normal-mode command to repeat last intra-line character find. Also support repeat count.
