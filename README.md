# Case_Study_2

## Welcome to the README.md file for Case Study Two

This readme file will serve as an instruction manual and guide to compiling project code, operating the Shiny application, and manipulating the dataset and code so that the user is able to customize.

### Code
#### Required Libraries and Packages

This section contains the libraries and packages used in the code. It also specifies the purpose for which they were used. 
The libraries and packages used in this case study are commented out in the R sheet file. In order to install them, uncomment the section.

##### Libraries/Packages Used

1. dplyr
3. ggplot2
4. dlookr
5. visdat
6. GGally
7. forcats
8. class
9. caret
10. e1071
11. magrittr
12. leaps


###### dplyr
Used for Exploratory Data Analysis and manipulation
###### ggplot2
Creating plots and data visualizations

###### dlookr
Used for Exploratory Data Analysis and manipulation

###### visdat
Analyze and examine data for missing values. Used in tidying data stage

###### GGally
EDA to determine and find correlation between variables in provided dataset

###### forcats
Functions within package to order data in alphabetical and numerical order

###### class
kNN classifier

###### caret
Classification and regression

###### e1071
Statistical Analysis Tools

###### magrittr
Forward Piping

###### leaps
Forward, backward, and stepwise regression. No longer in code

#### EDA
The EDA performed in this case study is very broad as there are 36 variables. A number for plots were created with the ggplot function. Also, an Exploratory Data Analysis Report was created using the dlookr package. This is available in the code. However, it is commented out so the code can compile at a quicker rate. To enable this, please jump to the exploratory data analysis section of the code and uncomment it. The report will open in a new window (most likely your browser). 

#### KNN
The split of the data can be changed for the classifier. Please write the percentage as splitPerc = .00, where .00 is the percentage of your choice.
The k value for this classifier can also be changed

#### Regression
The linear regression is done in iterations. 
The first regression includes all variables within the dataset (expect for ID, Over 18, and Attrition)
Based off the effect of the variables, they were eliminated in the next iteration
The code will save csv files to your computer of your monthly income predictions
A data set is used without monthly income to execute your model
