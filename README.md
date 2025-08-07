# Fractal Zoomer

## Introduction

**Fractal Zoomer** is an interactive application that allows users to explore fractals, originally focusing on the Mandelbrot Set. The application supports infinite zoom, real-time rendering, and advanced customization. Designed with web technologies, it delivers a responsive and immersive fractal exploration experience. As part of an advanced software engineering project, it now includes support for multiple fractal types, movement across the 2D plane, user-configurable parameters, and image export capabilities.

## Features

- **Infinite Zoom**: Zoom infinitely into fractals to reveal intricate and endless patterns.
- **Interactive Navigation**: Navigate through zoom and pan functionalities to explore different areas of the fractal space.
- **Real-Time Rendering**: Dynamically renders fractals in real time for a smooth and interactive user experience.
- **Multiple Fractal Types**: Explore at least three types of fractals, including:
  - **Mandelbrot Set**
  - **Julia Sets**
  - **Burning Ship Fractal** (or other custom types)
- **Parameter Customization**: Set parameters for each fractal type directly from the UI.
  - Mandelbrot: adjust the complex constant `c`
  - Julia: select or modify the complex function used
- **Customizable Visual Settings**: Change color schemes, zoom speed, and other display options.
- **Image Export**: Save the current fractal view as an image using a file dialog to choose the name and location.
- **2D Movement Support**: Move around the fractal in the 2D plane, not just zooming, for better exploration.

## Requirements

To run the fractal generation code, make sure you have the following Python libraries installed:

```bash
pip install matplotlib numpy
