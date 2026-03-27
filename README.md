# EX 08 CAMU SCHEDULE USING BOOTSTRAP

## DATE : 24/03/26

## AIM : 

To design a responsive and visually appealing CAMU Schedule using Bootstrap.

## DESIGN STEPS :

### STEP : 1

Clone the repository from GitHub.

### STEP : 2

Create Django Admin project.

### STEP : 3

Create a New App under the Django Admin project.

### STEP : 4

Add the Bootstrap CDN link inside the ```<head>``` section.

### STEP : 5

Insert a table element with Bootstrap table classes.

### STEP : 6

Construct the complete table.

### STEP : 7

Add a header/footer displaying copyright information.

### STEP : 8

Publish the website in the LocalHost.

## PROGRAM :

NAME : ANTONY ABISHEK K

REG NO : 212223240009

### camu.html

```
<html>
    <head>
        <title>Timetable</title>
        <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/css/bootstrap.min.css">
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.7.1/jquery.min.js"></script>
  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/js/bootstrap.min.js"></script>
    </head>
    <body>
        <img src="logo.png">
        <table class="table table-hover">
            <center>
            <b>CAMU TIMETABLE ABINAYA(25014971)</b>
            </center>
            <tr>
                <th>Day/Time</th>
                <th>Monday</th>
                <th>Tuesday</th>
                <th>Wednesday</th>
                <th>Thursday</th>
                <th>Friday</th>
                <th>Saturday</th>
            </tr>
            <tr>
                <th>8-10</td>
                <td>FWAD</td>
                <td>C</td>
                <td>FWAD</td>
                <td>FREE</td>
                <td>FWAD</td>
                <td>C</td>
            </tr>
            <tr>
                <th >10-12</td>
                <td >C</td>
                <td >FWAD</td>
                <td >FREE</td>
                <td>CN</td>
                <td >FREE</td>
                <td >FWAD</td>
            </tr>
            <tr>
                <th >12-1</th>
                <td  colspan="6" align="center">LUNCH</td>
            </tr>
            <tr>
                <th>1-3</td>
                <td  colspan="2" align="center">FREE</td>
                <td >MENTOR MEET</td>
                <td >C</td>
                <td colspan="2" align="center">CN</td>
            </tr>
            <tr>
                <th>3-5</th>
                <td >CN</td>
                <td>FREE</td>
                <td  colspan="2" align="center">CN</td>
                <td >C</td>
                <td>FREE</td>
            </tr>
        </table>
    </body>
</html>
<br>
<html>
    <body>
        <table class="table table-striped">
            <tr>
                <th>S.No</th>
                <th>Subject Code</th>
                <th>Subject Name</th>
            </tr>
            <tr>
                <th>1.</th>
                <td>19AI414</th>
                <td>Fundamentals of Web Application Develpoment</th>
            </tr>
            <tr>
                <th>2.</th>
                <td>19CS406</th>
                <td>Computer Network</th>
            </tr>
            <tr>
                <th>3.</th>
                <td>19AI304</th>
                <td>Fundamentals of C Programming</th>
            </tr>
        </table>
    </body>
</html>
```

## OUTPUT :

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/a53ef6ed-36da-4de3-a910-9da90dadabb2" />

## RESULT :

A responsive and visually appealing CAMU Schedule web page using Bootstrap is designed successfully.
