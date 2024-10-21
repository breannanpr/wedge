
# Applied Data Analytics

## Wedge Project

This project takes a look at the transaction-level view of The Wedge Co-Op, the largest co-operative grocery store in the US. The data covers the period of time from January 1, 2010 from the point-of-sale system that wedge developed, through January 2017. 

### Task 1

* Files for this task: 
<!--  List of file or files here  --> 

Loads all data into GBQ data set.

`File1 Name`: 
Description of what this file does.

<!--  Repeat for each file  --> 

### Task 2

Files for this task: 
* task_2.ipynb
* sampled_owner_transactions.csv

`task_2.ipynb`: This file produces code that connects to Google Big Query, builds a list of owners, takes a sample of them and extracts all the records associated with those owners; resulting in a written local file.
`sampled_owner_transactions.csv`: This is the file that was produced by the task_2.ipynb code file and it contains the sample of owners and their records.  

### Task 3

Files for this task:
* task_3.ipynb
* wedge_summary.db

`task_3.ipynb`: This file produces code that connects to Google Big Query, utilizes the data, creates three tables within one SQLite database using python programming language.
`wedge_summary.db`: This file contains the SQLite database that was created using the task_3.ipynb programming file. Within it, are three tables; sales by date by hour, sales by owner by year by month, and sales by product description by year by month. This data can help us to provide information that might influence business decisions. 


## Query Comparison Results

Fill in the following table with the results from the 
queries contained in `gbq_assessment_query.sql`. You only
need to fill in relative difference on the rows where it applies. 
When calculating relative difference, use the formula 
` (your_results - john_results)/john_results)`. 



|  Query  |  Your Results  |  John's Results | Difference | Rel. Diff | 
|---|---|---|---|---|
| Total Rows  |   |   |   |   |
| January 2012 Rows  |   |   |   |   |
| October 2012 Rows  |   |   |   |   |
| Month with Fewest  |   |   | Yes/No  | NA  |
| Num Rows in Month with Fewest  |   |   |   |   |
| Month with Most  |   |   | Yes/No  | NA  |
| Num Rows in Month with Most  |   |   |   |   |
| Null_TS  |   |   |   |   |
| Null_DT  |   |   |   |   |
| Null_Local  |   |   |   |   |
| Null_CN  |   |   |   |   |
| Num 5 on High Volume Cards  |   |   | Yes/No  | NA  |
|  Num Rows for Number 5 |   |   |   |   |
| Num Rows for 18736  |   |   |   |   |
| Product with Most Rows  |   |   | Yes/No  | NA  |
| Num Rows for that Product  |   |   |   |   |
| Product with Fourth-Most Rows  |   |   | Yes/No  | NA  |
| Num Rows for that Product  |   |   |   |   |
| Num Single Record Products  |   |   |   |   |
| Year with Highest Portion of Owner Rows  |   |   | Yes/No  | NA |
| Fraction of Rows from Owners in that Year  |   |   |   |   |
| Year with Lowest Portion of Owner Rows  |   |   | Yes/No  | NA |
| Fraction of Rows from Owners in that Year  |   |   |   |   |

## Reflections

This brings into view the realities of what a world of data engineering might look like and painted a clear image for me. I look forward to finishing this project, through the semester because the value that practicing these skills will bring is imense. There are pieces of this project that I had ah-ha moments with and also a significant amount of getting up and coming back to it later. Experiencing the cycle of working on a larger project like this feels overwhelming at first, I definitely put off this project for fear of just not being able to complete it or just not really knowing how to get started, where to start. The best remedy I found of that was just taking a step back, getting some pen and paper and making a game plan. In addition to this, articles and additional youtube videos were incredibly helpful in understanding how to go about this project. There were also some bits and pieces from lab recordings, lectures, some homework assignments that we had so far this semester that were incredibly valueable to be able to reference. 

I am still not sure I feel confident in submitting this but I am also just excited to learn about how to improve or if there are better ways to be more efficient at this. In all, this experience was awesome and I am glad to have perservered to the level that it is currently completed. 
