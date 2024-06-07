# Assignment 1
# Student id generation and percentage calculation
 Note:- This program will take input of number of subjects, marks obtained in that subject ,total marks for that subject , mobile number and name as input from the student . Then it will calculate percentages for that student and assign the roll number for him and then print the output on the text file present on the given path.
## Execution:
 This will ask for marks and mobile number again and again until valid entry is made .
 Operation will be terminated if invaid "name" and "subject name" is entered.
 By default data will be written on studentid.txt file on the "E" drive of your computer.


# Assignment 2
- In this part we took our previous logic to next level. 
- Here i have connected python notebook to the SQL server and created some classes of users . From this point all the entries being made will store and fetch the data from the SQL database.
- I have created a result site like programm in which users are classified in two types such as user class and admin class.
- Admin (in this case Teacher) can view, modify or delete data for all students
  > Admin view example.

  ![Admin class view example](https://github.com/ShubhamNimase/python_assignments/assets/155907618/16d068a5-0a9a-497a-8927-4e835ffe7a31)
- While users (students) can only view result of one person at a time with requirement of valid credentials (i.e username and roll number).
  > User View example.
  
   ![User class view example](https://github.com/ShubhamNimase/python_assignments/assets/155907618/e746eff6-3e57-4e90-a193-4b1fcbdb5dda)

# Assignment 3
- This part is based on performing operations on dataset by using 'padas' library which is a library in python used to handle dataframes.
- Here i have used superstore dataset to showcase data filtering techniques which can be easily performed by using pandas library and which includes sorting and filtering the dataframe by modifying the columns which includes data in the datetime format such as weekdays, months and years.
