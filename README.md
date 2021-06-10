1) Once you have extracted the zip load the project or run the main.py file which is the executing file 
 * it is good to note here that the dataset folder 'fer2013' has been removed from the zip because it increases the size of the file
  dramatically, so you will have to take the folder and paste it inside \Deep_Learning_CNNs\DeepLearning-based-on-CNNs

2) After the execution the project will ask you to give a name so it can save the experiments that will be made in a new file

3) The project inside is calling the constructor of an model from the architectures, so if you want to change architecture
  you have to change function on the 84th line of the code

4) The model has a callback so it's saving everytime the best model according to the val_accuracy in a folder called model_checkpoint

5)  Finally the code runs the model.fit and then we are printing the model scores, plotting the value of loss & accuracy and in the
    end we are plotting a figure with some filters represantation from the layer weights and we have a for loop for the first 10
    images with the actual labels and the ones that our model predicts.

* If you want to change architecture you should edit the architectures.py, otherwise for optimizers , learning rate and all the 
	other aspects, all of them are included to the main.py file.
