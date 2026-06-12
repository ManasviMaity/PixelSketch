Overview:
PixelSketch is a Python-based image processing project that transforms ordinary photographs into realistic pencil sketches.
The project uses mathematical image transformations and pixel-level operations to create a sketch effect without relying on advanced computer vision frameworks.

Features:
Converts color images to grayscale
Applies image inversion and Gaussian blur
Uses dodge blending to generate sketch effects
Enhances contrast for improved visual quality
Displays original and sketch-rendered images side by side


Technologies Used:
Python
NumPy
Pillow (PIL)
Matplotlib

Project Workflow: 
Load the input image.
Convert the image to grayscale.
Invert the grayscale image.
Apply Gaussian Blur to the inverted image.
Perform dodge blending to create the pencil sketch effect.
Enhance contrast and adjust intensity levels.
Display the original image and the generated sketch.
