# SQL_Report

Overview:
This SQL code generates a comprehensive report showcasing student names, grades, and marks. It adheres to specific criteria where students with grades greater than or equal to 8 have their actual names displayed, and students with grades lower than 8 are represented by NULL in the name column. The report is sorted in descending order based on grades, and within each grade, it further considers the alphabetical order of names (for grades 8 and above) or the ascending order of marks (for grades below 8).

SQL Code:
The code utilizes a combination of CASE statements, JOIN operations, and the ORDER BY clause to achieve the desired result. It employs a UNION ALL to combine results for students with grades 8 and above and those with grades below 8. The WHERE clause filters students based on their grades, and the ORDER BY clause ensures the correct sorting order.
