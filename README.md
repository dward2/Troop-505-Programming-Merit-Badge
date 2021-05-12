# Troop 505 Programming Merit Badge

## Requirement 5a
With your counselor's approval, choose a sample program.  Modify the code or add a function or subroutine to it.  Debug and demonstrate the modified program to your counselor.

For this requirement, you are going to make additions to a Text Adventure game written in C# using the GDB Online website.

1.  Visit https://onlinegdb.com/classroom/invite/j1c6LcSEZT
2.  Log in or create an account.  Then, visit the Text Adventure assignment in the Classroom.  
3.  If you cannot make an account, visit https://onlinegdb.com/S1OMnstuO instead.  You will then need to make a copy (or "fork") that code in order to edit your own.
4.  Make the following changes to the code:
  - Allow the user to type "Q" in the main room to quit the program.  The statement to end the program is `System.Environment.Exit(0);`.
  - Add code for the East and West rooms.  Have an action in one room impact what happens in another room.

When you are finished, "submit" your code if you logged in to the Classroom.  If you didn't log in, either e-mail me a copy of your code or "share" your code and sending me the link.  Also, demonstrate and explain your code to me on Zoom.
  
## Requirement 5b
With your counselor's approval, choose a second programming languate and development environment, different from those used for requirement 5a and in a different industry from 5a.  Then write, debug, and demonstrate a functioning program to your counselor, using that language and environment.

For this requirement, you are going to write a Python program to create a drawing using Turtle Graphics.

1. Visit <https://trinket.io/turtle>.
2. Erase the existing code
3. Write a program to create a drawing of your choice.  Ideas include:
    + Draw your name with the turtle (not the text functionality)
    + Draw a house with the turtle
    + Write functions to create generic shapes such as a circle, square, or triangle

When you are finished, e-mail me your code.  Then, demonstrate and explain your code to be on Zoom.

### Info
To create a turtle for drawing, enter the following lines of code:
```python
import turtle

t = turtle.Turtle()
```
The variable `t` is now used to control the turtle.  This variable name can be any name you like.

A full list of turtle commands can be found at <https://docs.python.org/3/library/turtle.html#turtle-methods>.  The most important are:

* `t.forward(#)` or `t.fd(#)` where `#` is the distance to move
* `t.backward(#)` or `t.bk(#)` where `#` is the distance to move
* `t.right(#)` or `t.rt(#)` where `#` is the degrees to turn
* `t.left(#)` or `t.lt(#)` where `#` is the degrees to turn
* `t.setheading(#)` where `#` is the heading, in degrees, in which to point the turtle
* `t.penup()`
* `t.pendown()`
* `t.pensize(#)` where `#` is the size of the pen

## Requirement 5c
With your counselor's approval, choose a third programming languate and development environment, different from those used for requirements 5a and 5b and in a different industry from 5a and 5b.  Then write, debug, and demonstrate a functioning program to your counselor, using that language and environment.

Create a webpage using HTML.  You edit and display your webpage in one of two ways:
1. Use the GDB debugger (https://www.onlinegdb.com/) and select "HTML,JS,CSS" as the language
2. Use any text editor on your computer, and then save the file with the file extension of `.html`.  Then, you can open that file within a web browser to see it.

When you have created your HTML document, e-mail it to me and demonstrate it to me on Zoom.

### Basic elements
Paragraph
```html
<p>This is what you want to show.</p>
```
Heading
```html
<h1>Title of Section</h1>
```
Line Breaks
```html
<p>
  Here is something I am writing.  I now want a new line.<br>
  This will be on a new line.
</p>
```
Text Color
```html
<p style="color:red;">This text will be in red.</p>
```
Text Font
```html
<p style="font-family: verdana;">This will be in the Verdana font.</p>
```
Text Alignment
```html
<p style="text-align: center;">Centered text</p>
```
Text Size
```html
<p style="font-size: 160%;">This will be larger text</p>
```
Multiple styles:
```html
<p style="color: red; text-align: center;">This will be centered and red</p>
```

### Inputs and Outputs
Here is some example HTML for a form that allows you to type in your age and calculates how many days you have been alive.

```html
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Title</title>
  <script>
    var calculate_age_in_days = function() {
        var input_age, output_age, age_string, output_text;

        input_age = document.getElementById('input_age').value;

        output_age = input_age * 365;

        if (input_age >= 18) {
            age_string = "You are an adult."
        }
        else {
            age_string = "You are a minor."
        }

        output_text = "Your age in days is " + output_age + ". " + age_string

        document.getElementById("output_age").innerHTML = output_text;
    }
  </script>
</head>

<body>
  <p>Enter your information.</p>
  <label for="input_age">Enter your age:</label>
  <input type="text" id="input_age">
  <input type="button" value="Enter" onclick="calculate_age_in_days();">

  <p id="output_age"></p>

</body>
</html>
```


