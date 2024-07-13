# Hey beautiful ladies :) Please Note! these assignments are part of your final lab assessment report.
1. ## Lab report document layout
    1. ### Assignment N (Related Area)
        ```
        Assignment Description
        ```
    1. ### Implementation
        ```
        Relevant Code Sections Only
        ```
    1. ### Output Snapshots
        ```
        Attach snapshots taken during code execution
        ```
    1. ### Takeaway
       ```
        Short summary (Few bulleted points) of your learning from this assignemnt implementation
       ```
1. Manually create folders for each assignment under your repo root folder. Folder structure would be (Referring my repo, you use yours):
    ```
    > NETLEARNING-BISHNU
        > FirstConsoleApp
        > Assignment 1
        > Assignment 2
        > ...
    ```
1. Save all your code snapshots in corresponding assignment 
folder. 
## Note: This will be your final assessment for Net centric Computing.
# Assignement 1 (Kick Starter)

1. Create a new console application named **Greeter** under **Assignment 1** folder.
1. Modify **Program.cs** to define a variable **fullName** and assign some name.
1. Print value of **fullName** to console.
> Take a snapshot of your work here (Code + Output) and save it. 
4. Define another variable **cFullName** and initilize it with **fullName** in uppercase letters. (Hint: *ToUpper()* string helper)
1. Print value of **cFullName** to console in format: "Hello, BISHNU RAWAL Ji!"
> Take a snapshot of your work here (Code + Output) and save it. 
6. Instead of initilizing **fullName**, get it from user. (Hint: *Console.ReadLine()*)
> Take a snapshot of your work here (Code + Output) and save it. 
7. Now also ask user to enter his/her "Date of Birth" and display user friendly date to console. At this point your output should look like assuming user enters dob as "2010/12/12": (Hint: *DateTime.Parse(dateString)*)
```
Hello, BISHNU RAWAL Ji!
Your DOB: Sunday, 12 December 2010
```
> Take a snapshot of your work here (Code + Output) and save it. 
8. Your last task is to calculate his/her age as accurate as possible and dispaly it to console. (Hint: If you subract dob from current date, you will get TimeSpan value, TimeSpan will have properties like *.TotalDays*, *.TotalHours* etc.) End output will be like:
```
Hello, BISHNU RAWAL Ji!
Your DOB: Sunday, 12 December 2010
Age as of now: 13 Years 2 Months 1 Week 1 Day
```
# Assignment 2 (OOP Concepts)

Think of a real world scenario where you can design classe(s), interface(s) and members as shown in following class diagram:

![alt text](/Assignment%202/Assignment2.png)

> **Note:** Please create new console app to demonstrate all this and push your changes and snapshots (if needed) to respective assignment folders

# Assignment 3 (File IO and LINQ)

You have csv data for inflation rate in Asia and the Pacific located `Assignment 3\Inflation.csv`. There are 6 data columns with few hundred rows. Data format looks like following:
RegionalMember | Year |Inflation|Unit of Measurement| Subregion| Country Code|
--------|-------|------|------|------|-------------------------------------------
........|........|....|....|.......|..........
Armenia|	2022	|8.6|	%|	Central Asia|	ARM|
Armenia	|2023|	7|	%|	Central Asia|	ARM
Armenia	|2024|	6.2|	%|	Central Asia|	ARM
Azerbaijan|	2018|	2.4|	%|	Central Asia|	AZE
Azerbaijan|	2019|	2.7|	%|	Central Asia|	AZE
Azerbaijan|	2020|	2.8|	%|	Central Asia|	AZE
........|........|....|....|.......|..........

Now your tasks are:
1. Create class **Inflation** with all column headers in csv file defined as properties
2. Create another class **InflationAnalysis** and define `List<Inflation> asianPacificInflations` collection as field.
1. Read csv text and populate `asianPacificInflations` collection looping through data read from the file
2. Write individual methods on `InflationAnalysis` tonswer following queries related to inflation:
    1. Find inflation rates for countries for the year 2021.
    2. A year when Nepal has highest inflation.
    3. List top 10 regions (countries) where inflation is highest for all time
    4. List top 3 south asian countries with lowest inflation rate for year 2020

> Note: Please take snapshots as needed for your attempt progress (Code + Output).