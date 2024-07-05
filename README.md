# Open a file or folder
`vim <path/to/file_or_folder>`

# Edit file
Press `Ins` key or use `i`

# Save file and not quit
```
Press Esc to exit edit
:w
```

# Save file and quit
```
Press Esc to exit edit
:q
```

# Unsave file and not quit
```
Press Esc to exit edit
:e!
```

# Unsave file and quit
```
Press Esc to exit edit
:q!
```

# Search a keyword in file
```
\<keyword>
```

# Search and repace of each key
```
:s/<keyword>/<replaceword>/g
```

# Search and repace all
```
:%s/<keyword>/<replaceword>/g
```

# Quit file and go back to current openning folder
```
:Ex (With E is uppercase)
```

# Delete a line
```
Press Esc to exit edit
dd
```

# Go to line number
```
:<linenumber>
```

# Show/Unshow line number
```
:set number
:set nonumber
```

# Change file name
```
navigate to file in folder
Use `R` key (uppercase letter)
Change file name and enter
```

# Move line up/down
## Move a Single Line Up
Position the cursor on the line you want to move.

Cut the line with `dd` (this deletes the line and places it in the buffer).

Move the cursor to the line above where you want to place the cut line.

Paste the line above with `p`.

## Move a Single Line Down
Position the cursor on the line you want to move.

Cut the line with `dd`.

Move the cursor to the line below where you want to place the cut line.

Paste the line below with `p`.
