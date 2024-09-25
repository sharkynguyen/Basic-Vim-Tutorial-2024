# Basic Editing in Vim

## 1. Introduction to Editing in Vim

Vim has several modes, but the most common for editing text are **Normal Mode** and **Insert Mode**. Understanding how to switch between these modes is essential for effective editing.

## 2. Switching to Insert Mode

To start editing text, switch to Insert Mode from Normal Mode:

- Press `i` to insert text before the cursor.
- Press `I` to insert text at the beginning of the line.
- Press `a` to append text after the cursor.
- Press `A` to append text at the end of the line.
- Press `o` to open a new line below the current line.
- Press `O` to open a new line above the current line.

To return to Normal Mode, press `Esc`.

## 3. Deleting Text

In Normal Mode, you can delete text using the following commands:

- `x`: Delete the character under the cursor.
- `dw`: Delete the word from the cursor to the end of the word.
- `dd`: Delete the entire line.
- `d3d`: Delete three lines starting from the current line.

## 4. Copying and Pasting Text

You can copy and paste text in Normal Mode:

- `yy`: Yank (copy) the current line.
- `y3y`: Yank three lines starting from the current line.
- `p`: Paste after the cursor.
- `P`: Paste before the cursor.

## 5. Saving and Quitting

To save your changes and quit Vim, use:

- `:w`: Save the file.
- `:q`: Quit Vim.
- `:wq`: Save and exit.
- `:q!`: Quit without saving.

## 6. Conclusion

These basic editing commands in Vim will help you navigate and manipulate text efficiently. Practice these commands to become more comfortable with Vim's editing capabilities.
