# Action Movie Success
The movie industry is a multi-billion dollar industry. Action movies are an all-time popular genre in the movie industry. The cost of making an action movie varies significantly, and every year, billions of dollars are poured into making, producing, and marketing movies. This project aims to investigate the connection between the popularity of an action movie and its budget. To do this, we will analyse the historical data of the most popular action movies of the last 20 years, focusing on their budgets, ratings, and financial performance.

## Project Overview
Automated processes are used to identify whether there is a relationship between an action movie's popularity (defined by its ranking on [IMDB](https://www.imdb.com "Search the web")) and its budget (provided by [BoxOfficeMojo](https://www.boxofficemojo.com "Search the web")). By using automated processing to collate and analyse the data, it increases efficiency and reduces room for human error. The results will provide valuable insight into the relationship between movie budget and ranking in the action movies genre, benefiting a range of users, from film industry leaders to the general audience.

From IMDb, the top 25 action movies from the last 20 years that have over 50,000 votes and a rating of over 7.5 are collected. From Box Office Mojo, each movie's budget, worldwide gross, and the percentage of domestic and international gross are collected. The movie budgets are plotted against their ranking to identify any existing relationships. These insights are then generated into a Word document for ease of use.

## Pre-requisites
* UiPath Studio (Academic Alliance)
  * Edge Extension (*Tools > UiPath Extensions > Edge*)
  * Use Modern for New Projects **OFF** (*Settings > Design > Use Modern for New Projects **OFF***)
* Microsoft Excel
* Microsoft Word

If you do not have a UiPath Studio Academic license, sign up [here](https://www.boxofficemojo.com](https://www.uipath.com/rpa/academic-alliance/academic-studio-download) "Search the web").

## Installation
Use the following steps to install and set up the project:
* git clone https://github.com/jsan956-ai/RPA-G4-2023.git
* Open UiPath Studio
* In the navigation bar, click *Open*
* Navigate to the directory of the project folder
* Open `project.json` file to install dependencies
* Open `Main.xaml`
* Run or Debug by clicking button

## Important Notes
On initial download, the `Files` folder will be empty. After running the bot, the output files will be generated and stored here. Before re-running the bot, it is recommended that the `Files` folder is emptied.

## Logs
Log files can be found in the `Logs` folder.

## Testing
Test cases can be found in the `Tests` folder.
