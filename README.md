# Introduction:
Hello viewer and welcome to Group 5's submission for Project 2. Please note that despite the description referring to this as a partner activity, our group consists of 4 members, Angel Lee, Alexandra Calametti, Brian Guenther, and Matthew Bond. In this repository, you will find the Starter_Code folder which contains our completed code "ETL_Mini_Project_Group_5", the ERD sql file containing the SQL query schema, and the image of the ERD. There is also a resources folder. The resources folder was provided to us with only two excel files: "contacts" and "crowdfunding". Our code added the additional csv files: "campaign," "category," "contacts," and "subcategory."

# Overview and Troubleshooting:
Description: "For the ETL mini project, you will work with a partner to practice building an ETL pipeline using Python, Pandas, and either Python dictionary methods or regular expressions to extract and transform the data. After you transform the data, you'll create four CSV files and use the CSV file data to create an ERD and a table schema. Finally, you’ll upload the CSV file data into a Postgres database. Since this is a one-week project, make sure that you have done at least half of your project before the third day of class to stay on track. Although you and your partner will divide the work, it’s essential to collaborate and communicate while working on different parts of the project. Be sure to check in with your partner regularly and offer support."

There are four major parts of the assignment: 1) Create the Category and Subcategory DataFrames, 2) Create the Campaign DataFrame, 3) Create the Contacts DataFrame, and 4) Create the Crowdfunding Database. 

In part 2, we were struggling to change the datatype of "launched date" and "end date." Fortunately, our group members found two effective ways which is why there is an additional "#Alternate" cell. See images:

![dtype1](https://github.com/leeangel0428/Crowdfunding_ETL/assets/137225965/07592ec6-60d5-470c-81b0-e799df22da96)

![dtype 2](https://github.com/leeangel0428/Crowdfunding_ETL/assets/137225965/2c2e7b3f-c4d4-4958-b473-d059d2172c6c)

In part 3, we were given two options: 1) Use Python dictionary methods or 2) Use regular expressions. We chose option 1 which is why the option 2 portion of our code is left blank.

We also ran into an error when creating the contacts dataframe. No matter what we did, we could not get it to run until we looked at the excel file and saw that the header should have been 3 and not 2 as the provided code suggested. See images:

![code_error1 1](https://github.com/leeangel0428/Crowdfunding_ETL/assets/137225965/3f131c1c-a3bd-4bc7-9895-3399344b8da8)

![code_error1 2](https://github.com/leeangel0428/Crowdfunding_ETL/assets/137225965/1e3d7782-7c45-45f4-95d4-3617ad903148)

![contacts_excel](https://github.com/leeangel0428/Crowdfunding_ETL/assets/137225965/6e52f53c-5d6d-41f9-8b25-5b33f9a43223)

Part 4 Images:

ERD:

![miniproject_erd](https://github.com/leeangel0428/Crowdfunding_ETL/assets/137225965/5394be7f-1f69-4b02-977b-35727bb242ff)

Checking that all of our SQL tables are correct:

![1](https://github.com/leeangel0428/Crowdfunding_ETL/assets/137225965/cae36faf-ddcc-4979-a7ee-697a15256834)

![2](https://github.com/leeangel0428/Crowdfunding_ETL/assets/137225965/a4549d90-9763-41a4-ad06-54a1d7e51d17)

![3](https://github.com/leeangel0428/Crowdfunding_ETL/assets/137225965/2d70162d-ca6b-4e37-afdb-d4ecd19b2e54)

![4](https://github.com/leeangel0428/Crowdfunding_ETL/assets/137225965/a81789c2-a695-4fc2-9285-d87f7e93dac5)

# Resources and citations (in usage order): 
Used to split columns:

Pandas. (2023). Pandas.Series.str.split. Pandas Documentation. Retrieved from:https://pandas.pydata.org/docs/reference/api/pandas.Series.str.split.html

Used for creating dataframes:

StackOverflow. (n.d.). Convert Pandas Column to DateTime. Retrieved from:https://stackoverflow.com/questions/26763344/convert-pandas-column-to-datetime

Used for list comprehension:

TutorialsPoiunt. (n.d.). How to get a list of all the keys from a Python dictionary? TutorialsPoint. Retrieved from: https://www.tutorialspoint.com/How-to-get-a-list-of-all-the-keys-from-a-Python-dictionary

Data to Fish. (2022, February 25). How to Extract Dictionary Valuies as a list. Retrieved from: https://datatofish.com/dictionary-values-as-list/
