# Analyzing-Historical-Stock-Revenue-Data-and-Building-a-Dashboard
This lab forms part of the course Python Project for Data Science

### Question 1: Use yfinance to Extrack Stock Data
Using the Ticker function, i extracted the data from Tesla. 

![image](https://github.com/alejandromz2/Analyzing-Historical-Stock-Revenue-Data-and-Building-a-Dashboard/assets/30611516/c5b45662-7e6a-4d71-9325-bd6c78d0b78e)

And them, i used function history to extract stock information and save it in the dataframe named tesla_data. I applied reset_index(inplace=True) to testla_ data and them i use the function head() to saw the first 5 values.

![image](https://github.com/alejandromz2/Analyzing-Historical-Stock-Revenue-Data-and-Building-a-Dashboard/assets/30611516/9ed7eb03-49b5-463b-a15c-d24d63820623)

### Question 2: Use Webscraping to Extract Tesla Revenue Data

Use the requests library to download the webpage https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-PY0220EN-SkillsNetwork/labs/project/revenue.htm Save the text of the response as a variable named html_data.

I extracted the data from the website and i changed the column names to Date and Revenue. Finally i remove the dolar simbol and display the last 5 row from the dataframe tesla_revenue

![image](https://github.com/alejandromz2/Analyzing-Historical-Stock-Revenue-Data-and-Building-a-Dashboard/assets/30611516/ddc1f9e6-86d5-4619-88e8-e7eee0eaac20)


### Question 3. Use yfinance to Extract Stock Data
