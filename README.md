# keras_anomaly_detection
CNN based autoencoder combined with kernel density estimation for colour image anomaly detection / novelty detection. 
Built using Tensforflow 2.0 and Keras.

The network was trained using the fruits 360 dataset but should work with any colour images.

The final model was able to detect 95% to 98% of anomalous images (depending on which class of images were treated as anomalous) with a false positive rate on 'normal' images of 12%.

Details of the project can be found here:
https://medium.com/@judewells/image-anomaly-detection-novelty-detection-using-convolutional-auto-encoders-in-keras-1c31321c10f2
