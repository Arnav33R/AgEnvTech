# Blockly Programming
**Due:** April 18, 11:59 PM

## Lab 2

<h2 style="background-color: #008080; color: white;">Learning Goals</h2>

<ul>
    <li>Create a simple script in Blockly</li>
    <li>Learn and practice some of the programming basics:</li>
    <ul>
      <li>Defining a variable</li>
      <li>if statement for logical comparison</li>
      <li>Loop</li>
      <li>Function</li>
    </ul>
</ul>

<h2 style="background-color: #008080; color: white;">Software and Hardware</h2>

<ul>
    <li>BlocklyProp Solo</li>
    <li>Activity Board</li>
    <li>Parallax USB programming cable</li>
</ul>

### Instructions
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
    - A continuous loop (use *repeat forever* block) asking users to enter a number (use *terminal receive* block).
    - Call a function that identifies if this is an even or odd number.
    - At the beginning of this block, you may want to add a new line (use *terminal new line* block) and a text block that prompts users to enter a number (use *terminal print text* block).
  - Your function block, which
    - Identifies if this is an odd or even number.
    - Prints the outcome in the terminal (e.g., "This is an ODD/EVEN number.").

- **Hints:**
  - To identify if a number is odd or even, you need to check the remainder when you divide the number by 2. If a number is evenly divisible by 2 with no remainder (remainder is equal to zero), then it is even, otherwise, it is odd (remainder is not equal to zero). You can use the *math operation* block and change it to *remainder after division* in the mutation window (gear icon).
  ![Hint](../../images/book/learning-modules/lab2_pic1.png)
  - Use if statement to check if the remainder is equal to zero or not:
    - If remainder = 0 -> this is an even number.
    - If remainder ≠ 0 -> this is an odd number.
  - You may want to add comments to your code to make your code more readable, make code maintenance much easier, and help others better understand your code.

### Useful Resources
- [Propeller BlocklyProp Block Reference](https://learn.parallax.com/support/reference/propeller-blocklyprop-block-reference)
  - [Variable Blocks](https://learn.parallax.com/tutorials/language/blocklyprop/simple-blocklyprop-programs-propeller-boards/variable-blocks)
  - [Terminal Talk](https://learn.parallax.com/tutorials/language/blocklyprop/simple-blocklyprop-programs-propeller-boards/terminal-talk)
  - [Values and Math Blocks](https://learn.parallax.com/tutorials/language/blocklyprop/simple-blocklyprop-programs-propeller-boards/values-and-math-blocks)
  - [Making Decisions](https://learn.parallax.com/tutorials/language/blocklyprop/simple-blocklyprop-programs-propeller-boards/making-decisions)
  - [Blocks that Repeat](https://learn.parallax.com/tutorials/language/blocklyprop/simple-blocklyprop-programs-propeller-boards/blocks-repeat)
  - [Functions](https://learn.parallax.com/support/reference/propeller-blocklyprop-block-reference/functions)
