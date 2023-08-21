# Vim Navigation and Editing Shortcuts

VIM Movement notes

### horizontal movement

- `w`: Move to the beginning of the next word.
- `b`: Move to the beginning of the previous word.
- `e`: Move to the end of the current word.
- `ge`: Move to the end of the previous word.
- `0`: Move to the beginning of the line.
- `^`: Move to the first non-blank character on the line.
- `$`: Move to the end of the line.
- `g_`: Move to the non-blank character at the end of the line.
- `t{character}`: Move until the specified character.
- `f{character}`: Find the next occurrence of the specified character.

### Vertical movement

- `}`: Jump downward to the beginning of the next paragraph.
- `{`: Jump upward to the beginning of the previous paragraph.
- `CTRL-D`: Scroll down half a page.
- `CTRL-U`: Scroll up half a page.
- `{line}gg`: Move to a specific line number.
- `gg`: Move to the top of the file.
- `G`: Move to the end of the file.

### Moving Precisely

- `/{pattern}`: Search forward for the specified pattern.
- `?{pattern}`: Search backward for the specified pattern.

### Moving semantically.

- `gd`: Jump to the definition of the word under the cursor.
- `gf`: Jump to a file in an import.

### Other movements.

- `%`: Jump to the matching parentheses, brackets, or braces.
