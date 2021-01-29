# Plant Disease Classification
This above is aimed to see how one can handle a simple machine learning project. The goal is to check what you can do with the layers of a custome CNN model. This project does not have a prediction function but only a model that can be trained and the accuracy is shown.

## Dataset
The dataset used for this project is the [PlantVillage](https://www.kaggle.com/emmarex/plantdisease) dataset from Kaggle. For the above model, the dataset was not completely used but rather only parts of it were used. The number of images used for the training and validation is around 6000 from the 20,000 images provided in the original dataset.

## Setting up the Dataset
- Separate the dataset into training and validation set and keep them in their respective folders.
- Each folder has labelled images of leaves from different plants so make sure both the training and validation set has those.
- Set up the root directory where your dataset is by changing the ```root_dir``` variable in the ```.py``` or ```.ipynb``` file.
- If you are running on Google Colab, mount your Google Drive by running the ```drive.mount``` cell, then copy and paste the key that is asked by allowing Colab to access your drive. Refresh the content bar on the left to find your drive accessible. Simply right on the directory, copy the path and paste it in the ```root_dir``` variable.

## Setting up the Virtual Environment (Optional)
Open command prompt and navigate to the where you want to clone the repository. Type in the following:
```
virtualenv {foldername}
```
Replace the foldername with your own and remove the curly braces. Once run, you should see a folder with the name given in the directory. Now place the files inside that folder, use command prompt to navigate inside the folder and then type in the following to activate the virtual environment.
```
Scripts\activate
```
## How to run
Install the dependencies from the requirements file. Type in the following:
```
pip install -r requirements.txt
```
Now, just compile the ```.py``` or ```.ipynb``` file and you are good to go. 

## Results
For the above model in the ```.ipynb``` file, the final accuracy measures are:
- Training accuracy = 44.85%
- Training loss = 17.32%
- Validation accuracy = 70.00%
- Validation loss = 12.79%

