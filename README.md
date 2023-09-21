# Introduction:
Hello viewer and welcome to Group 5's submission for Project 2. Please note that despite the description referring to this as a partner activity, our group consists of 4 members, Angel Lee, Alexandra Calametti, Brian Guenther, and Matthew Bond. In this repository, you will find the Starter_Code folder which contains our completed code "ETL_Mini_Project_Group_5" and a resources folder. The resources folder was provided to us with only two excel files: "contacts" and "crowdfunding". Our code added the additional csv files: "campaign," "category," "contacts," and "subcategory."

# Overview and Trooubleshooting:
Description: "For the ETL mini project, you will work with a partner to practice building an ETL pipeline using Python, Pandas, and either Python dictionary methods or regular expressions to extract and transform the data. After you transform the data, you'll create four CSV files and use the CSV file data to create an ERD and a table schema. Finally, you’ll upload the CSV file data into a Postgres database. Since this is a one-week project, make sure that you have done at least half of your project before the third day of class to stay on track. Although you and your partner will divide the work, it’s essential to collaborate and communicate while working on different parts of the project. Be sure to check in with your partner regularly and offer support."

There are four major parts of the assignment: 1) Create the Category and Subcategory DataFrames, 2) Create the Campaign DataFrame, 3) Create the Contacts DataFrame, and 4) Create the Crowdfunding Database. In part 2, we were struggling to change the datatype of "launched date" and "end date." Fortunately, our group members found two effective ways which is why there is an additional "#Alternate" cell. In part 3, we were given two options: 1) Use Python dictionary methods or 2) Use regular expressions. We chose option 1 which is why the option 2 portion of our code is left blank.

# Resources and citations (in usage order): 
Used to split columns:

Pandas. (2023). Pandas.Series.str.split. Pandas Documentation. Retrieved from:https://pandas.pydata.org/docs/reference/api/pandas.Series.str.split.html

Used for creating dataframes:

StackOverflow. (.d.). Convert Pandas Column to DateTime. Retrieved from:https://stackoverflow.com/questions/26763344/convert-pandas-column-to-datetime

Used for list comprehension:

TutorialsPoiunt. (n.d.). How to get a list of all the keys from a Python dictionary? TutorialsPoint. Retrieved from: https://www.tutorialspoint.com/How-to-get-a-list-of-all-the-keys-from-a-Python-dictionary

Data to Fish. (2022, February 25). How to Extract Dictionary Valuies as a list. Retrieved from: https://datatofish.com/dictionary-values-as-list/
