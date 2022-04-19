# Calculating the age of social network users

# Data

**profiles.csv** - a table of public information about users that is specified in their profiles.

Description of some columns:

*public: bool*, whether all "friendships" are public.

**relationships.csv** - table of "friendships" between users. It consists of two columns *user_id*, *friend_id*.

**test_users.txt** - the list of IDs of users whose age information is unknown. 
There is no AGE value in the *profiles.csv* table.

# Task

Using the provided data, find the age of the users specified in the *test_users.txt* list.
To do this, develop a method for calculating age, test it on known data, and apply it to unknown data.
The key data to solve the problem is information about users' friends.

## Statistical approach.

Apply statistics as a method for calculating age. 

## Machine Learning.

Using machine learning techniques as a method for calculating age, try to improve the accuracy of the statistical method.
