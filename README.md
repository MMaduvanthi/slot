# Ex04 Time Table
## Date:21-11-2026

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
<head>
    <title>TABLE</title>
</head>
<body>
    <center>
        <img src="logo.png" alt="saveetha logo" width="650" height="100">
        
        <h1>MY TIME TABLE - MADUVANTHI M (26004344)</h1>
        <table border="1" cellpadding="12" style="background-color:cornflowerblue;">
            <tr style="background-color:aqua;">
                <th>Day/Time</th>
                <th>M0NDAY</th>
                <th>TUESDAY</th>
                <th>WEDNESDAY</th>
                <th>THURSDAY</th>
                <th>FRIDAY</th>
                <th>SATURDAY</th>
            </tr>
            <tr>
                <td style="background-color:aquamarine;">08:00-9:30</td>
                <td style="text-align: center;">EDM</td>
                <td style="text-align: center;">CDS</td>
                <td style="text-align: center;">EDM</td>
                <td style="text-align: center;">PYTHON</td>
                <td style="text-align: center;">PYTHON</td>
                <td style="text-align: center;">MATHS</td>
                
            </tr>
            <tr>
                <td  style="background-color:aquamarine;">9:45-11:15</td>
                <td style="text-align: center;">PYTHON</td>
                <td style="text-align: center;">GERMAN</td>
                <td style="text-align: center;">FREE</td>
                <td style="text-align: center;">FREE</td>
                <td style="text-align: center;">FREE</td>
                <td style="text-align: center;">FWAD</td>
            </tr>
            <tr>
                <td  style="background-color:aquamarine;">12:15-01:00</td>
                <td style="text-align: center;">MM</td>
                <td style="text-align: center;">MM</td>
                <td style="text-align: center;">MM</td>       
                <td style="text-align: center;">MM</td>
                <td style="text-align: center;">WEEK OFF</td>   
                <td style="text-align: center;">MM</td>
            </tr>
            <tr>
                <td  style="background-color:aquamarine;">01:15-02:45</td>
                <td style="text-align: center;">FREE</td>
                <td style="text-align: center;">FCC</td>
                <td style="text-align: center;">FREE</td>
                <td style="text-align: center;">FCC</td>
                <td style="text-align: center;">FWAD</td>
                <td style="text-align: center;">FWAD</td>
            
            
            </tr>
            <tr>
                <td style="background-color:aquamarine;">03:00-04:30</td>
                <td style="text-align: center;">FREE</td>
                <td style="text-align: center;">FREE</td>
                <td style="text-align: center;">MATHS</td>
                <td style="text-align: center;">GERMAN</td>   
                <td style="text-align: center;">FREE</td>
                <td style="text-align: center;">FREE</td>
             
            </tr>
        </table>
            <br>
            <br>
        <h2>SUB CODE & NAME</h2>
        <table border="1" cellpadding="12"  style="background-color:cornflowerblue;">
           <tr>
                <th style="background-color:aqua;">S.NO.</th>
                <th style="background-color:aqua;"> SUBJECT CODE</th>
                <th style="background-color:aqua;">SUBJECT NAME</th>

            </tr>
            <tr> 
                <td style="background-color:aquamarine;">1</td>
                <td>19AI302</td>
                <td>ENGINEERING DESIGN AND MODELLING</td>
            </tr>
            <tr>
                <td style="background-color:aquamarine;">2</td>
                <td>19AI301</td>
                <td>PYTHON PROGRAMMING</td>
            </tr>
            <tr>
                <td style="background-color:aquamarine;">3</td>
                <td>ECA-M</td>
                <td>SCOFT MENTOR MEET</td>
            </tr>
            <tr>
                <td style="background-color:aquamarine;">4</td>
                <td>19GE626</td>
                <td>GERMAN LANGUAGE A1 BASIC</td>
            </tr>
            <tr>
                <td style="background-color:aquamarine;">5</td>
                <td>19EY708</td>
                <td>CAREER DEVELOPMENT SKILLS</td>
            </tr>
            <tr>
                <td style="background-color:aquamarine;">6</td>
                <td>19CS547</td>
                <td>FUNDAMENTALS OF CRYPTOCURRENCY</td>
            </tr>
            <tr>
                <td  style="background-color:aquamarine;">7</td>
                <td>19AI414</td>
                <td>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</td>
            </tr>
            <tr>
                <td style="background-color:aquamarine;">8</td>
                <td>19MA201</td>
                <td>CALCULUS AND MATRIX ALGEBRA</td>
            </tr
            
           
        </table>
    </center>
</body>
</html>
```

## OUTPUT
![alt text](<Screenshot 2026-11-21 142510-1.png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
