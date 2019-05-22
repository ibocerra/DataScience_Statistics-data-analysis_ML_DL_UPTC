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

We can find describtive stadistics information like pandas.describe() method and see a linear data relation between Revenues and Temperature. 

![](https://i.ibb.co/cx0XsJz/Screenshot-2019-05-22-Experiments-Microsoft-Azure-Machine-Learning-Studio.png)

#### Step #3: Split data

After confirm the linear relation between these two variables we need split data for training and testing purpose


## Authors
 
 * *Ibo Cerra* 
 * *Luis Carcamo*  - [lcarcamo1526](https://github.com/lcarcamo1526)


## License

This project is licensed under the MIT License 

