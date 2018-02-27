# Data-Analysis-Tool
Create a open source analysis tool that will integrate various data and file types. 

## Synopsis
The challenge with conducting data analysis as a part of the decision-making process, is that the data comes from disparate sources, each with its own data structure. This requires someone to “cleanse” into a standard data structure before it can be used. That is fine for organizations that have IT departments, but not feasible for most churches, particularly churches in the developing world. 

The purpose of this project is to ask *“what if”* there was a tool that could automate the cleansing process. How would we create a tool that a person with at most a secondary level education and minimal to no technical background could us? What would that tool look like and how would it behave.

This project is, at least initially, an ideation effort. It is to explore ideas around the meeting the challenge and testing those ideas out. What we learn as we go through this process will determine the next steps. 

This project is part of the Open Digerati Community (https://opendigerati.com/projects/) and is being sponsored by Compassion International. We have developed a use case below to test our ideas against. We want to be able to consume data from APIs and import various data file types (.csv, kml, xml, etc) and convert data from all sources to a common structure and format. Our goal is to explore the possibilities around solving the challenge and determining if we can develop a solution to it.
 
## Getting Involved
Currently we are in ideation mode for this project. If you have an idea that you would like to share, post it as an Issue. Also join the Slack Channel for this project, https://opendigerati.slack.com/messages/C8TPGGM9P/team/U8R43B17T/. 

## Project Use Case
The scenario we want to use for this project is to combine population data, administrative district data, and church location data of Uganda into a single data store. We will be importing population figures, and area in kilometers for each district in Uganda along with the district boundaries. We will create a population density by district for individuals under the age of 18 by calculating and storing the number of people per square kilometer. By combining this information with the church locations, we can identify potential church partnerships for Compassion’s program based on youth population density.

The data files and links to API data sources can be found in the Test-Scenario folder.
