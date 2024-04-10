# TAE 30: Blockly Programming
**Due:** April 18, 11:59 PM

## Week 2

### Learning Goals
- Create a simple script in Blockly
- Learn and practice some of the programming basics:
  - Defining a variable
  - if statement for logical comparison
  - Loop
  - Function

### Software and Hardware
- BlocklyProp Solo
- Activity Board
- Parallax USB programming cable

### Programming
- Create a script that:
  1. Gets a number from users, and
  2. Identifies if the number is odd or even.
  3. Prints the outcome in the terminal (e.g., "This is an EVEN number!")
- Save your code on your computer periodically.
- Submit your code saved as a *.svg file.

### What to Submit
- Submit your code saved as a *.svg file.

## Instruction and Hints
- The script should have two main blocks:
  - Main block, in which there are
    - A continuous loop (use repeat forever block) asking users to enter a number (use terminal receive block).
    - Call a function that identifies if this is an even or odd number.
    - At the beginning of this block, you may want to add a new line (use terminal new line block) and a text block that prompts users to enter a number (use terminal print text block).
  - Your function block, which
    - Identifies if this is an odd or even number.
    - Prints the outcome in the terminal (e.g., "This is an ODD/EVEN number.").
- **Hints:**
  - To identify if a number is odd or even, you need to check the remainder when you divide the number by 2. If a number is evenly divisible by 2 with no remainder (remainder is equal to zero), then it is even, otherwise, it is odd (remainder is not equal to zero). You can use the math operation block and change it to remainder after division in the mutation window (gear icon).
  - Use if statement to check if the remainder is equal to zero or not:
    - If remainder = 0 -> this is an even number.
    - If remainder ≠ 0 -> this is an odd number.
  - You may want to add comments to your code to make your code more readable, make code maintenance much easier, and help others better understand your code.

### Useful Resources
- [Propeller BlocklyProp Block Reference](https://learn.parallax.com/support/reference/propeller-blocklyprop-block-reference)
  - Variable Blocks
  - Terminal Talk
  - Values and Math Blocks
  - Making Decisions
  - Blocks that Repeat
  - Functions
