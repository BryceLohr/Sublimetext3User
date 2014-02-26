To-Do
=====

Features/changes to implement next.


1. Change list and accompanying navigation
1. `ctrl+t` normal-mode command to go back to previous spot after jumping to tag (going to definition, actually). This means the default key binding for the "transpose" command would need to be remapped, though.
1. Normal-mode binding for `''` to jump back to previous position
1. Fix bug in Vintage mode where `gq` format command joins the formatted text with lines above and below the target text, even if they are not selected or not in the same scope
1. `vintage_ctrl_keys`:
    a. Add normal-mode `ctrl+v` for visual block mode with multiple selections, like middle-mouse button selections
    a. Add insert-mode `ctrl+r` to put-from-register
    a. Add insert-mode `ctrl+y` and `ctrl+e` to insert character in same column from line above and below (respectively) on current line
1. `gv` normal-mode command to re-select the previous selection after un-selecting
1. `;` normal-mode command to repeat last intra-line character find. Also support repeat count.
1. BUG: Bracket-like text objects (), [], {}, don't work inside strings of a language's syntax (https://github.com/sublimehq/Vintage/issues/75)
