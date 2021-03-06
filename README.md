# Problem Set 2

## Group project
This is a group project.
You should work in groups of 2 to 4 (not alone and not more than 4). If this is a problem, please let me know ahead of time.

### Please enter the names of the group members here:
1. Kerry Lambert
2. Julio Quinones
3. Nicole Pelletier

## Due date
**It is my hope that is can be turned in on Friday, May 22nd**, but I will take it until May 26th at the latest.

## The dataset
I have provided a dataset that you will use for this. The dataset and it's description are on the cluster as well as in github.
 * The dataset is at: `/ufrc/bsc4452/share/Class_Files/data/flights.May2017-Apr2018.csv`
 * The metadata (description of the data) is at: `/ufrc/bsc4452/share/Class_Files/data/flights_metadata.md`
     * It is also [nicely rendered on github](https://github.com/CompTools/Class_Files/blob/master/data/flights_metadata.md).

## Instructions

The goal of this project is to write a Bash script that does the following:
1. Counts the number of flights that were delayed more than 15 minutes into or out of Gainesville, FL (airport code GNV) during the timeframe covered by the dataset. (*2 points*) 950

**Grading: 2pts**

2. Produce a table (text is fine) with the data to fill in this table (*13 points*):


GNV to: | Total flights | Total flights delayed (>15min) | Total flights delayed due to Weather
--------|---------------|------------------------|-------------------------------
ATL | 1476 | 310 | 0
CLT | 476 | 118 | 0
MIA | 205 | 36 | 0

3. Within a function, print a list of all unique airport codes contained in the dataset. (*3 points*)

**Grading: 3pts. Not a function, but nice solution**

4. Within a function list the cities in Florida that have airports in the dataset. (*2 points*)

**Grading: 2pts. Though your grep is kind of complex and misses: "PBI","West Palm Beach/Palm Beach, FL","FL"**


**Bonus question:**  Asks for user input (see chapter 28) to enter either a airport code or city, state name and then calculates the number of flights as in question 1. (*5 points extra credit*)

## To submit
You should submit your answer as one or more scripts in a git repository. Submit the link in Canvas.

You should start in Canvas, creating your group and then create the same group in github.

**Be sure to edit this README.md file with the names of the group members.**

## Grading
For questions, 1, 3 and 4, I will mostly be looking for the right answer.

**Your score on 1,3,4 (I'll fill this in when I grade):**


For question 2, you will receive points for:

Rubric item | Points | Your score
------------|--------|-----------
Using github| 1 point |  **1**
Having at least one commit from each member of the team | 2 points | **2**
Using meaningful commit messages | 2 points | **2--in the future, please use more than updated X. What was changed?**
Using functions correctly | 2 points | **0--No functions**
Using comments in code | 2 points | **2**
Using spacing to make code readable | 2 points |**2--could be better**
Getting the correct answer | 2 points | **1pt--digit grep didn't work so you got wrong answers**
Question 2 Total | 13| 10
**Extra credit:**
No extra credit.

**Total points: 17/20**
