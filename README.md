[![N|Solid](https://google.github.io/cartoonset/images/cs100279640926771550.png)](https://google.github.io/cartoonset/images/cs100279640926771550.png)
# Python Image Cartoonifier !
[~ By Mayuresh Patil]()

A python application that will transform an image into its cartoon using OpenCV.

Step 1: Importing the required modules

 - We will import the following modules:
    - CV2: Imported to use OpenCV for image processing
    - easygui: Imported to open a file box. It allows us to select any file from our system.
    - Numpy: Images are stored and processed as numbers. These are taken as arrays. We use NumPy to deal with arrays.
    - Imageio: Used to read the file which is chosen by file box using a path.
    - Matplotlib: This library is used for visualization and plotting. Thus, it is imported to form the plot of images.
    - OS: For OS interaction. Here, to read the path and save images to that path.

## Explanation:

Imread is a method in cv2 which is used to store images in the form of numbers. This helps us to perform operations according to our needs. The image is read as a numpy array, in which cell values depict R, G, and B values of a pixel.

## Beginning with image transformations:

To convert an image to a cartoon, multiple transformations are done. Firstly, an image is converted to a Grayscale image. Yes, similar to the old day’s pictures.! Then, the Grayscale image is smoothened, and we try to extract the edges in the image. Finally, we form a color image and mask it with edges. This creates a beautiful cartoon image with edges and lightened color of the original image.

Let’s start with these transformations to convert an image to its cartoon image. Cartoon effect has two specialties:

1) Highlighted Edges
2) Smooth colors

In this step, we will work on the first specialty. Here, we will try to retrieve the edges and highlight them. This is attained by the adaptive thresholding technique. The threshold value is the mean of the neighborhood pixel values area minus the constant C. C is a constant that is subtracted from the mean or weighted sum of the neighborhood pixels. Thresh_binary is the type of threshold applied, and the remaining parameters determine the block size.
## Installation

Here are the 5 steps to create a chatbot in Python from scratch:

1) Import and load the data file
2) Preprocess data
3) Create training and testing data
4) Build the model
5) Predict the response

## Run the cartoonifier

```
python MasterTask_Cartoonifier
```
