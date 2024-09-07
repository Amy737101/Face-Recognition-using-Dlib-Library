# Face Recognition Using Dlib library

## Make sure to install all the dependencies library given in the requirement.txt file

1] In the python codes, I have used the face_recognition library (a popular Python package for face recognition tasks, primarily relies on a deep learning model called dlib for face detection and facial feature extraction). Dlib uses a custom face recognition pre-trained model trained on a combination of the Histogram of Oriented Gradients (HOG) feature descriptor and a linear SVM (Support Vector Machine) classifier. This model has an accuracy of 99.38% on the labeled faces in the wild benchmark.

2] The model detects the face and records the date&time along with the percentage matched in the Excel file.

3] Also, the model needs just one photo to get trained to detect a person hence its easy to implement and takes less processing time.

4] The model also displays a message "This person is already in the list" if a person was already detected by the face_recognition system.
