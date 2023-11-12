# LeNet-Architecture-using-gray-scaled-images-vs-LeNet-Architecture-using-Colored-Images


![The-fifth-generation-of-LeNet-DCNN-architecture](https://github.com/sahar-hamdi/LeNet-Architecture-using-gray-scaled-images-vs-LeNet-Architecture-using-Colored-Images/assets/93557883/00669420-da97-41fa-89a5-77762f63b2d3)




-Load two common datasets  

-Use any needed pre-processing function to analyze dataset  

-Use LeNet-5 to complete the process of classification  

-Print LeNet-5 architecture 

-Print number of Trainable parameters in each layer  

-Print confusion matrix relative to testing samples  

-Print precision, recall, f1_score  

-Comment on your results








1- Import Libraries we will use

2- Load Datasets:

       -gray scaled images dataet (MNIST).
       -Colored images dataset (CFIAR-10).


3-Data Preproccesing :

     -Reshape taining and testing data.
     -Normalization of Training and Tetsing data.

4- Plot Figure for each Dataset.

5- Split the Training Dataset into train and Validation.

6- Build The LeNet-5 Architecture:

        -2 CNN Layers each layer has differnce filter size.
        - we used tanh acctivation function.
        -Average Pooling.
        -Flatten dataset.
        -Build 2   NN Layers with different number of neurons.
        -build the output NN Layer, we used softmax acctivation function.

7- Print The LeNet model

8- Model Training using Adam Optimizer and crossentropy as Loss Function.

9- iterate over layer to print the number of trainable parameters.

10- Print Confusion matrix relative to testing samples.

11- Calculate Precision, Recall.

![z5WJHm](https://github.com/sahar-hamdi/LeNet-Architecture-using-gray-scaled-images-vs-LeNet-Architecture-using-Colored-Images/assets/93557883/d8160042-3930-465c-ba37-c65d04ec786a)
call, and f1_score.




