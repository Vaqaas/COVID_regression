# COVID-19 Positive Case Changes by County in the U.S.

## Abstract

We've all experienced the impact of COVID-19 across the U.S. Because of the severity of this virus and its highly
contagious nature, we've seen a large rise in hospital admissions. As a result, resources from staff and equipment
have been experiencing shortages. The problem we're addressing is to better understand how the number of COVID-19
cases have been rising specified to the county level. By utilizing features such as number of vaccinations, deaths,
past cases, and hospital admissions, we built and refined a model to address this issue.

## Design

The project began by webscraping the New York Times website's coverage of COVID-19. We used tools such as Beautiful
Soup and Selenium to interact with the webpage and extract details. Afterwards, we processed the data to resemble 
something workable in a data analysis context, such as removing NA values and turning string-valued numbers into
usable floating point numbers. After fitting and refining the model, we can communicate the results so that county
hospitables can aqequately ration their supplies and be better prepared for rising cases.

## Data

After scraping the data from the NYTimes website, we obtained about 3000+ points of data with 11 feature columns. 
All the columns were numeric. Features included percent of population vaccinated, past hospital admissions, and
past cases.

## Algorithms

We used linear, polynomial, and ridge regression algorithms to ensure the best possible results. These packages and
classes included various optimization techniques like gradient descent to minimize mean-squared error.

## Tools

Primary coding was done in IPython notebooks. Webscraping was done with BeautifulSoup for specific HTML values,
while selenium was used for bypassing webpage-related obstacles like login pages. Furthermore, the data analysis
and modeling was performed with Pandas, Numpy, Sci-Kit, and plotting with MatplotLib.

## Communications

In the repository is a set of slides that communicates my findings as PDF file.
