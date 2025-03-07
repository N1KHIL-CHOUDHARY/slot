# Ex03 Time Table
## Date:
07-03-2025
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
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        *{
    padding: 0;
    margin: 0;
}
body{
    display: flex;
    justify-content: center;
    background-color: rgb(202, 198, 198);
    width: 100%;
}
.t{
    display: flex;
    justify-content: center;
    background-color: rgb(202, 198, 198);
    flex-direction: column;
}
.logo{
    height: 100px;
    width: 800px;
}
.timetable{
    border: 1px;
    font-size: 20px;
}
    </style>
</head>
<body>
   <div class="t">
    <img src="logo.png" alt="" class="logo">

    <h3 style="text-align: center; margin: 30px  0px; text-decoration: underline; ">WEB DEVELOPMENT AND FUNDAMENTALS OF AI-BATCH</h3>
    <table class="timetable" border="3px">
        <tr>
            <th>Day</th>
            <th>8-10</th>
            <th>10-12</th>
            <th>1-3</th>
            
        </tr>
        <tr>
            <td>Monday</td>
            <td>Web Development</td>
            <td>Task Assignment</td>
            <td>Fundamentals of AI</td>
            
        </tr>
        <tr>
            <td>Tuesday</td>
            <td>Task Completion</td>
            <td>Web Development</td>
            <td >Module Completion</td>
            
        </tr>
        <tr>
            <td>Wednesday</td>
            <td>Assessment Hour</td>
            <td>Task Presentation</td>
            <td>Mentors Meet</td>
           
        </tr>
        <tr>
            <td>Thursday</td>
            <td>Task Presentation</td>
            <td>Module Completion</td>
            <td>Fundamentals of AI</td>
            
        </tr>
        <tr>
            <td>Friday</td>
            <td>Task Completion</td>
            <td>Web Development</td>
            <td>Task Completion</td>
            
        </tr>
        <tr>
            <td>Saturday</td>
            <td colspan="3 " style="text-align: center;">Module Assessment Completion</td>
        </tr>
    </table>
</body>
</html>

```

## OUTPUT

![alt text](image.png)
![alt text](<Screenshot (16).png>)
## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
