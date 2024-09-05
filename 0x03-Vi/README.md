# Another text editor

After **Emacs**, it’s time to play with **Vi**.

# Resources

**Read or watch:**

- [Basic vi Commands](https://www.cs.colostate.edu/helpdocs/vi.html)

# Learning Objectives
At the end of this project, you are expected to be able to [explain to anyone](https://fs.blog/feynman-technique/), **without the help of Google:**

## General
- What is vi
- Who is Bill Joy
- How to start and exit vi
- What are the command and insert modes, and how to switch from one to the other
- How to edit text
- How to cut and paste lines
- How to search forward and backward
- How to undo
- How to quit vi

## Requirements
- All tasks **must be** done inside the sandbox `Ubuntu 20.04`
- Your sandbox **must be available at the end of this project** - the Checker will access to it just after the deadline to run the correction!
- The answer of a task must be in a specific file
- Each answer file must contain only the command to execute in Emacs for solving the task. Example: “What is the command to quit without saving changes?” -> the file should contain only `:q!`

## Quiz questions

### Question #0

Vi is included with almost every Linux distribution.

- [ ] False

- [ ] True

### Question #1

How do you quit Vi?

- [] `:q<Return>`

- `<ESC>`

- `q`

### Question #2

How do you enter Command Mode in Vi?

- `Ctrl / Command + C`

- `<ESC>`

- `<Return>`

### Question #3

How do you enter Insert Mode in Vi?

- `<Insert>`

- `<Return>`

- `i`

## Tasks

### 0. Create your answer directory

Navigate to `/root` and create a directory named `0x03_vi`

### 1. Inserting

What is the command to insert text before the cursor?

Write the answer into the file `/root/0x03_vi/inserting`.

You can validate if the format of your answer is correct by displaying the file information:

```bash
root@hex:~# ls -l /root/0x03_vi/inserting
-rw-r--r-- 1 root root 2 Nov 11 04:34 /root/0x03_vi/inserting
root@hex:~#
```

### 2. Cutting

What is the command to delete and cut the current line?

Write the answer into the file `/root/0x03_vi/cutting`.

Tips:

How to Copy, Cut and Paste

### 3. Pasting

What is the command to paste the lines in the buffer into the text after the current line?

Write the answer into the file `/root/0x03_vi/pasting`.

### 4. Undoing

What is the command to undo what you just did?

Write the answer into the file `/root/0x03_vi/undoing`.

#### 5. Exiting

What is the command to quit vi even though latest changes have not been saved for this vi call?

Write the answer into the file `/root/0x03_vi/exiting`.

### 6. Beginning of the line

What is the command to move the cursor to the start of the current line?

Write the answer into the file `/root/0x03_vi/beginning_of_the_line`.

### 7. End of the line

What is the command to move the cursor to the end of the line?

Write the answer into the file `/root/0x03_vi/end_of_the_line`.
