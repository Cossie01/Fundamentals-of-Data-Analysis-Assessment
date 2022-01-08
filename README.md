HDip Data Analytics 2021 Fundamentals of Data Analysis Assessment

*Submitted by*: Ciara O' Sullivan (Student Number: G00398379)

*Lecturer*: Dr Ian McLoughlin 

*Programming Language used*: Python 

*Github respository at*: Cossie01/Fundamentals-of-Data-Analysis-Assessment (github.com)


# Introduction

This README is broken down into two parts corresponding to the two assignments of the assessment. The first part is an overview of the overall basics of the Matplotlib package with sample code. From there, I use my newly found knowledge to display five different types of plots that can be executed by this package. For this I use the widely used Titanic Data set. This leads us onto the Cao data part of the assignment.

Alongside the README, I examine and show my workings in two separate jupyter notebooks. The first is called pyplot.ipynb and this examines the Matplotlib package while the second notebook called Cao.ipynb considers the second part of the assignment. 


In order to view the notebook you will need to download it from this repository and open it in Juypter. Jupyter notebook/lab is installed with the introduction of the Anaconda program. If unfamiliar with these programms, it is also possible to view a static version using my direct link to my git hub (https://github.com/Cossie01/Fundamentals-of-Data-Analysis-Assessment).


Furthermore, all images and reference can be located in a separate markdown file with the name References. 


## Matplotlib

The first part of the assignment is looking at matplotlib with a view of five specific plots.

Matplotlib makes graphs of arrays in Python and uses Numpy and other extention codes to provide good performance for large arrays.

Some visualisations that can be created from this package are as follows:

* Linegraphs
* Barcharts
* Histograms
* Scatterplots
* Area Plots
* Pie Charts
* Box plot
* Violin Plot
* Surface Plot

![matplotlib] (https://matplotlib.org/3.4.3/index.html) 


## The second part of the assignment is to view of CAO point system and using a panda data frame to compare and contrast.

The second part of the assignment is using the Panadas package to merge three datasets the Cao points from 2021, 2020 and 2019. Then to compare the Round 1 Points and then compare the Round 2 Points to see if they is any correlation between the years. From there, I have dispayed my outcomes with the use of some specific graphs.

![cao](https://upload.wikimedia.org/wikipedia/commons/5/51/Central_Applications_Office.png)


To do
- ~~Read in 2021 Cao Data~~
- ~~Read in 2020 Cao Data~~
- ~~Read in 2019 Cao Data~~
- ~~Clean up the data~~
- ~~Add all the data sets together~~
- ~~Use the course code as the index and remove duplicates ~~
- ~~Remove all courses that were not ran in the certain year~~s
- ~~Add all the points for R1 for the three years~~
- Detailed comparison using pandas
- Plots 

Items I learned

- Sometimes you need to re-load the whole kernel again to ensure something runs correctly. This occured when I was trying to remove colums from 2021 dataset, it would remove some columns but then when it was re-ran separetly then an error would appear and state that the column wasnt there so took some time trying to figure that out. 
- In times it felt it would be faster but I knew by learning new ways it will help me be more efficient in the future. 
- I think if I was to do this assignment again, I would change the name of the headers first of all the datasets and endsure they were all the same accross the board, this will make it easier when merging the dataframes. 
- Further on I noticed that there was NaN values which I wasnt sure at first what to do with it. 
![cheetsheet](https://st11.ning.com/topology/rest/1.0/file/get/2808327959?profile=original)