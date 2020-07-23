#  CSS GRID
- Display Grid 
- Grid Columns and Grid Rows
    - Syntax - grid-column-start: 3;
    - Syntax - grid-column-end:


## Character classes
    .	any character except newline
    \w\d\s	word, digit, whitespace
    \W\D\S	not word, digit, whitespace
    [abc]	any of a, b, or c
    [^abc]	not a, b, or c
    [a-g]	character between a & g
### Anchors
    ^abc$	start / end of the string
    \b\B	word, not-word boundary
#### Escaped characters
    \.\*\\	escaped special characters
    \t\n\r	tab, linefeed, carriage return
##### Groups & Lookaround
    (abc)	capture group
    \1	backreference to group #1
    (?:abc)	non-capturing group
    (?=abc)	positive lookahead
    (?!abc)	negative lookahead
    Quantifiers & Alternation
    a*a+a?	0 or more, 1 or more, 0 or 1
    a{5}a{2,}	exactly five, two or more
    a{1,3}	between one & three
    a+?a{2,}?	match as few as possible
    ab|cd	match ab or cd

- When I was learning CSS and HTML the way that I learnt best was by copying layouts written by others and then changing bits, deleting bits and playing around with them until I understood what was going on. With that in mind, I’ve composed a few common responsive website layouts for you to copy, edit, mess around with. I’ll go over my thinking with each layout and will outline a few tricks from each one. (NB, you may have noticed that I’m not a designer, so I hope you like cats!). I’ve moved the CSS in each demo that is relevant to the layout up to the top of the CSS file in comment blocks so that you can see the important parts easily, don’t write your CSS like this.