# Processing-Library-For-OpenSimplexNoise
This repo is a processing library for open simplex noise. 

It also serves as a work-in progress library for additional noise algorithims in Processing.

There are currently implementations for:

[x] Open Simplex noise

[ ] Feel free to add your own noise algorithim here!


# API

// Create a noise object, optional 2nd argument for seed
OpenSimplexNoise generator = new OpenSimplexNoise(this);

// Get a noise value
float xoff = 0.3;
float val = generator.noise(xoff);
