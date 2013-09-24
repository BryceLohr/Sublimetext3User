To-Do
=====

Features/changes to implement next.


1. `'.` normal-mode command to jump to last change
2. Change list and accompanying navigation
3. `ctrl+t` normal-mode command to go back to previous spot after jumping to tag (going to definition, actually). This means the default key binding for the "transpose" command would need to be remapped, though.
4. `ctrl+e` and `ctrl+y` insert-mode commands to copy the character below or above the cursor, respectively
5. Fix bug in Vintage mode where 'gq' format command joins the formatted text with lines above and below the target text
6. `vintage_ctrl_keys`:
    1. Add normal-mode `ctrl+v` for visual block mode with multiple selections, like middle-mouse button selections
    2. Add insert-mode `ctrl+r` to put-from-register
    3. Add insert-mode `ctrl+y` and `ctrl+e` to insert character in same column from line above and below (respectively) on current line
