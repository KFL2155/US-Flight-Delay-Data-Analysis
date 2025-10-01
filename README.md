## INTRO

I analyzed the entire dataset from the "Flight Delay Dataset - 2024" , which is available on Kaggle.com.
Once importing the file into Tableau Public, I noticed it contained 35 columns and over 7 million rows(screenshot reference below).

<img width="3060" height="785" alt="image" src="https://github.com/user-attachments/assets/7c350ffa-4267-476c-8859-5bd4366f074e" />


Due to the large size of this dataset, I decided to use Tableau to analyze and visualize my objectives.
I also wanted to use Tableau to practice my visualization skills and become more familiar with this tool.

## OBJECTIVES

Based on the data provided, I wanted to explore some questions which interested me:
1. Which flight routes have the longest delays?
2. Are there more delays during certain parts of the year?
3. Which states have the longest delays?

## ANALYSIS

Below is the final Dashboard after my analysis

<img width="803" height="453" alt="Image" src="https://github.com/user-attachments/assets/90a6170c-53c4-4b73-94fe-9dae7a599a76" />



I have also added a short video below to illustrate that the dasboard is interactive. I configured the filters of the map to apply to the entire dashboard to allow for a more interactive visualization.

https://github.com/user-attachments/assets/0949ac03-7bfb-4baa-8d33-aeb00332a472



1. Which flight routes have the longest delays?
We can see that flights from Vermont to Texas, on average, have carrier delays for almost 1 hour.
There was one flight from Oklahoma to South Carolina which had a carrier delay of almost 3 hours! However, since this is part of a dataset of over 7 million flights, I dop not find this to be statistically significant.
The second most delayed route due to carrier issues is from Alska to Michigan.

2. Are there more delays during certain parts of the year?
The bottom left graph of the Dashboard illustrates that the Summer months in the US have the most flights. There is also a positive correlation between the number of flights and the time of delayed departure. As the orange line shows, the delayed time in minutes generally increases as the number of flights also increases. Summer flights are, on average, expected to be delayed between 15-25 minutes.

3. Which states have the longest delays?
The map illustrates that the Midwest experiences the longest weather delays compared to other regions of the US. For example, Wyoming, West Virginia, and South Dakota have the longest national weather delays at 3, 3 and 2.5 minutes, respectively.
West Virginia is interesting since it has an average of 3 minute delays due to weather, but all of it's neighbors have an average weather delay of less than 1. 


# ADDITIONAL FINDINGS

<img width="451" height="250" alt="Image" src="https://github.com/user-attachments/assets/e05882bf-e216-43a8-8843-00424434f4d2" />


<img width="383" height="164" alt="Image" src="https://github.com/user-attachments/assets/5291df76-3aef-4a97-897a-a9cc7b419299" />



