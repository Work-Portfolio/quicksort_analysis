# quicksort_analysis

Time analysis of limiting the amount of recursive calls of Quick sort with different sized arrays and finishing sorting with 
insertion sort. The data was written into a CSV file and loaded into Apple's Numbers program to display data with tables
and graphs. NOTE: PDF export of this file did not completely render, best viewed with Numbers 

Brief description of submitted files:

Output/results.csv
    - A CSV file with the results of the quickSort testing. Formated "recursion limit, time"

Output/results.csv
    - Output file just used for testing

src/QuickSort.java
    - Class containing the quickSort method. It was modified from the FHSort class given in the class examples

src/RandomArray
    - A class written to return a Interger[] of a specified size filled with random numbers between 0-100000

src/RecLimAnalysis
    - This is the 'main'. It uses Random Array and QuickSort to test the quickSort method with different array sizes and recursion limits. Once the recursion limit is reached, insertion sort is used to finish the sorting process. The times are recorded and written to 'results.csv'


CS1C Project 9.numbers
    - Analysis of 'results.csv'. It has tables and graphs of results. Originaly written in "Macintosh Numbers", PDF has some reduring issues.
