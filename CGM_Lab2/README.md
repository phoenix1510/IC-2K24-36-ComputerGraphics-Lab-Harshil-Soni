# CGM Lab Assignment 2 – DDA Line Drawing Algorithm

## Aim

To implement the DDA (Digital Differential Analyzer) Line Drawing Algorithm using C++ and the graphics.h graphics library.

## Description

The program:

- Accepts the starting point (x1, y1).
- Accepts the ending point (x2, y2).
- Calculates dx and dy.
- Calculates the required number of steps.
- Calculates the increments in the x and y directions.
- Plots the line pixel-by-pixel using `putpixel()`.

## DDA Algorithm

1. Calculate:
   - dx = x2 - x1
   - dy = y2 - y1

2. Calculate the number of steps:
   - steps = max(|dx|, |dy|)

3. Calculate the increments:
   - xIncrement = dx / steps
   - yIncrement = dy / steps

4. Initialize:
   - x = x1
   - y = y1

5. Repeat steps + 1 times:
   - Plot pixel(round(x), round(y)).
   - x = x + xIncrement.
   - y = y + yIncrement.

## Submitted By

**Harshil Soni**

**Lab - 02**

**IC-2K24-36**