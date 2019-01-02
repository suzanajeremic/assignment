# assignment

##  Prerequisites
To fulfil this assignment you will need Java 8, Maven, Git and a GitHub Account :octopus:. You can use an IDE or source editor of your choosing.

## Requirements 

### Input data
This assignment source provides two .csv files in the [resource folder](src/main/resources/):
* __politicalCommunities.csv__
Lists all political communities in Switzerland.
* __postalCommunities.csv__
Lists all "postal communities" in Switzerland.

### Assignment 1
Analyze the data in the two .csv files and build a model / data structure that represents the consolidated data.
* Create the model classes
* Implement the method createModel(...) in CommunityMain so that it returns your model / data structure

How you can easy correlate the 2 data sets? Use a unique key / id available in both data sets

### Assignment 2
Implement all the other methods in CommunityMain that throw a runtime exception using your model / data structure that you have created in Assignment 1

### Assignment 3
When looking at the 2 CSV's, describe some other "interesting" facts you get out of your data set's.
