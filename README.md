# Expression_Recognition
Machine Learning Model for human expressions recognition and classification.

The content of this repository consists in a main program related to the creation and testing of a new model with the aim 
of predict the human expression of a face given. This model will differentiate between seven expressions (angry, disgust, happy, fear, sad, surprise and neutral).

The code consists on five phases:

1. Data Analysis and Extraction
2. Images Preprocessing
3. Model creation and Model training
4. Training Results Analysis
5. Testing with New Images


For the data extraction, its gonna be needed to upload images corresponding to each category mentioned, and its important to differentiate between train images and test images.
The structure to be followed is the one followed in this repository:

-Reduced_Dataset

    +train
        +angry
        +disgust
        +fear
        +happy
        +neutral
        +sad
        +surprise
    +test
        +angry
        +disgust
        +fear
        +happy
        +neutral
        +sad
        +surprise
   
In each directory, you must introduced the images you want to train or test the model. In my case, i've used the dataset from:    
https://www.kaggle.com/datasets/sulthankhan/facial-expression-recognition
