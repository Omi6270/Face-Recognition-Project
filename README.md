Face Recognition Project
Overview
This project is a face recognition system that identifies individuals based on stored images and their details. The project is built using Python, Google Colab, and OpenCV.

Key Features
Storage Integration: Stored images of individuals and their details are maintained in Google Drive.
Face Recognition: Users can upload an unknown photo, and the system will identify it if it matches a stored image.
Unknown Detection: If the uploaded photo does not match any stored image, the system will display "Unknown."
Tech Stack
Programming Language: Python
Platform: Google Colab
Libraries Used: OpenCV
Setup Instructions
Prepare the Environment:

Create an .ipynb file on Google Colab.
Upload all training images (stored images of individuals with their details) to Google Drive.
Run the Code:

Execute the first part of the code to load the training images.
In the second part, upload the unknown photo for recognition.
Results:

If the uploaded photo matches a stored image, the details of the individual will be displayed.
If there’s no match, the system will label the image as "Unknown."
Usage
Input:

Training images: Stored in Google Drive with corresponding details.
Unknown photo: Uploaded by the user during runtime.
Output:

Displayed information about the matched individual.
If no match is found, the output will indicate "Unknown."
