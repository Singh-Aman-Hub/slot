# Ex03 Time Table
## Date: 10-03-2025

## AIM
To write a html webpage page to display your slot timetable.

## ALGORITHM
### STEP 1
Create a Django-admin Interface.

### STEP 2
Create a static folder and inert HTML code.

### STEP 3
Create a simple table using ```<table>``` tag in html.

### STEP 4
Add header row using ```<th>``` tag.

### STEP 5
Add your timetable using ```<td>``` tag.

### STEP 6
Execute the program using runserver command.

## PROGRAM
"""
'''
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Schedule</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            background-color: #f4f4f4;
            margin: 0;
            padding: 20px;
        }
        table {
            width: 60%;
            margin: 20px auto;
            border-collapse: collapse;
            background: #fff;
            box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
            border-radius: 8px;
            overflow: hidden;
        }
        th, td {
            padding: 12px;
            border: 1px solid #ddd;
            text-align: center;
        }
        th {
            background-color: #007BFF;
            color: white;
        }
        tr:nth-child(even) {
            background-color: #f9f9f9;
        }
        tr:hover {
            background-color: #f1f1f1;
        }
    </style>
</head>
<body>
    <img src="logo.png" height="100" width="540">
    <h2>Weekly Study Schedule</h2>
    <table>
        <tr>
            <th>Days/Time</th>
            <th>8hrs - 10hrs</th>
            <th>10hrs - 12hrs</th>
            <th>1hrs - 3hrs</th>
        </tr>
        <tr>
            <td>Monday</td>
            <td>Data Science</td>
            <td>Module Completion</td>
            <td>Machine Learning</td>
        </tr>
        <tr>
            <td>Tuesday</td>
            <td>Task Assignment</td>
            <td>Module Completion</td>
            <td>Module Completion</td>
        </tr>
        <tr>
            <td>Wednesday</td>
            <td>ML</td>
            <td>Web Dev</td>
            <td>DSA</td>
        </tr>
        <tr>
            <td>Thursday</td>
            <td>DSA</td>
            <td>Module</td>
            <td>Operating System</td>
        </tr>
        <tr>
            <td>Friday</td>
            <td>Webinar</td>
            <td>DSA</td>
            <td>Test</td>
        </tr>
    </table>    
</body>
</html>

'''
"""

## OUTPUT
![alt text](<Screenshot (1841).png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
