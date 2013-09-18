To-Do
=====

1. `:s` invokes Replace panel
2. `Y` yanks to end of line, rather than the whole line. This annoyed me in Vim as well.
3. `vintage_ctrl_keys: true` so Ctrl-R is Redo.
4. `:bd` closes current buffer
5. `:wq` saves current file and closes buffer
6. `:e` edits a file
7. `ZZ` saves and closes current file as a normal-mode command


Features/changes to implement next.


1. `'.` normal-mode command to jump to last change
2. Change list and accompanying navigation
3. `ctrl+t` normal-mode command to go back to previous spot after jumping to tag (going to definition, actually). This means the default key binding for the "transpose" command would need to be remapped, though.
4. `ctrl+e` and `ctrl+y` insert-mode commands to copy the character below or above the cursor, respectively
5. Fix bug in Vintage mode where 'gq' format command joins the formatted text with lines above and below the target text
