# Face-Recognition
A deep learning CNN application inspired by the VGG_Face architecture

There are two notebooks available.
The Extract_Faces.ipynb can be used to collect face image dataset either from live webcam or from a video which can be later used to train our model.

The second notebook FaceRecognition_VGG_Face.ipynb can be used to make our own face recognition model.
The model is first defined with the VGG_Face architecture. We used the pretrained VGG model for this. Then our own custom network of FC Layers is added to the model.
The model is then trained yielding more than 90 percent validation accuracy.

The trained model is not uploaded. It can be trained using the notebooks given; it would not take more than 2 minutes to train the model(depends on the dataset).
