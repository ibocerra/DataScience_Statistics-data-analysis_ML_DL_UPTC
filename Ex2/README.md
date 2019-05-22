# Exercise 2 - Azure ML

According the Exercise 1 we are going to apply the same linear regression algorithm with the iceCream dataset using Azure ML studio


### Prerequisites

```

   1) Azure Machine Learning Studio account
   2) Sample csv data. 


```

#### Step #1: Login and load Dataset into AZURE-ML

Log in Azure-ML account then go to Dataset and click on new, browse your dataset file and upload our Excel or CSV file. We are going to use this dataset as a training model

![](https://raw.githubusercontent.com/lcarcamo1526/Machine-Learning-UPTC/master/Ex2/Gif/1.gif)

#### Step #2: Create new experiment and load data

Click on Experiment, create a new experiment and choose blank template, then go to left bar and select saved data and drag and drop to the map the data set, or simply double-click in Icecream.csv then select IceCream at the main window and choose to visualize data.


![](https://raw.githubusercontent.com/lcarcamo1526/Machine-Learning-UPTC/master/Ex2/Gif/2.gif)

We can find descriptive statistics information like pandas.describe() method and see a linear data relation between Revenues and Temperature.

![](https://i.ibb.co/cx0XsJz/Screenshot-2019-05-22-Experiments-Microsoft-Azure-Machine-Learning-Studio.png)

#### Step #3: Split data

After confirm the linear relation between these two variables we need split data for training and testing purpose.
In the left bar we search for "split data" and drag and drop to main window, then click on Ice cream data and drag a relation to Split data, finally we divide the data into 3/4 (Training) and 1/4 (Testing)

![](https://raw.githubusercontent.com/lcarcamo1526/Machine-Learning-UPTC/master/Ex2/Gif/3.gif)

![](https://i.ibb.co/4ZtMhDy/Screenshot-2019-05-22-Experiments-Microsoft-Azure-Machine-Learning-Studio-1.png)

#### Step #4: Train model

After split data we need choose and train our model, in this case is clearly Lineal regression model, to do that find in the left bar "Train model" and "Linear regression" and add to the main window.

![](https://raw.githubusercontent.com/lcarcamo1526/Machine-Learning-UPTC/master/Ex2/Gif/4.gif)

To train our model we need a dependable value, in this case es Revenue column, to add this column in your model, click in the train model section, and launch column selector, after that add a new rule choose the column name that we wanna predict, in this case Revenue.

After that add a "score model" and "Model evaluator" components to main window and connect the test dataset (The 1/4 splitted from the original data set) to model score, then add a relation with model evaluator, the click run or F5. 

![](https://raw.githubusercontent.com/lcarcamo1526/Machine-Learning-UPTC/master/Ex2/Gif/5.gif)

## Authors
 
 * *Ibo Cerra* 
 * *Luis Carcamo*  - [lcarcamo1526](https://github.com/lcarcamo1526)


## License

This project is licensed under the MIT License 

