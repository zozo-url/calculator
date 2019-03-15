
HTML
Create calculator class
    create id for the title
    create screen to display answer using input form tag, set id to answer
    Create 5 classes called "row"
        Create buttons within row classes

CSS
Set body + html classes with a width: 100% and a background colour
Stylise calculator class: width, height, background-colour, border, margin, text-align
Stylise title
Stylise the screen
Set row class to display:block
Create standard button style
Stylise AC and CE (Same as the standard button but with a different colour)
Increase height of tall + button

JAVASCRIPT
Create array variable "entries"
Create integer variable "total" and set to 0
Create string variable "temp" and set to ""
Create event listener that when you click a button the value of that button is set to variable "val"
Create If statement: If val is a number or the "." button, add it to the display
Create If statement: If you click the AC button, clear the display and display history (entries array, temp and total)
Create Else If statement: If you click the CE button, it clears the last entry (temp)
Create Else If statement: If val is equal to "x", push temp and "*" to entries array and clear temp string
Create Else If statement: If val is equal to divide button, push temp and "/" to entries array and clear temp
Create Else If statement: If val is equal to "=", push temp to entries array
Create variable "nt" that is set to the first value in the array
Create For loop that runs through the array
    Create variable "nextNum" that is set to the array value after current For loop array value
    Create variable "symbol" that is set to current For loop array value
        Create If statement: If symbol is equal to "+", plus and equal the first value (nt) to nextNum
        Create If statement: If symbol is equal to "-", minus and equal the first value (nt) to NextNum
        Etc 
        Etc
Create If statement: if nt is less than 0, add negative symbol the front of nt
Push answer to answer id
Set entries and temp to empty
Create Else statement: push number to the screen when it is pressed
