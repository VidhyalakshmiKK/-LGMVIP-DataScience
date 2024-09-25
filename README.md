## Image to Sketch using Python
This is a simple python code to convert an image to a sketch using OpenCV
### Process :
- **Load the image:** Use OpenCV to read the image from the file.

- **Convert the image to grayscale:** Convert the image to a grayscale image as the first step in the sketching process.

- **Invert the grayscale image:** Create a negative of the grayscale image by inverting the pixel values.

- **Apply Gaussian blur:** Use Gaussian blur to soften the inverted image. This helps create a smoother sketch effect.

- **Invert Blurred image:** Using bitwise_not invert the blurred image.

- **Sketch the image:** sketch the image by performing bit-wise division between the grayscale image and the inverted-blurred image.
