# Ex02 Time Table
## Date:28/11/2025

## AIM
To write a html webpage page to display your slot timetable.

## ALGORITHM
### STEP 1
Create a Django-admin Interface.

### STEP 2
Create an App inside the Django project.

### STEP 2
Create a static folder uder the created App and insert HTML code.

### STEP 3
Create a simple table using ```<table>``` tag in html with the relevant attributes.

### STEP 4
Add rows using ```<tr>``` tag.

### STEP 5
Add your course schedule using ```<td>``` tag.

### STEP 6
Execute the program using runserver command.

## PROGRAM
```
<html>
    <body>
        <img src="logo.png" alt="My Photo" height="120" width="650" align="center" ertitle="SEC Logo">

        <h3 height="140" width="700" >SLOT TIME TABLE - ARUNJUTHAN.M.A (25016022)</h3>
        <table border="10" cellpadding="8" cellspacing="8" bgcolor="cyan" height="120" width="650" >
            <tr bgcolor="yellow">
                <td>Day/Time</td>
                <td>Monday</td>
                <td>Tuesday</td>
                <td>Wednesday</td>
                <td>Thursday</td>
                <td>Friday</td>
                <td>Saturday</td>
            </tr>
            <tr>
                <td bgcolor="yellow">8-10</td>
                <td>FREE SLOT</td>
                <td>PYTH</td>
                <td colspan="2">FREE SLOT</td>
                
                <td>FWAD</td>
                <td>FREE SLOT</td>
            </tr>
             <tr>
                <td bgcolor="yellow">10-12</td>
                <td>FREE SLOT</td>
                <td>ENG</td>
                <td>PYTH</td>
                <td>FREE SLOT</td>
                <td>FWAD</td>
                <td>FWAD</td>
            </tr>
             <tr>
                <td  bgcolor="yellow">12-1</td>
                <td colspan="6">LUNCH</td>
            </tr>
             <tr>
                <td bgcolor="yellow">1-3</td>
                <td>FWAD</td>
                <td>FWAD</td>
                <td>Mentor Meet</td>
                <td>FREE SLOT</td>
                <td>ENG</td>
                <td>FREE SLOT</td>
            </tr>
             <tr>
                <td bgcolor="yellow">3-5</td>
                <td>ENG</td>
                <td>PYTH</td>
                <td>PYTH</td>
                <td>ENG</td>
                <td>PYTH</td>
                <td>ENG</td>
            </tr>


        </table>


        
        <table border="10" cellpadding="8" cellspacing="8" height="120" width="650" >
            <tr>
                <td>S.No.</td>
                <td>Subject Code</td>
                <td>Subject Name</td>
            </tr>
            <tr>
                <td>1.</td>
                <td>19AI414</td>
                <td>Fundamentals of Web Application Development(FWAD)</td>
            </tr>
            <tr>
                <td>2.</td>
                <td>19EN101</td>
                <td>Communicative English(ENG)</td>
            </tr>
            <tr>
                <td>3.</td>
                <td>19AI301</td>
                <td>Python Programming(PYTH)</td>
            </tr>
        </table>
    </body>
</html>

```

## OUTPUT
![alt text](<Screenshot 2025-11-28 183655.png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
