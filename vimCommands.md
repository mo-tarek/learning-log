Here’s a comprehensive list of 100 essential Vim commands to help you navigate and use Vim more effectively:

### Basic Navigation
1. `h` - Move left
2. `j` - Move down
3. `k` - Move up
4. `l` - Move right
5. `0` - Move to the beginning of the line
6. `$` - Move to the end of the line
7. `gg` - Go to the beginning of the file
8. `G` - Go to the end of the file
9. `w` - Move to the next word
10. `b` - Move to the previous word
11. `e` - Move to the end of the current word

### Inserting Text
12. `i` - Insert before the cursor
13. `I` - Insert at the beginning of the line
14. `a` - Append after the cursor
15. `A` - Append at the end of the line
16. `o` - Open a new line below
17. `O` - Open a new line above

### Deleting Text
18. `x` - Delete the character under the cursor
19. `dw` - Delete from the cursor to the end of the word
20. `d$` - Delete to the end of the line
21. `d0` - Delete to the beginning of the line
22. `dd` - Delete the entire line
23. `D` - Delete from the cursor to the end of the line

### Copying and Pasting
24. `yy` - Yank (copy) the entire line
25. `y$` - Yank from the cursor to the end of the line
26. `p` - Paste after the cursor
27. `P` - Paste before the cursor

### Undo and Redo
28. `u` - Undo the last change
29. `Ctrl + r` - Redo the last undone change

### Searching
30. `/pattern` - Search forward for "pattern"
31. `?pattern` - Search backward for "pattern"
32. `n` - Repeat the last search in the same direction
33. `N` - Repeat the last search in the opposite direction

### Replacing Text
34. `r` - Replace the character under the cursor
35. `R` - Enter replace mode
36. `:%s/old/new/g` - Replace all occurrences of "old" with "new" in the file

### Visual Mode
37. `v` - Enter visual mode (character-wise selection)
38. `V` - Enter visual line mode
39. `Ctrl + v` - Enter visual block mode
40. `y` - Yank selected text in visual mode
41. `d` - Delete selected text in visual mode

### File Management
42. `:w` - Save the current file
43. `:q` - Quit Vim
44. `:wq` - Save and quit
45. `:q!` - Quit without saving
46. `:e filename` - Open a file
47. `:saveas filename` - Save the current file as a new file
48. `:set number` - Show line numbers
49. `:set nonumber` - Hide line numbers

### Buffers and Windows
50. `:ls` - List all open buffers
51. `:bN` - Switch to buffer number N
52. `:split` - Split the window horizontally
53. `:vsplit` - Split the window vertically
54. `Ctrl + w, w` - Switch between windows
55. `Ctrl + w, q` - Close the current window

### Marks and Jumps
56. `m{a-z}` - Set a mark (e.g., `ma` sets mark 'a')
57. `'{mark}` - Jump to the beginning of a line with mark 'mark'
58. `` `mark `` - Jump to the exact position of mark 'mark'
59. `Ctrl + o` - Jump to the previous location
60. `Ctrl + i` - Jump to the next location

### Folding
61. `zf{motion}` - Create a fold with specified motion
62. `zo` - Open a fold
63. `zc` - Close a fold
64. `za` - Toggle a fold

### Macros
65. `q{register}` - Start recording a macro in register
66. `q` - Stop recording the macro
67. `@{register}` - Execute the macro stored in register

### External Commands
68. `:!command` - Execute an external command
69. `:r !command` - Read output of an external command into the file

### Command Mode
70. `:` - Enter command mode
71. `:history` - Show command history
72. `:set` - Show or change settings

### Indentation
73. `>>` - Indent the current line
74. `<<` - Unindent the current line
75. `=` - Re-indent the selected text

### Tab Management
76. `:tabnew` - Open a new tab
77. `:tabnext` - Go to the next tab
78. `:tabprev` - Go to the previous tab
79. `:tabclose` - Close the current tab

### Working with Text
80. `J` - Join the next line to the current line
81. `gq` - Format text (requires a motion)
82. `:set paste` - Disable auto-indentation and formatting
83. `:set nopaste` - Re-enable auto-indentation and formatting

### Miscellaneous
84. `Ctrl + f` - Scroll forward one page
85. `Ctrl + b` - Scroll backward one page
86. `Ctrl + d` - Scroll down half a page
87. `Ctrl + u` - Scroll up half a page
88. `:syntax on` - Enable syntax highlighting
89. `:syntax off` - Disable syntax highlighting
90. `:set relativenumber` - Show relative line numbers

### Plugins and Extensions
91. `:PlugInstall` - Install plugins (if using vim-plug)
92. `:PlugUpdate` - Update plugins
93. `:Help` - Open help documentation

### Customization
94. `:set background=dark` - Set background to dark
95. `:set background=light` - Set background to light
96. `:colorscheme scheme_name` - Change color scheme

### Closing and Exiting
97. `ZZ` - Save and quit
98. `ZQ` - Quit without saving
99. `:confirm q` - Confirm quit if there are unsaved changes

### Help
100. `:help` - Open the help system

These commands cover a wide range of functionalities in Vim, from basic navigation to more advanced features. Familiarizing yourself with these will significantly enhance your productivity in Vim!
