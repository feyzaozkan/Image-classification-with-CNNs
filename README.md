# Image-classification-with-CNNs
This project consists of 3 different .ipynb files which are PART1_1.ipynb, PART1_1.ipynb, PART2.ipynb.

-PART1_1.ipynb contains the CNN model without residual connections.

-PART1_2.ipynb contains the model with residual connection. 

-PART2.ipynb contains the Res-Net18 model and different fine-tuning processes.


Before starting implementation, dataset files should be added to google drive account.

All files can be implemented in Google colab just by running cells one by one. 




---------Some common properties of files------------

In each file; 

	After running first cells, google colab ask for permission to connect users' google drive account. To fetch the data set, it should be approved.

	After fetching data, automatically train,validation,and test directories are created to store data properly.

	These public variables should be updated according to needs.
	num_images_per_folder = 70  
	batch_size = 8
	num_classes = 8
	learning_rate = 0.0001
	num_epochs = 100

	There is a class for CNN model in PART1_1.ipynb and PART1_2.ipynb to build from scratch. 
	
	def train_validate(model) function is used to train and validate model and get est_accuracy,best_model,	train_accuracy_list,val_accuracy_list,train_loss_list,val_loss_list. That is also used in three files.

	The first and second files contain def plot(list1,list2,title,name,type) function. This function plots the training and validation results using lists coming from train_validate(model). Also, it saves the plots in current directory with the "name" argument. "type" is written to y-axis.

	
	








