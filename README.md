Analytics Portfolio
# COVID-19 ANALYSIS USING SQL AND VISUALIZATION USING POWER BI.

The Covid-19 pandemic caused significant loss of life and negative economic impact, making effective public communication critical for decision-making. Daily updated Covid-19 datasets are available on various websites, including https://bit.ly/3LmfAAG.

In my project, I used the 2022 Covid-19 dataset to explore and visualize data using MSSQL and Power BI. I split the dataset into two forms with Excel for simplicity: CovidDeaths, and CovidVaccinations. The CovidDeaths dataset includes information on cases and deaths, while the CovidVaccinations dataset contains details only on vaccinations and tests.


I executed this SQL project using Microsoft SQL Server Management Studio, and a snapshot of a few columns and entries in the CovidDeaths and CovidVaccinations datasets is available below. The SQL query file is also available on my Github Repo:


In Scenario 1 : The following data was explored specifically for Ethiopia: Total Daily Cases, Deaths, and Percentage Death Rate, which indicates the likelihood of an infected person dying. It should be noted that this scenario is not limited to Ethiopia, and information for other countries can also be explored using the same approach.

![1](https://user-images.githubusercontent.com/131899006/234667653-ab0959aa-54cc-4ef5-8833-162dc452e6f6.png)

The above table represents the results for the first 15 days since the covid-19 outbreak in the country, we can see that no deaths were recorded and there were just a total of two cases.

![1b](https://user-images.githubusercontent.com/131899006/234668279-880fa5a5-9e06-4b35-b1bb-91e2101873fd.png)


The above table represents results for the last 15 days prior to May 2ND, 2022 when the cases already blew up over 470,000 cases and over 7500 deaths.



In Scenario 2: I examined multiple countries and analyzed their Total Cases, Total Deaths, Percentage of the Country Population Infected, and Percentage of the Country's Population Deceased. The results were sorted in descending order by the Percentage of the Country's Population Infected.

![2A](https://user-images.githubusercontent.com/131899006/234668410-ef79f429-3fbf-4d63-b156-bbfefd5987b7.png)


The query and snapshots above show the top rows of the result, which indicate that the Faeroe Islands had the highest percentage of the population infected with Covid-19. Scrolling down the result reveals information on other countries, with the explored columns sorted in descending order of their percentage of the population infected.

It should be noted that the above exploration can be sorted in descending order of other variables such as Total Cases or Total Deaths, depending on the information of interest. For example, if we sort the above scenario in descending order of Total Cases, the query and result using Microsoft SQL Server Studio would be as follows:

![2b](https://user-images.githubusercontent.com/131899006/234668591-403f46b4-8617-4b8b-84a9-ef27ec30b071.png)



The snapshot of the result above displays the top 15 countries with the highest total cases of COVID-19. The United States had the highest number of cases, with over 81 million recorded, and nearly a million total deaths. India followed with over 43 million cases, and so on, with countries arranged in descending order of Total Cases. Scrolling down on the MSSQL studio reveals additional countries and their corresponding Cases, Deaths, Populations, and more.

Scenario 3: presents an alternative method of exploring countries with their Total Cases, Sum of Deaths, Percentage of Population Infected, and Percentage of Population Dead. The highest infection count and highest death count are used in place of Total Cases and Total Deaths, respectively, as columns in the dataset record the cumulative cases and deaths. The query and result for this scenario are as follows:
![3A](https://user-images.githubusercontent.com/131899006/234668905-8a4f1ef8-5ddf-4710-88a2-530338762b02.png)


Thus, we can deduce it gave the same results as the former case scenario. It is an alternative solution to the former scenario.

In Scenario 4: I provide information on global numbers, including the world's Total Cases, Total Deaths, Total Population, Death Percentage, and Case Percentage.

![4A](https://user-images.githubusercontent.com/131899006/234669049-1614f78a-cd83-4e73-ba0a-38802432343c.png)


The results of Scenario 4 reveal that as of May 2nd, 2022, the recorded total cases of COVID-19 worldwide were 513,180,614, estimated to be over 500 million cases. The total number of recorded deaths across the world was 6,194,913. The world's total population was estimated to be over 6 trillion, with a death percentage and case percentage of 1.2% and 0.008%, respectively.

Scenario 5: Focuses on exploring the country's recorded daily new cases, new deaths, cumulative cases, cumulative deaths, new vaccinations, and cumulative vaccinations. In order to better visualize and understand these insights, visualizations were created for this COVID-19 case study analysis.

![5A](https://user-images.githubusercontent.com/131899006/234669083-78b6fa69-f3d3-4a7f-aee9-a9d8937aae2e.png)

![5B](https://user-images.githubusercontent.com/131899006/234669146-282c2241-9152-4b1f-8094-4c59cbfd2b77.png)

The result gives the country's daily recorded population, cases, the cumulative sum of daily cases, deaths, the cumulative sum of daily deaths, vaccinations, and the cumulative sum of the daily vaccinations. Insights from these results will be understood more clearly through the visualizations.

SCENARIO 6:
Here, we look into continents and their confirmed cases, deaths, and vaccinations. We want to know the order in which these continents are ordered in their confirmed total cases, deaths, and vaccinations.

![6A](https://user-images.githubusercontent.com/131899006/234669239-ff64ca95-57ce-4c02-8c8d-ba3f0f202580.png)

Here, we can see the continents and their respective total cases and total deaths, This was sorted by the total cases in descending order, Thus Europe had the highest sum of cases, followed by Asia, NA, SA, Africa, and Oceania.
Then, we will explore the continents sorted in descending order of their total deaths

![6B](https://user-images.githubusercontent.com/131899006/234669264-72f38491-fb8d-4106-9a8f-6da279fd6e95.png)

This is a COVID-19 exploration project that utilizes SQL to analyze cases, deaths, and vaccinations. The purpose of this project is to apply basic SQL knowledge to explore real-life scenarios of the COVID-19 outbreak. The queries include basic SQL functions, window functions, and CTEs. Visualizations of the case scenarios in this project were created using Power BI.
VIZUALIZATION USING POWER BI 


