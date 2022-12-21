# Mandelbrot Plotter

A program to plot a [Mandelbrot set](https://en.wikipedia.org/wiki/Mandelbrot_set), a fractal produced by iterating  a simple function on complex numbers. 

## Requirements
To run or compile the code, you'll need to have Rust installed. 
- [How to set up a Rust development environment?](https://www.rust-lang.org/learn/get-started)

Check here [Rust - Get Started]() for help on how to set up a Rust development enviroment.

## Usage
```
cargo run <file-name> <dimensions> <upper_left_bound> <lower_right_bounds>
```

Example:
```
target/release/mandelbrot mandel.png 4000x3000 -1.20,0.35 -1,0.20
```


For an example of the resulting image, check the [mandel.png](mandel.png) file.