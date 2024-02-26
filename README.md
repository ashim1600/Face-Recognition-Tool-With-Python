## Face Recognition Command-Line Tool
> This Project guides you through building a face recognition command-line tool using Python. It covers various techniques, including face detection, face recognition, and incorporating command-line arguments for user interaction.

## Project Overview
The project is structured into several steps, including:

> Environment setup
 Data preparation
 Model training
 Face recognition
 Result display
 Model validation
 Prerequisites
 To undertake this project, you should have:

### An intermediate-level understanding of Python
> Familiarity with installing third-party modules using pip
Knowledge of modules like argparse, pathlib, and pickle
Dependencies
The project utilizes the following third-party libraries:

> dlib
face-recognition
numpy
Pillow
Key Tasks
Key tasks within face recognition include:

### Detecting faces in images
> Generating encodings for faces
Comparing unknown faces with known encodings
Storing encodings on disk to avoid redundant computation
Functions
## Two main functions are developed:

recognize_faces(): Identifies faces in unlabeled images using pre-loaded encodings.
_recognize_face(): Compares unknown encodings with pre-loaded encodings to determine the most likely match.
Result Presentation
Results are presented by:

## Drawing bounding boxes around recognized faces
> Annotating them with names on the input image using the Pillow library
Model Validation
The tutorial concludes by introducing model validation techniques to assess the trained model's performance on new data. It includes the use of the argparse module to create a command-line interface for the script, enabling users to execute tasks like training, validation, and testing.

## Further Extensions
Suggestions for further project extension include:

## Incorporating video processing
> Updating training data
Implementing a portable security camera solution
use this in read me.md file format with bullets and headings and subheadings

