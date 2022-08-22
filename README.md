# PyProject1

This is a basic Python project that allows one to detect the color of anything on a provided image. To make it, I used to regular importable libraries: cv2 and argparse, 
along with two pip-installable libraries: numpy and pandas. It also requires the usage of a csv file for referencing the name and values of each color. To use the project,
type in the terminal window "python colourDetection.py -i <image path>" and it works for any image you provide it with, both .png and .jpg . An example image has been provided.
While the program is running, double click anywhere on the image and, on the top of the screen, the name of the color of whatever you double-clicked will be displayed,
along with its RGB values. It will continue forever, until you hit the "escape" key. Since there are 256^3 = 16777216 different ways to express a color, there are lots
of colors that can be seen, each with different RGB values - no two colors' RGB values are exactly the same.
