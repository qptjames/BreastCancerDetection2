Code for ECE 461P team 13: Breast Cancer Detection

Mini_DDSM_upload is the file for Breast Mammograms.
main.ipynb is the code for pre-processing, simple training, and image output.
dspMammogram.py is the code for the final training and CNN modeling.

How to run the code: 
1. Download Mini_DDSM_Upload onto local machine.
2. Change the data_dir variable in dspMammogram.py to the path of the downloaded Mini_DDSM.
3. Compile and run code


Notes:
In our code, we are using a pre-trained CNN model called DenseNet201. DenseNet201 is a deep convolutional neural network that was introduced in 2017. It is a powerful and efficient architecture for image classification tasks, featuring densely connected layers that enable feature reuse throughout the network. With its use of skip connections and feature concatenation, DenseNet201 is able to achieve state-of-the-art results on several benchmark datasets while requiring fewer parameters than other deep learning models. It has been widely adopted in various computer vision applications, such as object detection, segmentation, and image recognition.
