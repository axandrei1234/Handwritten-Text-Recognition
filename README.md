# Handwritten-Text-Recognition
How To Run My Project

Steps

Step 1:
Open the following link.
https://colab.research.google.com/drive/116dT6ek81GOQiESxrTYAMdrLgZtPVqS9?usp=sharing

Step 2:
Because we are using CNNs you will need to set the runtime to GPU instead of CPU. 
 
Step 3:
Run the first cell (the cell with all the imports)

Step 4:
Drag into colab the dataset.zip folder and unzip it using the cell shown below 
Note: the cells that you can see above the ‘!unzip dataset.zip’ were used to preprocess the original images.

Step 5: 
You may proceed to execute all the cells below the command '!unzip dataset.zip,' with the exception of the last two cells in the application, specifically designed for conducting tests administered to both humans and the CNN.

Step 6:
To run the last cell you will need to drag the testSetProcessed.zip into colab and unzip it using the cell below 
 
After running the unzip cell you will be able to run the last cell that will predict the unlabeled images from that folder.
