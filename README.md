# Mandelbrot Set example

This project is a web-based Mandelbrot Set explorer built with vanilla JavaScript and HTML5 Canvas

## How It Works

The Mandelbrot Set is a mathematical set of points in the complex plane, the boundary of which forms a fractal. Here's a brief overview of how this application works:

1. **Rendering**: The Mandelbrot Set is rendered on an HTML canvas using JavaScript. For each pixel on the canvas, we perform the Mandelbrot Set algorithm to determine if the point is in the set.

2. **Mandelbrot Set Algorithm**: For each point c = x + yi in the complex plane:
   - Start with z = 0
   - Iterate z = z² + c
   - If |z| > 2, the point is not in the set
   - If |z| <= 2 after a set number of iterations, the point is considered to be in the set

3. **Coloring**: Points inside the set are colored black. Points outside the set are colored based on how quickly they escaped, using a randomly generated color palette.

4. **Infinite Zooming**: The application uses high-precision calculations to allow for deep zooming into the Mandelbrot Set. As you zoom in, the application recalculates the visible portion of the set with increased precision.

5. **Random Color Palettes**: Each time you click the "Randomize Colors" button, a new color palette is generated, giving a fresh look to the Mandelbrot Set visualization.



Enjoy exploring the depths and colors of the Mandelbrot Set :)
