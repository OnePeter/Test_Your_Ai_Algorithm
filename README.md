# Test_Your_Ai_Algorithm
data for testing your AI Algorithm

Data structure:
  Data configure line
  [Head line]
  Data


Data configure line:
Ai_Data:RowCount,NoOfHeadLine,ColumnOfLabels,ColumnOfInput,ColumnOfResult,DataTypes

RowCount: DataRowCount, eg: 1000
NoOfHeadLine: 0- no head line, eg 0, or 1
ColumnOfLabels:Label for rows, eg 0, 1, or 2
ColumnOfResult: if start with -, it means count from end column backwards, without -, Result column first, Input column afterwards
  eg. 2, -1
DataTypes:  N-integer, B-Boolean (0,1)  V-value, C-category, S-string
  eg,  N2 - two columns of number
       N  - one column of number
       B3 - three columns of boolean
       V2 - two columns of values
 for category, it needs specify the number of category by using . 
  eg.  C2.5 -- two columns, each columns has 5 categories, such as, 0,1,2,3,4    

eg:
Ai_Data:300,1,1,2,-1,N,V2,C1.9

Ai_Data: Mark
300: the count of data row is 300
1: there is one line of data head
1: first column is label
2: two columns of input
-1: one column of result at end column (-:at end)
N,V2,C1.9:First column is number, two columns of value, last column if a category of 9 values

eg:
Ai_Data:100,0,0,2,1,B,V2
1,0.5,0.3
0,0.2,1.2

Ai_Data: Mark
100: the count of data row is 100
0: there is no data head
0: no label column
2: two columns of input
1: one column of result, result column first, then input column
B,V2:one boolean column, two columns of value

