# Assignment9

Name: Divya Pothuru 
NetworkId:DXP62920

VIDEO-LINK:

1. Add one more hidden layer to autoencoder
In this code first we have executed the code which was given then we have added some hidden layers in encode(the encoded representation of the input) and in decode(the lossy reconstruction of the input) and this model plots an input to its reconstruction and also the encoder for its encoded representation and then compiling the model and loading the MNIST dataset after that normalize and flatten the data then train the autoencoder.
<img width="788" alt="image" src="https://user-images.githubusercontent.com/122486644/230260607-2aeaf6c8-d384-402c-b911-e21dd0d91550.png">


2. Do the prediction on the test data and then visualize one of the reconstructed version of that test data.
Also, visualize the same test data before reconstruction using Matplotlib

for this we are using the matplotlib lib and then getting the reconstructed images for the test set. And choose a random image from the test set based on the index of the image to be plotted then plotting the orginal image as well as plotting the reconstructed image by using an imshow() function.
<img width="841" alt="image" src="https://user-images.githubusercontent.com/122486644/230261655-0b97ac62-2c51-4b07-bd10-b6fee0497bb7.png">



3. Repeat the question 2 on the denoisening autoencoder
Here we are repeating the step 2 which we have done for autoencoder,in this first we have executed the code which is given and then added few lines like plotting the orginal noisy and reconstructed image by getting the recostructed images for the test set and then choosing a random image from the test set.
<img width="902" alt="image" src="https://user-images.githubusercontent.com/122486644/230262173-98946f22-edd3-4f27-b26e-e207aecad561.png">


4. plot loss and accuracy using the history object.
Importing the matplotlib, here we are training the autoencoder by using the autoencoder.fit() function and then plotting the both loss and accuracy by using the plot() function by declaring the title, xlabel, ylabel functions we are displaying the graphs of both loss and accuracy.
<img width="877" alt="image" src="https://user-images.githubusercontent.com/122486644/230262766-5a285968-5c84-432a-b051-3f9547276e09.png">
<img width="572" alt="image" src="https://user-images.githubusercontent.com/122486644/230262804-0a36dfc9-2be7-4915-89c4-48b00017bbc7.png">
<img width="636" alt="image" src="https://user-images.githubusercontent.com/122486644/230262844-a31df43e-7fe8-4fbb-9369-83931c970c5e.png">
