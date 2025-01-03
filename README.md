Face Recognition Project


Overview

This project is a face recognition system that identifies individuals based on stored images and their details. The project is built using Python, Google Colab, and OpenCV.

Key Features

1. Storage Integration: Stored images of individuals and their details are maintained in Google Drive.
2. Face Recognition: Users can upload an unknown photo, and the system will identify it if it matches a stored image.
3. Unknown Detection: If the uploaded photo does not match any stored image, the system will display "Unknown."
   
Tech Stack

1. Programming Language: Python
2. Platform: Google Colab
3. Libraries Used: OpenCV
   
Setup Instructions

1. Prepare the Environment:
Create an .ipynb file on Google Colab.
Upload all training images (stored images of individuals with their details) to Google Drive.

2. Run the Code:
Execute the first part of the code to load the training images.
In the second part, upload the unknown photo for recognition.

3. Results:
If the uploaded photo matches a stored image, the details of the individual will be displayed.
If there’s no match, the system will label the image as "Unknown."

Usage

1. Input:
Training images: Stored in Google Drive with corresponding details.
Unknown photo: Uploaded by the user during runtime.

2. Output:
Displayed information about the matched individual.
If no match is found, the output will indicate "Unknown."
