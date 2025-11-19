# untrusted
Solutions and hints for Untrusted - a user javascript adventure game
<details><summary>  
    01-cellBlockA
  </summary>

### Hint 1
<details>
  <summary>Click to reveal</summary>
  Pick up the computer (symbol that looks like Mac command).
</details>

### Hint 2
<details>
  <summary>Click to reveal</summary>
  The description gives you a clue: "In fact, you should be doing less."
</details>

### Hint 3
<details>
  <summary>Click to reveal</summary>
  What do the for-loops in the editable area do?
</details>

### Hint 4
<details>
  <summary>Click to reveal</summary>
  What do the for-loops in the editable area do?
</details>

### Solution
<details>
  <summary>Click to reveal</summary>
  Delete one of the for-loops in the editable area to create a gap.
</details></details>
<details><summary>  
02-theLongWayOut
  </summary>

### Hint 1
<details>
  <summary>Click to reveal</summary>
  Once again, the description gives you a clue: "four clever characters should be enough to erase all their tricks."
</details>

### Hint 2
<details>
  <summary>Click to reveal</summary>
  What are four characters that make a block of code "useless," to the computer at least?
</details>

### Hint 3
<details>
  <summary>Click to reveal</summary>
  What do you do when you want to make a note to yourself in a block of code?
</details>

### Solution
<details>
  <summary>Click to reveal</summary>
  Comment out the code using <code>/*</code> and <code>*/</code>.
</details></details>

<details><summary>  
03-validationEngaged
  </summary>

### Hint 1
<details>
  <summary>Click to reveal</summary>
  Try deleting one of the for-loops. What error message do you get?
</details>

### Hint 2
<details>
  <summary>Click to reveal</summary>
  If a required amount of blocks are required to be there, what can you do?
</details>

### Hint 3
<details>
  <summary>Click to reveal</summary>
  How can you move one of the boundaries somewhere else, keeping the same number of blocks?
</details>

### Solution
<details>
  <summary>Click to reveal</summary>
  Replace the <code>10</code> in the <code>x</code> for-loop with <code>0</code>, moving the top boundary to the top of the screen. 
</details></details>

<details><summary>  
04-multiplicity
  </summary>

### Hint 1
<details>
  <summary>Click to reveal</summary>
  Once again, the description gives us a hint: "Level filenames can be a hint, by the way." This filename is <code>multiplicity</code>.
</details>

### Hint 2
<details>
  <summary>Click to reveal</summary>
  <code>Multiplicity</code> means to duplicate, or to make clones, of something. What can you duplicate in this case?
</details>

### Hint 3
<details>
  <summary>Click to reveal</summary>
  You can't move out of the box. But what can you move into the box?
</details>

### Solution
<details>
  <summary>Click to reveal</summary>
  In the editable zone, place an object called "exit". There, you've just placed an exit within reach! 
</details></details>
<details><summary>  
    05-minesweeper
  </summary>

### Hint 1
<details>
  <summary>Click to reveal</summary>
  Look carefully at the closing brackets right after the editable zone. Which loop are you editing in?
</details>

### Hint 2
<details>
  <summary>Click to reveal</summary>
  The description once again gives a clue: "If only there was some way you could track the positions of the mines..."
</details>

### Hint 3
<details>
  <summary>Click to reveal</summary>
  How can you change the color of squares? Look at preceding code.
</details>

### Hint 4
<details>
  <summary>Click to reveal</summary>
  You're editing in the if-loop that defines where mines are placed. 
</details>

### Solution
<details>
  <summary>Click to reveal</summary>
  Insert this line: <code>map.setSquareColor(x, y, '#fff');</code> to change the color of all mineblocks.
</details></details>
