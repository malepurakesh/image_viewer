## Idea:
This repo is to practice the C & C++. 

The Idea of this project is to view the images and see one after another by pressing arrow keys. 

Steps:

1. Open the App.
2. Provide the directory name which contains Pictures (C:\Users\rakesh\Pictures or /usr/rakesh/Pictures).
3. The application will start displaying the images.
4. Using arrow keys change the images.

The application source can work on both the platforms (Ubuntu & Windows)

The application binary will be generated using cmake files.
 
## Planning 

1. Main Function (main.cpp)
       This function will show the cli for input path of images.
2. Create Object for a class. (singleton)
        -> (arrow key) next image
        <- (arrow key) previous image. If it is first image, no action.
        x close the application.
        

## Requirements:

1. Main function 
      * it needs APIs for taking input of string / browse path. and validating the image path.
      * throwing error message if the path is incorrect / there are no images.
2. Class Object

      * APIs to read and hold file names and display images based on Keys.

## Compilation 

The compilation and generating the application binary will be done using CMake file. 
