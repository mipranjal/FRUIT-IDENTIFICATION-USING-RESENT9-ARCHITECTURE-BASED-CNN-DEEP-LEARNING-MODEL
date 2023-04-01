# **Fruit Identification using ResNet9 Architecture Based CNN Deep Learning Model**

<img src="https://user-images.githubusercontent.com/110101325/229269013-8374b23b-db50-4b1c-abf8-b1d8188826e8.png">



This code implements a deep learning model based on ResNet9 architecture to identify fruits from images. Fruits are an important source of nutrients and fiber in our diets, and it is essential to identify them correctly for people with specific dietary requirements.

The model is trained on the Fruits 360 dataset, which is a large and extensive dataset containing 131 categories of fruits and vegetables. The dataset includes images of fruits like Apples, Apricots, Avocados, Bananas, Blueberries, Cactus fruit, Cantaloupes, Cherries, Chestnuts, Clementines, Corn, Cucumbers, Dates, Eggplants, Figs, Ginger Root, Grapefruits, Grapes, Guavas, Hazelnuts, Huckleberries, Kiwis, Lemons, Limes, Lychees, Mandarines, Mangoes, Mangostans, Melons, Mulberries, Nectarines, Onions, Oranges, Papayas, Passion fruits, Peaches, Pears, Peppers, Pineapples, Plums, Pomegranates, Potatoes, Quinces, Rambutans, Raspberries, Redcurrants, Salaks, Strawberries, Tamarillos, Tangelos, Tomatoes, Walnuts, and Watermelons.

## Dependencies
* Python 3.6 or above
* PyTorch
* torchvision
* numpy
* matplotlib
* Dataset

The dataset used in this code can be downloaded from Kaggle using the following link: https://www.kaggle.com/moltean/fruits

The dataset consists of 90,483 images divided into a training set of 67,692 images and a test set of 22,688 images. The dataset contains images of 131 categories of fruits and vegetables.

## Model Architecture
The deep learning model is based on ResNet9 architecture and is implemented using PyTorch. The ResNet9 model is a small version of the ResNet architecture, which has shown to be effective in image classification tasks.

## Usage
Install the dependencies using pip or conda.
Download the dataset from Kaggle.
Extract the dataset and update the dataset_path variable in the code to point to the dataset directory.
Run the code.
The code will train the model on the training set and evaluate the model on the test set. It will also display the images from the test set along with the predicted labels.


