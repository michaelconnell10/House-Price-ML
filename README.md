# Using Machine Learning to predict house prices

The housing market is crazy right now. It seems like anyone who has bought a house in the last 12 months has had to overpay by several tens of thousands to try and
compete with real estate companies buying out houses in bulk to rent out. This, in turn, has also caused a shift in the rental market too - with landlords increasing rent prices by several hundreds of dollars.

For this project, I scraped real estate info from realtor.com using a reformatted version of my [Indeed Scraper](https://github.com/michaelconnell10/Indeed-Scraper/blob/main/Indeed_Scraping.py). However, I went in and manually cleaned the data - I took out any that were measured in acres as well as any where the property size listed looked incorrect. For example, there was one in Austin's city limits that had a property size of 69 acres.

After cleaning the data, I used supervised Machine Learning to predict house prices based around property size. The main tools used in this project are Python, Jupyter notebooks, and regression models. 
