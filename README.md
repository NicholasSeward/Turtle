# Turtle
This page is dedicated to a custom Java class for drawing [turtle graphics](https://en.wikipedia.org/wiki/Turtle_graphics).  Turtle allows you to draw 2D graphics by telling a turtle what to do.  The turtle can turn and travel forwards and backwards.  You can also raise and lower the tail of the turtle to control whether it draws or not.  Complex drawings can be made with very little code.  Check out the code for the image at the bottom of the page.  

[Documentation](https://sites.google.com/a/asmsa.org/java-turtle/turtle-documentation-api)
[Tutorial](https://en.wikipedia.org/wiki/Turtle_graphics)
[Lessons](https://sites.google.com/a/asmsa.org/java-turtle/tutorial)

![Square Spiral](squareSpiral.png)

SquareSpiral.java
```
public class SquareSpiral
{
    public static void main(String[] args) 
    {
        Turtle bob = new Turtle();
        for(int i=0;i<360;i++)
        {
            bob.forward(i*1.25);
            bob.left(90.25);
        }
    }
}
```
[![Sample Instruction](https://img.youtube.com/vi/Q84fbxt48OI/0.jpg)](https://www.youtube.com/watch?v=Q84fbxt48OI)
