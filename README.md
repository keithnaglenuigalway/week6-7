## Week 5

### You are required to complete the following two programming questions:
### Question 1
1. Select two of the sort algorithms discussed in class and code the selected algorithms.
2. Add code to your sort algorithms to calculate efficiency by gathering data on:
       a. Time for algorithm to run
       b. Number of swaps
       c. Number of comparisons
3. Download the Peak Wind speed at 80meter data for your birthday in 2013 from the following website: http://www.nrel.gov/midc/apps/daily.pl?site=NWTC&start=20010824&yr=2014&mo=7&dy=24
      
      i.   Enter the date of your 2013 birthday as both the starting and ending date
      
      ii.  Check the box for the “Pk Wind Speed (80m)” in the right-hand column.
      
      iii. Select the output type “1-Min data (ASCII text)” in the left-hand column near the bottom
      
      iv.  Click on the Submit button.
     
     This will generate an ACSII list of the Peak Wind speed at 80meter in Colorado on your birthday in 2013.
     
4. Copy and paste the data into a text file and save in csv format.
5. Open the file in a spreadsheet program. Delete the top row and the first two columns.
6. Save the file and re-open in a text editor. Find and replace all instances of the newline character ‘\n’ with a comma ‘,’
7. Copy and paste the newly formatted data into an array declaration in your C program. Consider using a .h header file to keep things neat.
8. Run both of your algorithms with the wind speed data you created (keeping track of time, swaps, and comparisons).
9. Display your results and discuss which algorithm performed better on your data set.


### Question 2
Using the sorted data you created in Question 1, identify the maximum and minimum wind speed values. Create an array consisting of five integers that divide the extremes of the data range into five equally spaced partitions.  Returning to the unsorted data, create code that will read in the data, counting the frequency of instances of the data falling into each partition. Print out the frequencies in a user-friendly format.
    
    Simplified example:
    Number of measurements: 1440
    max wind speed: 100mph, min wind speed: 1mph
    partition ranges 1-20, 21-40, 41-60, 61-80, 91-100
    number of measurements between 1mph and 20mph: 901
    number of measurements between 21mph and 40mph: 214
    number of measurements between 41mph and 60mph: 166
    number of measurements between 61mph and 80mph: 117
    number of measurements between 91mph and 100mph: 41
