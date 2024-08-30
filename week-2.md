# Going Horizontal

## New Motions to add to move more effectively (horizontal)

### Important to Note that we can combine these with other motions

### Remember:

### - Command

### - Count

### - Motion

- "\_" goes to the beginning of the line
- $ goes to the end of the line
  - d$ deletes to the end of the line from the cursor's position
- 0 goes to the first character of the line, including whitespace
- f is used as a modifier to go forward to the first instance of a character
  - "f(" goes to the first instance of the character (
- t functions the same as f, but goes to the character before the character you specify
- both f and t motions can be modified with , and ;
  - , goes backwards and ; goes forwards
- F and T are the reverse of f and t
- I goes to the beginning of the line and enters insert mode
- A goes to the end of the line and enters insert mode
- o makes a new line below the current line and enters insert mode
- O makes a new line above the current line and enters insert mode
