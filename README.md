# Ex03 Time Table
## Date:12-11-2024

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
     <body>
        <table border="5" bgcolor="violet" cellspacing="20" cellpading="20">
            <caption>SLOT TIMETABLE - MUBARAK R (24900694)</caption>
               <tr bgcolor="yellow"> 
                <th bgcolor="yellow">Day/Time</th>
                <td>Monday</td>
                <td>Tuesday</td>
                <td>Wednesday</td>
                <td>Thursday</td>
                <td>Friday</td>
                <td>Saturday</td>
               </tr> 
                <tr>
                    <th bgcolor="yellow">8-10</th>
                    <td>Free Slot</td>
                    <td>Free Slot</td>
                    <td>Free Slot</td>
                    <td>python</td>
                    <td>FOWAD</td>
                    <td>DE</td>
                    </tr>
                <tr>
                        <th bgcolor="yellow">10-12</th>
                        <td>CHEM</td>
                        <td>CAMA</td>
                        <td>DE</td>
                        <td>BEEE</td>
                        <td>CHEM</td>
                        <td>FOWAD</td>
                </tr>
                         <tr>
                            <th bgcolor="yellow">12-01</th>
                            <th colspan="6">LunchBreak</th>
                        </tr>
                         <tr>
                            <th bgcolor="yellow">01-03</th>
                            <td colspan="2">FOWAD</td>
                            <td>MentorMeet</td>
                            <td colspan="2">BEEE</td>
                            <td>CAMA</td>
                         </tr>
                        </tr>
                    </tr>
                </tr>
        </table>
<br>
<table border="5">
    <tr>
        <th>S.No</th>
        <th>SubjectCode</th>
        <th>Subject name</th>
    </tr>
    <tr>
        <td>1</td>
        <td>19AI414</td>
        <td>Fundamentals of Web Application Development</td>
    </tr>
    <tr>
        <td>2</td>
        <td>19EE305</td>
        <td>Basic Electrical,Electronics and Measurement Engineering</td>
    </tr>
    <tr>
        <td>3</td>
        <td>19CY205</td>
        <td>Principles of Chemistry in Engineering</td>
    </tr>
    <tr>
        <td>4</td>
        <td>19MA201</td>
        <td>Calculus and Matrix Algebra</td>
    </tr>
    <tr>
        <td>5</td>
        <td>19EE404</td>
        <td>Digital Electronics</td>
    </tr>
    <tr>
        <td>6</td>
        <td>19AI301</td>
        <td>Python Programming</td>
    </tr>
    
</table>
     </body>
</html>
```
## OUTPUT
![alt text](<Screenshot (60).png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
