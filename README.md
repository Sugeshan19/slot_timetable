# Ex03 Time Table
## Name: SUGESHAN
## Reg.no: 212224040337
## Date:03.04.2025

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

<head>
    <title>
        slot time table
    </title>
</head>
<body style="background-color: black;" text="white">
    <center>
        <h1>Slot Time Table - SUGESHAN 212224040337</h1>
        <img src="\static\logo.png" alt="Logo" width="750" height="100">
        <br>
        <table border="1" cellpadding="10" cellspacing="0" style="border-collapse: collapse; width: 80%; text-align: center;" bordercolor="yellow">
            <tr>
                <td>days</td>
                <td>Monday</td>
                <td>Tuesday</td>
                <td>Wednesday</td> 
                <td>Thursday</td>
                <td>Friday</td>
                <td>Saturday</td>            
            </tr>
            <tr>
                <td>8:00-10:00</td>
                <td>-</td>
                <td>-</td>
                <td>-</td>
                <td>-</td>
                <td>-</td>
                <td>-</td>

            </tr>
            <tr>
                <td>10:00-12:00</td>
                <td>c-proramming</td>
                <td>-</td>
                <td>calculus</td>
                <td>fundamentals of web</td>
                <td>-</td>
                <td>edm</td>
            </tr>
            <tr>
                <td>1:00-3:00</td>
                <td>-</td>
                <td>fundamentals of web</td>
                <td>mentor meet</td>
                <td>-</td>
                <td>c-programming</td>
                <td>chemistry</td>
            </tr>
            <tr>
                <td>3:00-5:00</td>
                <td>chemistry</td>
                <td>-</td>
                <td>edm</td>
                <td>probability</td>
                <td>calculus</td>
                <td>probability</td>
            </tr>
        </table>
    </center>
</body>

```

## OUTPUT 

![alt text](<Screenshot 2025-04-04 072824.png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
