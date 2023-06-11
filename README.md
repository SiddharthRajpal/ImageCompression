# Pillow Image to Text Converter

This script converts an image into a text file using the Python Imaging Library (Pillow). Each pixel's coordinates and RGB values are written to a text file.

## Prerequisites

- Python 3.x
- Pillow library (install using `pip install pillow`)

## Usage

1. Ensure that the image you want to convert is in the same directory as the script.
2. Rename the image file to `img.png` (or modify the script to use a different filename).
3. Run the script using a Python interpreter.

## Output

The script creates a text file named `text.txt` in the same directory as the script. Each line in the text file represents a pixel in the image and contains the pixel's coordinates (x, y) and its RGB values.

## Example

If you have an image with dimensions 500x500, the resulting text file will contain 250,000 lines, each representing a pixel in the image. Here's an example of how the contents of the `text.txt` file might look:

0,0,(255, 255, 255)
0,1,(255, 255, 255)
0,2,(255, 255, 255)
...
499,498,(0, 0, 0)
499,499,(0, 0, 0)


## Limitations

- This script assumes that the image file is in PNG format. Modify the script accordingly if you are using a different image format.
- For large images, the resulting text file can be quite large and may take up a significant amount of disk space.

Feel free to modify the script to suit your specific requirements or to extend its functionality.

**Note:** Make sure to handle any exceptions or errors that may occur during the execution of the script for robustness.
