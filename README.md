# Capture Photo using the device camera in Javascript


The Javascript logic is divided into 3 part:

- The basic setup

- Clear the photo

- Capturing the photo

## The Basic setup
The basic startup part which involves initialization of variables,
asking the user for permission to access the webcam, then start video streaming from webcam, getting references to all the HTML elements which we will be using in the Javascript code, etc.
Also adding a click event listener to the Take photo button.

## Clearing the Photo
In this, we collect the frames of the photo from the canvas and then convert it into a format like PNG or any other to show it in the HTML page.

## Capturing the Photo
This is the main part where we capture a frame from the video stream.
