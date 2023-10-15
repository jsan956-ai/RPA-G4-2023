![image](https://github.com/jsan956-ai/RPA-G4-2023/assets/79944764/f87a7ee4-b863-41bd-8626-a6dfde063e8c)
# Action Movie Success
The movie industry is a multi-billion dollar industry. Action movies are an all-time popular genre in the movie industry. The cost of making an action movie varies significantly, and every year, billions of dollars are poured into making, producing, and marketing movies. This project aims to investigate the connection between the popularity of an action movie and its budget. To do this, we will analyse the historical data of the most popular action movies of the last 20 years, focusing on their budgets, ratings, and financial performance.

## Project Overview
Automated processes are used to identify whether there is a relationship between an action movie's popularity (defined by its ranking on [IMDB](https://www.imdb.com "Search the web")) and its budget (provided by [BoxOfficeMojo](https://www.boxofficemojo.com "Search the web")). By using automated processing to collate and analyze the data, it increases efficiency and reduces room for human error. The results will provide valuable insight into the relationship between movie budget and ranking in the action movies genre, benefiting a range of users, from film industry leaders to the general audience.

From IMDb, the top 25 action movies from the last 20 years that have over 50,000 votes and a rating of over 7.5 are collected. From Box Office Mojo, each movie's budget, worldwide gross, and the percentage of domestic and international gross are collected. The movie budgets are plotted against their ranking to identify any existing relationships. These insights are then generated into a Word document for ease of use.

## Pre-requisites
* UiPath Studio (Academic Alliance)
* Edge Extension (*Tools > UiPath Extensions > Edge*)
![image](https://github.com/jsan956-ai/RPA-G4-2023/assets/79944764/9243fde2-54fc-46b4-a67b-c3a4d826f0e4)
* Use Modern for New Projects **OFF** (*Settings > Design > Use Modern for New Projects **OFF***)
![image](https://github.com/jsan956-ai/RPA-G4-2023/assets/79944764/547a7ccb-b44d-4861-a718-01b5e4d863a2)
* Microsoft Excel
* Microsoft Word

If you do not have a UiPath Studio Academic license, sign up [here](https://www.boxofficemojo.com](https://www.uipath.com/rpa/academic-alliance/academic-studio-download) "Search the web").

## Installation
Use the following steps to install and set up the project:
* git clone https://github.com/jsan956-ai/RPA-G4-2023.git
* Open UiPath Studio
* In the navigation bar, click *Open*
  
![image](https://github.com/jsan956-ai/RPA-G4-2023/assets/79944764/f8ea5fd2-5ce2-4045-b1c7-297c8c798f36)

* Navigate to the directory of the project folder
* Double Click `project.json` file to open the project and install the correct package dependencies
  
![image](https://github.com/jsan956-ai/RPA-G4-2023/assets/79944764/d6dd0c3e-6bf3-4360-864e-fbab70ec4431)

* Open `Main.xaml`, this is the main workflow which runs the application

* Run or Debug by clicking the following button found in the top ribbon called `Debug File`
  
![image](https://github.com/jsan956-ai/RPA-G4-2023/assets/79944764/ca3abcb8-2d42-4a1c-b59a-8762a56b94fe)

Doing so will automatically open up a Microsoft Edge browser and the entire process for the RPA BOT is completely automated, as such refrain from interacting with your computer at all while the bot is running.

## Important Notes
On initial download, the `Files` folder will be empty. After running the bot, the output files will be generated and stored here. Before re-running the bot, it is recommended that the `Files` folder is emptied.
**Before** running the RPA Bot make sure that all instances of Microsoft Edge browsers are closed.

## Logs
All Files generated from running the bot will be inside the `Files` folder.
Log files can be found in a sub folder called `Logs` and the Excel Spreadsheet and corresponding Word Document containing the scatter plots and insights showing potential trends in the movie data will be in the root directory of the `Files` folder.

![image](https://github.com/jsan956-ai/RPA-G4-2023/assets/79944764/6c7f4b37-d33d-44d6-90e6-1ecde3ae376c)

## Testing
Test cases can be found in the `Tests` folder.
