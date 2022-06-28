Cataract Detection

A cataract is a clouding of the normally clear lens of the eye. For people who have cataracts, seeing through cloudy lenses is a bit like looking through a frosty or fogged-up window. Clouded vision caused by cataracts can make it more difficult to read, drive a car (especially at night) etc. A computer vision based model which is trained properly can help in detecting cataract, hence early detection and treatment of disease is possible

![image](https://user-images.githubusercontent.com/81282356/176218809-a98a7c1d-d07a-4fd9-b1a2-094dede534c5.png)


1) Data Collection 
        The dataset used in this project is collected from the open sources, git hub datasets, yahoo search and images taken by our own camera. The images include             camera taken images of eyes of Cataract and Normal eyed people and not medical images.

2) Data Pre-Processing 
        The images are augumented by using different methods [such as horizontal flip, rescaling, rotation, zoom_range, width shift, height shift, shearing, fill mode.

4) Training data with appropriate algorithm 
        To classify types of images, we used the 3 deep learning models. 

        (i) Convolutional Neural Network model

        (ii) Convolutional Neural Network with Recurrent Neural Network model

        (iii) VGG-16 model
        This model has 16 layers. The image is convoluted and pooled at each layer of the model. With the VGG16 model, the rural denizens will be able to determine             whether a person is suffering from cataract or not, without consulting an ophthalmologist. The output is then classified accordingly. The training accuracy in         this model is 91.91% and validation accuracy is 94.65%

5) Visualize the pattern using suitable graphs 
        Data visualization done in Microsoft Excel
        
6) Testing model's accuracy and implementing required changes 
        An image of the eye is taken on the spot and tested with the model. 
        
7) Deployment - Displaying the result
