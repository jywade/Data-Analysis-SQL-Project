# Hotel Revenue Project

In this project, I sought out to answer three questions from stakeholders using analysis and visualization tools such as MS SQL Server, Power Query, and Power BI. 


****Question 1: Is our hotel revenue growing by year?****


****Question 2: Should we increase our parking lot size?****


****Question 3: What trends can we see in the data?****

Pipeline: Built a database, developed the SQL query, connected Power BI to database, visualized data, summarized findings.


I began by uploading the data to MS SQL server and conducting exploratory data analysis in order to find the find the total revenue per year (2018, 2019, 2020).

<img width="884" alt="MS-SQL-TotalRevenue" src="https://user-images.githubusercontent.com/120602494/236716893-adeffb96-1995-4126-8919-7fbf6240f8f3.png">

I then further analyzed by hotel type (there were two hotel types: city, resort).

<img width="883" alt="Revenue-by-HotelType" src="https://user-images.githubusercontent.com/120602494/236717051-a5a9069e-d0f8-47ed-afcf-7b4e012ccab0.png">

Revenue seemed to be growing and had a significant increase from 2018 to 2019. 


I then joined (left join) the tables to see meal cost for the two hotel types and market segments. 

<img width="872" alt="sql-join" src="https://user-images.githubusercontent.com/120602494/236717382-cab5d8c8-e20a-4ca5-b316-8d6f62dd4486.png">


After this I uploaded the SQL query to Power BI and transformed it using Power Query editor. 

I divided the required parking spaces by the total nights in order to find the parking percentage and answer the second question. 

There didn't seem to be enough evidence for the suggestion of increasing the parking lot size, the data was stagnant and not really growing. 

I utilized power query in order to create new measures and find any trends or patters within the data. The average of adr, the total nights, the average of discount, and the number of car spaces all had an upward trend between 2018 and 2020. 

I visualized my findings using Power BI visualization tools. 

<img width="793" alt="Screenshot 2023-05-07 213353" src="https://user-images.githubusercontent.com/120602494/236718271-bd1361d3-5d4d-4545-be4a-c1f110ebf34d.png">


