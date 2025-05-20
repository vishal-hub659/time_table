# Ex03 Time Table
# Date:28.11.2024
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
<html>

<head>
    <title>Timetable</title>
    <style>
        body {
             font-family:Arial, 
 sans-serif;
             background-color:
 #f8f9fa;
             margin: 0;
             padding: 0;
        }
        h1 {
            text-align: center;
            color: #343a40;
        }

        table {
            border-collapse:
  collapse;
            margin: 20px auto;
            background-color:
  #fff;
            border: 2px solid
  #dee2e6;
            box-shadow: 0 2px 4px
 rgba(0, 0, 0, 0.1);
        }

        th,
        td {
            border: 1px solid
  #dee2e6;
             padding: 10px;
             text-align: center; 
            }

            th{
                background-color:
  #f8f9fa;
            }

            .special {
                background-color:
   #f0f0f0;
            }
        </style>
      </head>

      <body>
          <h1>time table</h1>
          <table>
    
   <tr>
    <th>Days/Time</th>
    <th> 8-10 </th>
    <th> 10-12 </th>
    <th> 12-1 </th>
    <th> 1-3 </th>
    <th> 3-5 </th>
   </tr>

   <tr>
     <th>Monday</th>
     <td></td>
     <td>Web</td>
     <td>Break</td>
     <td>French</td>
     <td></td>
    </tr>

    <tr>
      <th>Tuesday</th>
      <td></td>
      <td>Physics</td>
      <td>Break</td>
      <td>Python</td>
      <td></td>
     </tr>

     <tr>
        <th>Wednesday</th>
        <td>Python</td>
        <td></td>
        <td>Break</td>
        <td>Mentor meeting</td>
        <td>Chemistry</td>
       </tr> 

       <tr>
         <th>Thursday</th>
         <td>French</td>
         <td>Python</td>
         <td>Break</td>
         <td>Web</td>
         <td></td>
        </tr>

        <tr>
           <th>Friday</th> 
           <td>Physics</td>
           <td></td>
           <td>Break</td>
           <td>Yoga</td>
           <td></td>
          </tr>

          <tr>
            <th>Saturday</th>
            <td>French</td>
            <td>Python</td>
            <td>Break</td>
            <td>Chemistry</td>
            <td>Web</td>
           </tr> 
    </table>

</body>
</html>
```
# OUTPUT
![Screenshot 2024-11-28 143305](https://github.com/user-attachments/assets/99de5a13-ce96-4234-8a00-d410f1f69b06)

# RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
