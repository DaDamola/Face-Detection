# Face Detection

This repo contains a face detection program developed in Python. It uses a trained Haar feature-based cascade classifier to detect several faces in an image with OpenCV. It draws 2D bounding boxes around the faces. The classifier determines whether a face exists or not in an image; it's trained on a large dataset of images with faces and without faces. It extracts features from the image represented by values; these values indicate traits a face would have. They are grouped to make different stages of the classifier. An image that passes through all the stages of the classifier has a face in it. 

