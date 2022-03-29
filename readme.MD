#### Lab 5. Introduction to Classes and Objects.

#### Due Tuesday, April 6, start of class.

As usual, this lab will be graded according to specifications grading. To get full credit, 
push your version of the lab to your GitHub repo before the deadline.

In this lab, you'll get some practice creating objects and classes. 

1. We'll begin by creating classes for three basic shapes: Circle, Square and Rectangle. You can find these in shapes.py

2. Add constructors for each class. Circle should set a radius, Square a length, andRectangle an height and width.

3. Add a getArea() method for each class.

4. Let's make a test function which creates a list of objects and iterate through that. Ask each object to compute its area.

5. Add a Point class. It should have x and y as members. Add a constructor.

6. Now, let's add points to Circle, Square, Rectangle. Add a center to Circle, and a lowerLeftCorner to Square and Rectangle.

7. Add contains to Circle, Square, Rectangle. 

8. Add a perimeter() method to to each class. 

9. Equality and sameness. Two objects are the same if they occupy the same memory location. But they're equal if they have the same members. Let's add an equal method.

10. Add color as a member variable for shapes. Add:
    - A default value in the constructor
    - getters and setters.
    - Store the color internally as RGB values. The user should be able to provide the name of one of the 16 basic
    web colors (https://en.wikipedia.org/wiki/Web_colors) and your setter should use the RGB value.
    for example, if the user did setColor('white'), you should set the color member variable to FFFFFFF.
    If they call getColor and the value is one of the 16 web colors, return the name.
    So, if the color is set to FFFFFF, getColor() should return 'White'. If it's something like FFE01CB, just return the RGB code.
    

