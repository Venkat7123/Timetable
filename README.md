# Ex03 Time Table
## Date: 17.11.2024

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
    <title>SLOT TIME TABLE: S.VENKATACHALAM 24900079</title>
    <style>
        img {
            padding-top: 3%;
            size: 100%;
            padding-bottom: 2%;
        }

        .ta {
            font-weight: 500;
            border-radius: 9px;
            background-color: black;
            width:65%;
            text-align: center;
        }

        tr,
        th,
        td {
            border-radius: 5px;

        }

        .id {
            background-color: rgb(236, 144, 144);
        }

        td {
            font-size: 15px;
        }

        .name {
            color: black;
        }

        caption {
            font-size: 48px;
            font-weight: 500;
            padding-bottom: 2%;
           
        }

        .idd {
            background-color: rgb(120, 206, 228);
        }

        .a {
            background-color: rgb(154, 233, 151);
        }

        .b {
            background-color: rgb(69, 147, 248);
        }

        .c {
            background-color: rgb(238, 189, 124);
        }

        .d {
            background-color: rgb(211, 166, 248);
        }
        .tab{
            background-color: black;
            font-weight: 500;
            border-radius: 9px;
            width: 65%;
            text-align: center;
        }
        .u {
            background-color: rgb(77, 215, 52);
        }
        .v {
            background-color: rgb(230, 127, 59);
        }
        .w{
            background-color: rgb(236, 64, 127);
        }
        .x {
            background-color: rgb(90, 88, 253);
        }
        .y {
            background-color: rgb(255, 83, 83);
        }
        .z{
            background-color: rgb(194, 125, 255);
        }
    </style>
</head>

<body>
    <center><img src="logo.png" width="1500"></center>
    <table class="ta" border="1" align="center" cellpadding="20">
        <caption>SLOT TIME TABLE: S.VENKATACHALAM 24900079</caption>
        <tr class="id">
            <th>Day/Time</th>
            <th>MONDAY</th>
            <th>TUESDAY</th>
            <th>WEDNESDAY</th>
            <th>THURSDAY</th>
            <th>FRIDAY</th>
            <th>SATURDAY</th>
        </tr>
        <tr class="idd">
            <th>8-10</th>
            <td>FREE SLOT</td>
            <td>19CS305</td>
            <td colspan="3">
                FREE SLOT
            </td>
            <td>19EE404</td>
        </tr>
        <tr class="a">
            <th>10-12</th>
            <td>FREE SLOT</td>
            <td>19MA201</td>
            <td>19AI301</td>
            <td>19CS305</td>
            <td>19EE404</td>
            <td>19AI414</td>
        </tr>
        <tr class="b">
            <th>12-1</td>
            <td colspan="6">
                LUNCH BREAK
            </td>
        </tr>
        <tr class="c">
            <th>1-3</td>
            <td>FREE SLOT</td>
            <td>19AI414</td>
            <td>MENTOR MEET</td>
            <td>19AI414</td>
            <td>19AI301</td>
            <td>19MA201</td>
        </tr>
        <tr class="d">
            <th>3-5</td>
            <td colspan="6">
                FREE SLOT
            </td>
        </tr>
        
        <table class="tab" border="1" align="center" cellpadding="20">
            <br><br>
            <tr class="u">
                <th>S.NO</th>
                <th>SUBJECT CODE</th>
                <th>SUBJECT NAME</th>
            </tr>
            <tr class="v">
                <td>1.</td>
                <td>19CS305</td>
                <td>Computer Architecture</td>
            </tr>
            <tr class="w">
                <td>2.</td>
                <td>19MA201</td>
                <td>Calculus And Matrix Algebra</td>
            </tr>
            <tr class="x">
                <td>3.</td>
                <td>19AI414</td>
                <td>Fundamentals of Web Application Development</td>
            </tr>
            <tr class="y">
                <td>4.</td>
                <td>19AI301</td>
                <td>Python Programming</td>
            </tr>
            <tr class="z">
                <td>5.</td>
                <td>19EE404</td>
                <td>Digital Electronics</td>
            </tr>
        </table>
</body>

</html>
```

## OUTPUT
![alt text](<Screenshot 2024-11-17 073937.png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
