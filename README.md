# Face detection with ML and Open CV

In order to build face recognition software, we have to use the built-in Haar cascade classifiers in OpenCV. Luckily these classifiers have already been pre-trained to recognize faces!

*images/* folder has several images for face detection. 

One can modify *scaleFactor* and *minNeighbors* parameters to fine tune the face detection technique.

run the command to test it

python detect_faces.py --face cascades/haarcascade_frontalface_default.xml --image images/obama.png
