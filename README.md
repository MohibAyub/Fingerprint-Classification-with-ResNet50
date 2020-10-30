# Fingerprint-Classification-with-ResNet50
This project is based on image classification in which the deep learning model is trained using a Residual Neural Network to classify the fingerpints as one among the following categories: Arch (A), Left loop (L), Right loop (R), Whorl (W), Tented-Arch (T).<br/>
<br/>
Dataset used for testing and training purposes:  NIST Special Database 4, 8-Bit Gray Scale Images of Fingerprint Image Groups.<br/> (Link to the dataset given in description.)
<br/>
The dataset contains 4000 images labled as A, L, R, W, T ; 3200 images were used for training and 800 images were used for validation.<br/>
A 50-layer Residual Neural Network (ResNet50) was used to train the deep learning model and a softmax activation unit was included in the final layer to estimate the probabilities of the input image belonging to a specific class.<br/>
<br/>
Results of the training: Train accuracy: 91.1% , Validation Accuracy: 83-86%<br/>
<br/>
The trained model is saved into most commonly used .hd5 and .pkl formats ready to be deployed on a web server using AWS, Flask Web Framework etc.
