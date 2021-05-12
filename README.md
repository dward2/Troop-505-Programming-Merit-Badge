# Troop 505 Programming Merit Badge

## Requirement 5a
With your counselor's approval, choose a sample program.  Modify the code or add a function or subroutine to it.  Debug and demonstrate the modified program to your counselor.

For this requirement, you are going to make additions to a Text Adventure game written in C# using the GDB Online website.

1.  Visit https://onlinegdb.com/classroom/invite/j1c6LcSEZT
2.  Log in or create an account.  If you cannot make an account, visit https://onlinegdb.com/S1OMnstuO instead.  You will then need to make a copy (or "fork") that code in order to edit your own.
3.  Make the following changes to the code:
  - Allow the user to type "Q" in the main room to quit the program.  The statement to end the program is `System.Environment.Exit(0);`.
  - Add code for the East and West rooms.  Have an action in one room impact what happens in another room.
  
## Requirement 5b
With your counselor's approval, choose a second programming languate and development environment, different from those used for requirement 5a and in a different industry from 5a.  Then write, debug, and demonstrate a functioning program to your counselor, using that languate and environment.

For this requirement, you are going to write a Python program to create a drawing using Turtle Graphics.

1. Visit <https://trinket.io/turtle>.
2. Erase the existing code
3. Write a program to create a drawing of your choice.  Ideas include:
    + Draw your name with the turtle (not the text functionality)
    + Draw a house with the turtle
    + Write functions to create generic shapes such as a circle, square, or triangle

### Info
To create a turtle for drawing, enter the following lines of code:
```python
import turtle

t = turtle.Turtle()
```
The variable `t` is now used to control the turtle.  This variable name can be any name you like.

A full list of turtle commands can be found at <https://docs.python.org/3/library/turtle.html#turtle-methods>.  The most important are:

* t.forward(#) or t.fd(#)
* t.backward(#) or t.bk(#)
* t.right(#) or t.rt(#)
* t.left(#) or t.lt(#)
* t.setheading(#)
* t.penup()
* t.pendown()
* t.pensize(#)
