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
	num_images_per_class = 70	
	num_train_per_class = 50	
	num_val_per_class = 10
	img_size = 64
	batch_size = 8
	num_classes = 8
	learning_rate = 0.0001
	num_epoch = 30


	There is a class for CNN model in PART1_1.ipynb and PART1_2.ipynb to build from scratch. 
	
	def train_val(model) and def train_one_epoch(model) function are used for training & validation model and to get list of train_loss, train_acc, val_loss , val_acc and  best_models[-1] . These functions are also used in three files.

	The first and second files contain def plot(list1,list2,title,name,type) function. This function plots the training and validation results using lists coming from train_val(model). Also, it saves the plots in current directory with the "name" argument. "type" is written to y-axis.

	
	







