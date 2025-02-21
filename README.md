INTRODUCTION 

Hello, a little something about this project before we dive right into. So around November 2020, I had an interview with one really

good company here in Ghana. At the time, even though I had studied SQL, I just wasnt so confident, it was as if I didnt know what I went there for

and when the interview started, my nervousness and negative mentality really kicked in.  The interview was on a simple sql project on JOINS however, 

it wasn't the regular joins but multiple Joins and I just didnt know my way around it. To cut every short, I failed the interview but that didn't mean I was out

and given up I needed a dataset similar to the one I had in there. Luckily I had already downloaded this dataset and done something with it in Exce. I then

began to think and imagine similar questions with this dataset that I saw when I went for the interview. took me a while but finally got the hang of it.

I say well done to me.

Anyways, For this particular project, The source of my data was from kaggle . The dataset contained three different excel sheet, the first one contained data about the orders,![COFFEE SQL 4](https://github.com/user-attachments/assets/49176a93-7438-4526-a81e-1a0ec68cfafc)
![COFFEE SQL 3](https://github.com/user-attachments/assets/643f7499-4025-45ca-9b88-8f968b512323)
 second customers and third, Products.

After downloading the data, I applied the four step process I normally follow. which are 

Data Cleaning & Transformation![COFFEE SQL](https://github.com/user-attachments/assets/b3675093-8436-4f99-a3c1-fe377419b93b)

Data analyzing
Data visualization
Recommendations
Data Cleaning

In this dataset, I had only checked and confirmed there aren't any duplicates in excel so I moved forward with standardizing the dataset![COFFEE SQL 2](https://github.com/user-attachments/assets/890db72a-d623-485f-ad04-5c013b812435)


Above, I used functions like CASE END to change or standardize how some of the names were spelt out. I wanted to make it more readable for anyone that looks at the project, I also made use of Parsename and replace, to separate the full anme column into First_Name and Sur_Name. I also made use of delete where information of something columns are null, I didn't want that in this project and also we dropped some columns we won't be using.

Data Analysing

Here we had to get insight from the dataset to help in management decision making and so some of the questions we answered is included in the pictures below;

we also showcase the queries we wrote to derive these insights where we made use of alot of multiple joins functions since the dataset is contained in three different sheets.

We didn't perform any visuals on this dataset for now

Recommendations
Management should provide goods that sell more per city to those cities and make inquiries as to why certain products sell less at these cities. This way, managers can decide to either improve the quality of those goods at hose cities or focus on providing more of those goods to cities that prefer them
Management should also look at the monthly trend of the goods. Do they sell more at certain months by a very high high margin? if yes, it means we need to focus on providing more during those times than on less selling months in each city
Who are the top buying customers, and if we can give them something to entice them more, we can also learn why they love the types of products and based on that target their kinds with the types of products these top buyers enjoy the most.
Conclusion

Taking on this project has helped me practice my newly acquired skill and has helped build my confidence;

I successfully cleaned a raw data , transformed and analyzed it mainly with sql and applied MULTIPLE JOIN function. something I wasn't so confident about initially.
