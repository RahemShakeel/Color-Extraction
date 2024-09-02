# Color-Extraction
This Python project uses the turtle graphics library to create a grid of colored dots. The colors are defined in a list, and the turtle draws each dot in a grid pattern, creating an aesthetically pleasing visual effect.

## Overview
The code in this repository generates a pattern of dots using the turtle module. Each dot is colored randomly from a predefined list of RGB colors. The pattern is created in a grid format, where the turtle moves to a new position after drawing a set number of dots.

## Features
- Draws a grid of colored dots.
- Uses a predefined list of RGB colors.
- Customizable number of dots and dot size.
- Simple and effective use of the turtle graphics library.

## Prerequisites
To run this code, you need to have Python installed on your system. This project requires the turtle and random libraries, which are included with standard Python installations. Additionally, if you wish to use the commented-out code to extract colors from an image, you need to install the colorgram library.

## Code Explanation
- Imports: The code imports the turtle and random libraries. The colorgram library is used in the commented-out section for color extraction.
- Color List: A list of RGB tuples is used to specify the colors for the dots.
- Turtle Setup: Configures the turtle’s appearance and speed.
- Drawing Dots: Uses a loop to draw the grid of dots. The turtle moves to the next row after every 10 dots.
