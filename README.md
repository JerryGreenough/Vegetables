# Vegetables
A demonstration of ETL (Extract-Transform-Load) techniques that have been used to acquire information concerning vegetables. Investigations have been conducted into three areas: 

<ul>
    <li>(i) Production & consumption of vegetables,</li>
    <li>(ii) Nutritional value of vegetables,</li>
    <li>(iii) Recipes that use vegetables.</li>
</ul>

<br>

Each of the above areas is represented by a Jupyter Notebook containing Python code that performs ETL operations that culminate in the population of a MongoDB Database. The extraction phase for each area of interest involves web-scraping and data processing using Python libraries such as Pandas, Beautiful Soup as well as the Python ```requests``` library. The Pandas library is also used for data transformation. 

<br>

Prior to the loading phase, a number of charts a produced using the ```matplotlib``` Python library. Loading of the MongoDB database is achieved programmatically with Python by using the ```pymongo``` library.
