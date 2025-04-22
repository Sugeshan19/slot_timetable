# Ex03 Time Table
## Name: sugeshan
## Reg.no: 212224040337
## Date:15.04.2025

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

<html> 
<head> 
<title>Slot Timetable</title> 
</head> 
<body style="background-color: black;" text="white">
<center> 
<img src="/static/logo.png" height="100" width="540"> 
</center>
<br>
<table align="center" cellspacing="2" cellpadding="4" border="2"> 
<tr align="center"> 
<th>S. No.</th> 
<th>Subject Code</th> 
<th>Subject Name</th> 
</tr> 
<tr> 
<td align="center">1.</td> 
<td align="center">19AI302</td> 
<td>EDM</td> 
</tr> 
<tr> 
<td align="center">2.</td> 
<td align="center">19A1304</td> 
<td>FUNDAMENTALS OF C PROGRAMMING (C PROGRAM)</td> 
</tr> 
<tr> 
<td align="center">3.</td> 
<td align="center">19A1414</td> 
<td>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT (FWAD)</td> 
</tr> 
<tr> 
<td align="center">4.</td> 
<td align="center">19CY205</td> 
<td>PRINCIPLES IN CHEMISTRY ENGINEERING (CHE)</td> 
</tr> 
<tr> 
<td align="center">5.</td> 
<td align="center">19SH201</td> 
<td>CALCULUS</td> 
</tr> 
<tr> 
<td align="center">6.</td> 
<td align="center">19SH202</td> 
<td>PROBABILITY</td> 
</tr> 
</table> 

<center>
    <h1>Slot Time Table - Sugeshan.S 212224040337</h1>
    <br>
    <table border="1" cellpadding="10" cellspacing="0" style="border-collapse: collapse; width: 80%; text-align: center;" bordercolor="yellow">
        <tr>
            <td>DAYS</td>
            <td>MONDAY</td>
            <td>TUESDAY</td>
            <td>WEDNESDAY</td> 
            <td>THURSDAY</td>
            <td>FRIDAY</td>
            <td>SATURDAY</td>            
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
            <td>C-PROGRAMMING</td>
            <td>-</td>
            <td>CALCULUS</td>
            <td>FUNDAMENTAL OF WEB APPLICATION</td>
            <td>-</td>
            <td>EDM</td>
        </tr>
        <tr>
            <td>1:00-3:00</td>
            <td>-</td>
            <td>FUNDAMENTAL OF WEB APPLICATION</td>
            <td>MENTOR MEET</td>
            <td>-</td>
            <td>C-PROGRAMMING</td>
            <td>CHEMISTRY</td>
        </tr>
        <tr>
            <td>3:00-5:00</td>
            <td>CHEMISTRY</td>
            <td>-</td>
            <td>EDM</td>
            <td>PROBABILITY</td>
            <td>CALCULUS</td>
            <td>PROBABILITY</td>
        </tr>
    </table>
</center>

</body> 
</html>

```

## OUTPUT 

![alt text](<Screenshot 2025-04-22 185742.png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
