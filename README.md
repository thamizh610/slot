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
DEVELOPED BY:
Thamizarasan.S
212223220116
```
<!DOCTYPE html>
<html>
    <head>
        <title>
            THAMIZH
        </title>
        <link href="table.css" rel="stylesheet"/>
        <style>
             table {
            border-collapse: collapse;
            width: 30%;
            height: auto;
            margin: auto;
            

        }

        th, td {
            border: 2px solid black;
            padding: 8px;
            text-align: left;
        }

        th {
            background-color: #f2f2f2;
        }
        </style>
       
    </head>
    
    <body>
        <img class="logo" src="saveetha logo.jpg" alt="saveetha logo" >
        
       <p class="name">SLOT TIME TABLE-THAMIZARASAN.S</p>
        <table
          style="width:50%" >
            <tr class="hd">
                <th>TIMING</th>
                <th>MONDAY</th>
                <th>TUESDAY</th>
                <th>WEDNESDAY</th>
                <th>THURSDAY</th>
                <th>FRIDAY</th>
                <th>SATURDAY</th>
            </tr>
            <tr>
                <th>8am to 10am</th>
                <td class="nc">No Class</td>
                <td class="de">Digital Electronics</td>
                <td class="nc">No Class</td>
                <td class="de">Digital Electronics</td>
                <td class="fw">Fundamentals of Web Application Development</td>
                <td class="os">Operating System</td>
            </tr>
            <tr>
                <th>10am to 12pm</th>
                <td class="nc">No Classes</td>
                <td class="fw">Fundamentals of Web Application Development</td>
                <td class="py">Physics of Quantum Computing</td>
                <td class="nc">No class</td>
                <td class="c">Fundamentals of C Programming</td>
                <td class="ml">Introduction to Machine Learning</td>
            </tr>
            <tr>
                <th>1pm to 3pm </th>
                <td class="ml">Introduction to Machine Learnng</td>
                <td class="nc">No Class</td>
                <td class="nc">No Class</td>
                <td class="nc">No Class</td>
                <td class="nc">No Class</td>
                <td class="nc">No Class</td>
            </tr>
            <tr>

                <th>3pm to 5pm</th>
                <td class="c">Fundamentals of C Programming</td>
                <td class="py">Physics of Quantum Computing</td>
                <td class="fw">Fundamentals of Web Application Development</td>
                <td class="os">Operating System</td>
                <td class="nc">No Class</td>
                <td class="nc">No Class</td>
            </tr>
    
        </table>
        <br>
        

        <table>
            <tr>
                <th>S.NO</th>
                <th>Subject Code</th>
                <th>Subject Name</th>
            </tr>
            <tr>
                <th>1</th>
                <td>19Ai304</td>
                <td>Fundamentals of C Programming</td>
            </tr>
            <tr>
                <th>2</th>
                <td>19Ai410</td>
                <td>Introduction to Machine Learning</td>
            </tr>
            <tr>
                <th>3</th>
                <td>19Ai414</td>
                <td>Fundamenrals of Web Application Development</td>
            </tr>
            <tr>
                <th>4</th>
                <td>19CS405</td>
                <td>Operating System</td>
            </tr>
            <tr>
                <th>5</th>
                <td>19EE404</td>
                <td>Digital Electronics</td>
            </tr>
            <tr>
                <th>6</th>
                <td>19PH214</td>
                <td>Physics of Quantum Computing</td>
            </tr>
           
        </table>
       

    </body>
    
</html>
```


## OUTPUT
![image](https://github.com/thamizh610/slot/assets/150418511/9e6e1bbf-93a1-4a28-b20a-8be461210b56)



## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
