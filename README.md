# Ex03 Time Table
## Date: 

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
<html>
    <head>
    <title>Slot Timetable</title>
    </head>
    <body>
        <center>
            <img src="saveetha logo.png" height="100" width="540">
        </center>
        <br>
        <table align="center" width="540" cellspacing="2" cellpadding="4" border="5" bgcolor="cyan">
            <caption><b>SLOT TIME TABLE - ASHIKA TR (212224220011)</b></caption>
            <tr align="center">
                <th bgcolor="yellow">Day/Time</th>
                <th bgcolor="yellow">Monday</th>
                <th bgcolor="yellow">Tuesday</th>
                <th bgcolor="yellow">Wednesday</th>
                <th bgcolor="yellow">Thursday</th>
                <th bgcolor="yellow">Friday</th>
                <th bgcolor="yellow">Saturday</th>

            </tr>
            <tr align="center">
                <th bgcolor="yellow">8-10</th>
                <td>FREE SLOT</td>
                <td>FREE SLOT</td>
                <td>FREE SLOT</td>
                <td>Software Engineering</td>
                <td>FREE SLOT</td>
                <td>FREE SLOT</td>

            </tr>
            <tr align="center">
                <th bgcolor="yellow">10-12</th>
                <td>ENVIRONMENTAL SCIENCE AND SUSTAINABILITY</td>
                <td>FREE SLOT</td>
                <td>BASIC ELECTRICAL AND ELECTRONIC ENGINEEERING</td>
                <td>FREE SLOT</td>
                <td>FUNDAMENTALS OF WEB APPLICATION</td>
                <td>HUMAN VALUES AND PROFEESIONAL ETHICS</td>

            </tr>
            <tr align="center">
                <th bgcolor="yellow">12-1</th>
                <th colspan="5" align="center"><b>LUNCH</b></th>
            </tr>
            <tr align="center">
                <th bgcolor="yellow">1-3</th>
                <td>PHYSICS FOR QUANTUM COMPUTING</td>
                <td>REASONING ABILITY</td>
                <td>MENTOR MEET</td>
                <td>CRYPTOCURRENCY</td>
                <td>CRYPTOCURRENCY</td>
                <td>BASIC ELECTRICAL AND ELECTRONIC ENGINEEERING</td>            
            </tr>
            <tr align="center">
                <th bgcolor="yellow">3-5</th>
                <td>FREE SLOT</td>
                <td>FREE SLOT</td>
                <td>PHYSICS FOR QUANTUM COMPUTING</td>
                <td>FUNDAMENTALS OF WEB APPLICATION</td>
                <td>FREE SLOT</td>
                <td>FREE SLOT</td>

            </tr>
        </table>
        <br>
        <table align="center" cellspacing="2" cellpadding="4" border="2">
            <tr align="center">
                <th>S.no</th>
                <th>Subject Code</th>
                <th>Subject Name</th>
            </tr>
            <tr>
                <td align="center">1.</td>
                <td align="center">19PH814</td>
                <td>PHYSICS FOR QUANTUM COMPUTING</td>
            </tr>
            <tr>
                <td align="center">2.</td>
                <td align="center">19EY709</td>
                <td>REASONING ABILITY</td>
            </tr>
            <tr>
                <td align="center">3.</td>
                <td align="center">19AI414</td>
                <td>FUNDAMENTALS OF WEB APPLICATION</td>
            </tr>
            <tr>
                <td align="center">4.</td>
                <td align="center">19EE305</td>
                <td>BASIC ELECTRICAL AND ELECTRONIC ENGINEEERING</td>
            </tr>
            <tr>
                <td align="center">5.</td>
                <td align="center">19CY801</td>
                <td>ENVIRONMENTAL SCIENCE AND SUSTAINABILITY</td>
            </tr>
            <tr>
                <td align="center">6.</td>
                <td align="center">19SH801</td>
                <td>HUMAN VALUES AND PROFEESIONAL ETHICS</td>
            </tr>
            <tr>
                <td align="center">7.</td>
                <td align="center">19PCS415</td>
                <td>CRYPTOCURRENCY</td>
            </tr>
        </table>
    </body>
</html>
```
## OUTPUT
![image](https://github.com/user-attachments/assets/4b0e146a-8ab4-4093-954e-0a793a8fc5c7)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
