# Analysis of Stock Market Data Year over Year

## Overview of Project
### Purpose
The goal of this project is to use VBA to analyze a set of stock market data over 2017 and 2018 in order to help inform investment decsions. After an initial run of 12 using VBA code, we refactored the code in order to run it over the entire dataset and run more efficiently.

## Results
### Differences between 2017 and 2018
![2017 analysis results](https://user-images.githubusercontent.com/49666078/166146563-1859faae-ab71-4cf4-9775-a657547e4ad0.png)
![2018 Analysis results](https://user-images.githubusercontent.com/49666078/166146569-f1d55dd5-d96e-43bc-b1e7-c35fd9aec148.png)

As seen in the images above, the selected data shows that 2017 was an all around better year for these stocks than 2018. The two standouts from the data set are **ENPH** and **RUN** which both had posititve returns in both 2018 and 2017. **TERP** was the only stock that had negative years in both years. 

### Execution times of refactored script
![VBA_Challenge_2017](https://user-images.githubusercontent.com/49666078/166147550-110e1f9e-5b70-49ce-a161-577f0b81a20b.png)
![VBA_Challenge_2018](https://user-images.githubusercontent.com/49666078/166147551-c76238a4-0375-459f-85ca-a81cf808f7f8.png)

When the initial script was built to run analysis on this data, the script ran in around 0.6 seconds, but when the code was refactored to loop through the data all at once using an index, we got the script to run in around 0.12 seconds as seen in the screenshots above.

## Summary 

### Pros and cons of refactoring code

#### Pros
* You can double check your code for pieces that could be running more efficiently. 
* It helps you to understand the code better and comment out where there might be confusion.
* Generally it is good to improve your code.

#### Cons
* The benefit of refactoring the code is not always evident if the functionality does stay the same.
* When refactoring, you can run into more bugs and errors that were not present in the original code.

### Pros and Cons of refactoring the All Stock Analysis code
#### Pros
* The main pro to refactoring this code was that it made the code run more efficiently.
#### Cons
* There were a lot more errors that came up when refactoring the code than the original code.
