# faceRec

Please check enviroment settings in the env_info.ipynb.


Face Recognition (FR) has been becoming one of the mostly debated topics in the machine learning, or more specifically, deep learning. It is well known, though maybe little out of date, convolutional neural network is perfectly suitable for the image-related problem. In this small project, we explored a range of ways to realize the single and multiple FR.

Our project is to develop an FR application that can detect the faces in the test photos and return the possibility of each label in the training photos. We have 5 persons in the training data, each 20 photos.

FR is usually done in two ways. One is to train a neural-network based model, preferably a ConvNet model, to classify the images. However, in terms of human faces, the vast compute and time resources with a great number of images is required to achieve a high enough accuracy. We do not have such a gigantic dataset. Thus, we opted the second approach in the end, transfer learning. Namely, we borrowed the results from some well-trained FR model.
