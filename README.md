# CNN_Model

In neural networks, Convolutional neural network (ConvNets or CNNs) is one of the main categories to do images recognition, images classifications. Objects detections, recognition faces etc., are some of the areas where CNNs are widely used.Computers sees an input image as array of pixels and it depends on the image resolution. Based on the image resolution, it will see h x w x d( h = Height, w = Width, d = Dimension ). Eg., An image of 6 x 6 x 3 array of matrix of RGB (3 refers to RGB values) and an image of 4 x 4 x 1 array of matrix of grayscale image.

# Working of CNN Model
Convolution is the first layer to extract features from an input image. Convolution preserves the relationship between pixels by learning image features using small squares of input data. It is a mathematical operation that takes two inputs such as image matrix and a filter or kernel.Then the convolution of 5 x 5 image matrix multiplies with 3 x 3 filter matrix which is called “Feature Map” Convolution of an image with different filters can perform operations such as edge detection, blur and sharpen by applying filters

# Working of Model
 Design a model for predict the 4 major type of dataset in the world of image classifcation that is CIFAR10/100 , MINST  with optimize accuracy and better result.
 
 Provide input image into convolution layer
Choose parameters, apply filters with strides, padding if requires. 
Perform convolution on the image and apply ReLU activation to the matrix.
Perform pooling to reduce dimensionality size
Add as many convolutional layers until satisfied
Flatten the output and feed into a fully connected layer (FC Layer)
Output the class using an activation function (Logistic Regression with cost functions) and classifies images.
