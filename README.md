# End_to_End_Image_Classification_web_App-

what I used in this project :


1- Obtain the Data :

    Data is obtained in the form of images in a larger number for building the entire end to end web 
    application. The data is obtained from the open internet by scraping the images from the web. The 
    images captured need to be of a high resolution and can be slightly distorted. There can be some 
    amount of noise present in the images so that the algorithm is able to classify the images properly.
    We have used a CNN model dataset for classification between different images of cats and dogs
    from Kaggle

2- Data Preprocessing :

    The collected images need to be categorized and labelled to prepare the dataset.
    The images need to be resized to the same size. The images can be sharp with a high resolution as 
    well as a bit blurry and noisy. Transformation operations like translation, rotation and scaling 
    should be applied so that the images captured are present in all angles. Images can be distorted or 
    sheared so that it generalizes well. Introduce noise in the images if not present. A uniform 
    distribution of the number of images should be present in each of the classes.

3- Model Training :

    Once the dataset is ready, we rescale and assign categorical labels to images for each of the classes.
    For image classification and recognition, we will have to use neural networks. The convolutional 
    neural network architecture fits best for images as they work with matrices. Convolutional Neural 
    networks have different layers which aid in mathematical operations which are performed on 
    images. The layers include Convolution layer, Pooling layer, Flatten Layer, Activation functions 
    and the fully connected layers. We have used ReLU activation function for hidden layers and 
    softmax function for final output layer for multi class regression.
    We can see the model summary which would show all the layers and parameters fed.
    We divide the dataset into training and testing data and finally train the model for image 
    classification and save the model into a file. 

4- . Design the User Interface and Integrate the User Interface and Modelling :

    Once the model is ready to use, the web app is built and user interface is designed using Flask 
    which is simple to read and interpret in such a way that it fulfils the main objective of the 
    application.
    For web app, Flask to integrates the TensorFlow library and use the model weights for making the 
    right kind of prediction on the input image.
