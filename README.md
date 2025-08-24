# Mining-Data-Analysis
This is a Jupyter Notebook project I created for college course. Its purpose is to read a CSV file containing mining revenue information, analyze it and exhibit outputs for brazilian states and individual minerals information for a better understanding of the data.

For every task, there is my developed cell and after, an answer key for verification.

## Introduction and Data Reading
These two cells were developed by the professors, which the objective of the project is presented. The goal is to put in practice all the commands, logical thinking and functions we've learned throughout the course using a real and large data base, available by the National Mining Agency (ANM), called CFEM (Financial Compensation by Mineral Resources Exploitation). At first, the code downloads the CSV file from ANM's website and read it as lists.

## Revenue Growth Throughout the Years
Here, an analysis regarding the revenue growth on the brazilian state of 'Minas Gerais' through the years of 2004 and 2024 is requested. The first logical step was to filter the lists storing of MG state information. Then, create a revenue sum variable to store the revenue of a same year, ranging from 2004 to 2024, then keep these float numbers stored on an array for plotting.

## Iron Extraction by State between 2014 and 2024
The challenge here was to identify a specific mineral, iron, from all the others. Then, once I knew which states had extracted this mineral, I segregated them on a list. Then, for every state on that mineral specific list, I've made a variable to sum up every quantity, handling with attention every invalid data input, such as empty items "" that were on the file. Then, adjusting the variable quantity for millions of tons, dividing by 1,000,000 and plotting.

## Gold Extraction by State in the Past 10 Years
The basic logic from the last task is reused. Using the same functions and operations, with the exception of the axis' labels.

## Iron Extraction Growth Throughout the Years for Minas Gerais and Pará
The greatest difference here is that I had to apply functions working with two different lists/arrays at the same time. However, the state segregation and the quantity sum variable logic is preserved. Also, it was a good practice to learn how to plot two different arrays at a time on a graph.

## Percentage of Revenue Collection of South Region States and Minas Gerais in 2023, by Extracted Mineral
That was, undoubtedly, the hardest one. First, I had to make a segregation between the south region states (RS, SC and PR) on the lists. Then, separated only 2023 information and added up every revenue collection for every mineral for Minas Gerais and the South, generating the total of revenue for the percentage calculus. Thus, for every mineral these states extracted, I added up the obtained renevue into an array. Divided by the total revenue and multipied by 100 to get the percentage x%. Creating a threshold to define which mineral was at a considerable percentage, I plot two different tabular graphs, one for Minas Gerais extracted percentage by minerals and the other, for South Region states.

# Conclusion
That was a great project. My first time handling a large database and working with real information. I really enjoyed putting in practice all functions and commands I've learned through the course and my individual studies and learning more about data analysis libraries, such as NumPy and Matplotlib. 
