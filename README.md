# Decision-Tree-Simulation-in-Banking-Data

I try to run a simple Decision Tree simulation of Banking data that previosly I have downloaded it from kaggle by finding out how each independent variables affect balance. Using python, we can visualize the result of the decision.

1. import related libraries

![text image](https://github.com/altheanabila/Decision-Tree-Simulation-in-Banking-Data/blob/main/pic1.png)

2. Extracting the data [Banking data.csv](https://github.com/altheanabila/Decision-Tree-Simulation-in-Banking-Data/blob/main/bank.xlsx) into pandas dataframe

![textimage](https://github.com/altheanabila/Decision-Tree-Simulation-in-Banking-Data/blob/main/pic10.png)

3. Checking out if there's missing value or string data which means we need to convert it to dummy variables

![textimage](https://github.com/altheanabila/Decision-Tree-Simulation-in-Banking-Data/blob/main/pic2.png)

4. Creating dummy variable, for variable with string value

![textimage](https://github.com/altheanabila/Decision-Tree-Simulation-in-Banking-Data/blob/main/pic3.png)

5. Define X variable and y variable

![text image](https://github.com/altheanabila/Decision-Tree-Simulation-in-Banking-Data/blob/main/pic4.png)

6. Use test train split with test size: 0.2

![text image](https://github.com/altheanabila/Decision-Tree-Simulation-in-Banking-Data/blob/main/pic5.png)

7. import decision tree regressor, and define prediction of y

![text image](https://github.com/altheanabila/Decision-Tree-Simulation-in-Banking-Data/blob/main/pic6.png)

8. Find mean squared error and r2 score, define dot data

![text image](https://github.com/altheanabila/Decision-Tree-Simulation-in-Banking-Data/blob/main/pic7.png)

9. Display regression tree graph

![textimage](https://github.com/altheanabila/Decision-Tree-Simulation-in-Banking-Data/blob/main/pic8.png)

![text image](https://github.com/altheanabila/Decision-Tree-Simulation-in-Banking-Data/blob/main/pic9.png)
