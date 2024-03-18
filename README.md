# Ex03 Time Table
## Date:14:3:24

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
        <title>My Time Table</title>
    </head>
    <body>
        <img src="logo.png" height="150" width="900">
        <table border="4" cellspacing="8" cellpadding="5" width="50" height="50">
        <caption>SLOT TIME TABLE- PRAJAN P (23013995)</caption>
        <tr>
            <th bgcolor="blue">Day/Time</th>
            <th bgcolor="blue">monday</th>
            <th bgcolor="blue">tuesday</th>
            <th bgcolor="blue">wednesday</th>
            <th bgcolor="blue">thursday</th>
            <th bgcolor="blue">friday</th>
            <th bgcolor="blue">saturday</th>
        </tr>
        <tr>
            <td bgcolor="blue">8-10</td>
            <td bgcolor="red">CHEM</td>
            <td bgcolor="red">ML</td>
            <td bgcolor="red">PLA</td>
            <td bgcolor="red">creativeskills</td>
            <td bgcolor="red">webdev</td>
            <td bgcolor="red"> ML</td>
        </tr>
        <tr>
            <td bgcolor="blue">10-12</td>
            <td bgcolor="red">eng</td>
            <td bgcolor="red">PLA</td>
            <td bgcolor="red">free</td>
            <td bgcolor="red">free</td>
            <td bgcolor="red">Cprogram</td>
            <td bgcolor="green">free</td>
        </tr>
        <tr>
            <td bgcolor="blue">12-1</td>
            <td colspan="6" bgcolor="green" align="center">LUNCH </td>
        </tr>
        <tr>
            <td bgcolor="blue">1-3</td>
            <td bgcolor="red">PLA</td>
            <td bgcolor="red">webdev</td>
            <td bgcolor="red">eng</td>
            <td bgcolor="red">webdev</td>
            <td bgcolor="green">free</td>
            <td bgcolor="red">CHEM</td>
        </tr>
        <tr>
            <td bgcolor="blue">3-5</td>
            <td bgcolor="red">Cprogram</td>
            <td bgcolor="green">free</td>
            <td bgcolor="green">free</td>
            <td bgcolor="green">free</td>
            <td bgcolor="green">free</td>
            <td bgcolor="red">PLA</td>
        </tr>
        </table>
        <table border="4" cellspacing="8" cellpadding="5" width="600" height="40">
            <tr>
                <th>S.no</th>
                <th>Subject code</th>
                <th>Subject name</th>
            </tr>
            <tr>
                <td>1.</td>
                <td>19EY702</td>
                <td>creative skills</td>
            </tr>
            <tr>
                <td>2.</td>
                <td>19EN101</td>
                <td>Communicative English</td>
            </tr>
            <tr>
                <td>3.</td>
                <td>19CY205</td>
                <td>Principles of Chemistry in Engineering</td>
            </tr>
            <tr>
                <td>4.</td>
                <td>19AI414</td>
                <td>Fundamentals of Web Application Development</td>
            </tr>
            <tr>
                <td>5.</td>
                <td>19AI410</td>
                <td>Introduction to Machine Learning</td>
            </tr>
            <tr>
                <td>6.</td>
                <td>19AI304</td>
                <td>Fundamentals of C programming</td>
            </tr>
            <tr>
                <td>7.</td>
                <td>19AI301C</td>
                <td>Python and Linear Algebra</td>
            </tr>

        </table>
    </body>
</html>
```


## OUTPUT
![image](https://github.com/Karthi051/slot/assets/148327224/fc589e22-edb6-48ec-8cd3-2ecc2990223c)




## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
