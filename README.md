Question 1: Pandas Basics
1.1 Importing Pandas
Write the command to import the Pandas library and check its version.
1.2 Creating a DataFrame
Create a simple DataFrame using the following data:
Name     Age     City  
Alice    25      New York  
Bob      30      Los Angeles  
Charlie  35      Chicago  
Print the DataFrame.

Question 2: Pandas Series
2.1 Creating a Series
Create a Pandas Series from the list [100, 200, 300, 400, 500].
Print the Series.
2.2 Accessing Elements in a Series
From the Series created in Question 2.1, access the second and fourth elements and print them.
2.3 Series Operations
Create a second Series S2 with values [10, 20, 30, 40, 50].
Perform element-wise addition between the two Series (S1 from 2.1 and S2) and print the result.

Question 3: DataFrame Basics
3.1 DataFrame Column Access
Using the DataFrame created in Question 1.2, print only the 'Name' and 'City' columns.
3.2 Adding a New Column
Add a new column Salary to the DataFrame in Question 1.2 with the following values: [50000, 60000, 70000].
Print the updated DataFrame.
3.3 Basic Statistics on DataFrames
Using the updated DataFrame, calculate and print:
- The average Age
- The total sum of Salary

Question 4: Filtering and Indexing
4.1 Conditional Filtering
Filter the DataFrame from Question 3.2 to display rows where the Age is greater than 28.
Print the filtered DataFrame.
4.2 Setting and Resetting Index
Set the Name column as the index of the DataFrame and print the updated DataFrame.
Then reset the index to the default and print the DataFrame again.

Question 5: Working with CSV Data
5.1 Reading a CSV File
Assume you have a CSV file called employees.csv with the following content:
Name, Department, Salary  
John, Sales, 50000  
Jane, Marketing, 60000  
Emily, HR, 55000  


Write the code to read this CSV file into a Pandas DataFrame and print the contents of the DataFrame.
5.2 CSV Data Manipulation
From the DataFrame created in 5.1, perform the following tasks:
- Filter the rows where the Salary is greater than 55000.
- Print only the Name and Department columns for the filtered rows.

Question 6: Grouping and Aggregation
6.1 Grouping by Department
Using the DataFrame created in Question 5.1, group the data by the Department column and calculate the average Salary for each department.
Print the result.
6.2 Aggregation
For the same DataFrame, find the minimum and maximum Salary for each Department.

Question 7: Merging DataFrames
7.1 Merging Two DataFrames
You are given two DataFrames:
df1 = pd.DataFrame({
    'Name': ['John', 'Jane', 'Emily'],
    'Department': ['Sales', 'Marketing', 'HR']
})

df2 = pd.DataFrame({
    'Name': ['John', 'Jane', 'Emily'],
    'Experience (Years)': [5, 7, 3]
})


Write the code to merge these two DataFrames on the Name column.
Print the merged DataFrame.

Question 8: Sorting
8.1 Sorting Data
Sort the DataFrame from Question 7.1 based on the Experience (Years) column in descending order.
Print the sorted DataFrame.
