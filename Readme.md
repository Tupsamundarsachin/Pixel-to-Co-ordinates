

# Pixel to Coordinate Converter

## Purpose
This Python script converts pixel positions within an image to their corresponding x and y coordinates.



## Approach
1. **Load the Image**: The script uses OpenCV to load an image from the file path.
2. **Pixel to Coordinates Conversion**: The script converts the given pixel position to x and y coordinates, which are distances from                                       from the left edge (x-coordinate) and the top edge (y-coordinate) of the image.
3. **Display Image with Highlighted Pixel**: The script uses OpenCV and Matplotlib to display the image with a highlighted pixel position.




## Assumptions
- The image is in a standard format (e.g., JPG, PNG).
- The pixel positions are provided as tuples in the form (x, y).
- The script assumes the origin (0, 0) of the coordinate system is at the top-left corner of the image.




### How to Use

## Prerequisites
1. Ensure you have Python installed. You can download Python from [python.org](https://www.python.org/).
2. Install the required libraries:
    - OpenCV: For loading and processing images.
    - Matplotlib: For displaying images.
    - Pillow: For loading and processing images.
    
    Install the above libraries using the command  " pip install opencv-python matplotlib pillow"
    

## Steps
1. **Place Your Image**:
    - Put the image you want to process in the same directory as the script.

2. **Update the Script**:
    - Open the `pixel_Position.py` file.
    - Update the `image_path` variable with the path to your image file. For example:
    
    image_path = r"C:\Users\LENOVO\Downloadas\img2.jpeg"  but replace backslashes with forword slashes
    

3. **Run the Script**:
    - Execute the script from the command line:
    
    python pixel_Position.py
    

## Example
Given an image named `img2.jpeg` and a pixel position (400, 300), the script gives the output as:
                                                                                                  The pixel at position (400, 300) has coordinates (x=400, y=300)