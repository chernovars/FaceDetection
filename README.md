# FaceDetection

I have trained a Haar-Cascade for face detection with 27 stages, using 600 positive face images and 1000 negetive images. This repository contains both positive and negetive samples, I used to train the cascade, also it contains a trained 'cascade.xml' file. 

In order to obtain best results set scaleFactor= 1.05 and minNeighbours= 5 in detectMultiScale function.
