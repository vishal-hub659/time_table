# Ex03 Time Table
# Date:21.04.2025
# AIM
To write a html webpage page to display your slot timetable.

# ALGORITHM
## STEP 1
Create a Django-admin Interface.

## STEP 2
Create a static folder and inert HTML code.

## STEP 3
Create a simple table using `<table>` tag in html.

## STEP 4
Add header row using `<th>` tag.

## STEP 5
Add your timetable using `<td>` tag.

## STEP 6
Execute the program using runserver command.

# PROGRAM
```
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <center>
        <img src="aswin/timeapp/static/sec-logo-01as.jpg" height="100" ; width="540">
    </center>
    <style>
        table {
            border: 3px solid black;
            width: 80%;
            height: 100px;
            border-collapse: collapse;
            margin: 3px;
            margin-left: auto;
            margin-right: auto;

        }

        th,
        td {
            border: 5px solid black;
            padding: 20px;
            text-align: center;
        }

        tr {
            background-color: blue;
        }

        tr :nth-child(1) {
            background-color: red;
        }

        th {
            background-color: pink;
        }
    </style>

</head>

<body>
    <table>
        <tr>
            <th>Time</th>
            <th>Monday</th>
            <th>Tuesday</th>
            <th>Wednesday</th>
            <th>Thursday</th>
            <th>Friday</th>
            <th>Saturday</th>
        </tr>
        <tr>
            <td>8-10</td>
            <td colspan="6" ;align="center">Free Slot</td>
        </tr>
        <tr>
            <td>10-12</td>
            <td>Statistics</td>
            <td>CN</td>
            <td>Digital</td>
            <td>Probability</td>
            <td>CN</td>
            <td>Probability</td>
        </tr>
        <tr>
            <td>1-3</td>
            <td>OS</td>
            <td>Web</td>
            <td>Mentor Meet</td>
            <td>Statistics</td>
            <td>Web</td>
            <td>Free Slot</td>
        </tr>
        <tr>
            <td>3-5</td>
            <td colspan="3" ;align="center">Free Slot</td>
            <td>OS</td>
            <td>Digital</td>
            <td>Free Slot</td>
        </tr>
    </table>
    <table>
        <tr>
            <th>S.NO</th>
            <th>Subject Code</th>
            <th>Subject Name</th>
        </tr>
        <tr>
            <td>1</td>
            <td>19CY405</td>
            <td>Operating System</td>
        </tr>
        <tr>
            <td>2</td>
            <td>19MA211</td>
            <td>Statistics and Numerical Methods</td>
        </tr>
        <tr>
            <td>3</td>
            <td>19MA222</td>
            <td>Probability and Queueing Models</td>
        </tr>
        <tr>
            <td>4</td>
            <td>19AI414</td>
            <td>Fundamentals of Web Application Development</td>
        </tr>
        <tr>
            <td>5</td>
            <td>19EE404</td>
            <td>Digital Electronics</td>
        </tr>
        <tr>
            <td>6</td>
            <td>19CS406</td>
            <td>Computer Network</td>
        </tr>

    </table>
</body>

</html>

```
# OUTPUT
![alt text](<Screenshot 2025-04-01 153259.png>)
# RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
