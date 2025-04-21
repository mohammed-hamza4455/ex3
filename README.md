# Ex03 Time Table
## Date:21-04-2025

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
    <title>SLOT TIME TABLE - John Wilfred Thomas J W , reg no:212224040141</title>
    <style>
        table {
            border-collapse: collapse;
            width: 80%;
            margin: 5px auto;
        }

        table + table {
            margin-top: 20px;
        }

        th, td {
            border: 5px solid Black;
            text-align: center;
            padding: 8px;
        }

        img {
            width: 100%;
            height: 15%;
        }

        .center-text {
            text-align: center;
        }
        
        strong {
            font-weight: bold;
            font-size: 30px;
        }
    </style>
</head>
<body>
    <img src="logo.png">
    <div class="center-text">
        <p><strong>SLOT TIME TABLE - John Wilfred Thomas J W (212224040141) </strong></p>
    </div>
    <table>
        <tr>
            <th colspan="1" bgcolor="Yellow">Day/Time</th>
            <th colspan="1" bgcolor="Yellow">Monday</th>
            <th colspan="1" bgcolor="Yellow">Tuesday</th>
            <th colspan="1" bgcolor="Yellow">Wednesday</th>
            <th colspan="1" bgcolor="Yellow">Thursday</th>
            <th colspan="1" bgcolor="Yellow">Friday</th>
        </tr>
        <tr>
            <th colspan="1" bgcolor="Yellow">8-10</th>
            <th colspan="3" bgcolor="Cyan">FREE SLOT</th>
            <th colspan="2" bgcolor="Cyan">UI UX</th>
        </tr>
        <tr>
            <th colspan="1" bgcolor="Yellow">10-12</th>
            <th colspan="1" bgcolor="Cyan">WEB</th>
            <th colspan="1" bgcolor="Cyan">PY</th>
            <th colspan="1" bgcolor="Cyan">WEB</th>
            <th colspan="1" bgcolor="Cyan">REASONING</th>
            <th colspan="1" bgcolor="Cyan">BEEE</th>
        </tr>
        <tr>
            <th colspan="1" bgcolor="Yellow">12-1</th>
            <th colspan="5" bgcolor="Cyan">LUNCH</th>
        </tr>
        <tr>
            <th colspan="1" bgcolor="Yellow">1-3</th>
            <th colspan="1" bgcolor="Cyan">CN</th>
            <th colspan="1" bgcolor="Cyan">BLOCKCHAIN</th>
            <th colspan="1" bgcolor="Cyan">MENTOR MEET</th>
            <th colspan="1" bgcolor="Cyan">BEEE</th>
            <th colspan="1" bgcolor="Cyan">PY</th>
        </tr>
        </tr>
    </table>

    <table>
        <tr>
            <th colspan="1" bgcolor="White">S. No.</th>
            <th colspan="1" bgcolor="White">Subject Code</th>
            <th colspan="2" bgcolor="White">Subject Name</th>
        </tr>
        <tr>
            <th colspan="1" bgcolor="White">1.</th>
            <th colspan="1" bgcolor="White">19AI41</th>
            <th colspan="2" bgcolor="White">Fundamentals of Web Application Development(WEB)</th>
        </tr>
        <tr>
            <th colspan="1" bgcolor="White">2.</th>
            <th colspan="1" bgcolor="White">19AL301</th>
            <th colspan="2" bgcolor="White">Python Programming(PY)</th>        
        </tr>
        <tr>
            <th colspan="1" bgcolor="White">3.</th>
            <th colspan="1" bgcolor="White">19AL547</th>
            <th colspan="2" bgcolor="White">BLOCKCHAIN FOR BUSINESS(BLOCKCHAIN)</th> 
        </tr>
        <tr>
            <th colspan="1" bgcolor="White">4.</th>
            <th colspan="1" bgcolor="White">19EE305</th>
            <th colspan="2" bgcolor="White">BASIC ELECTRICAL,ELECTRONCS AND MEASUREMENT(BEEE)</th> 
        </tr>
        <tr>
            <th colspan="1" bgcolor="White">5.</th>
            <th colspan="1" bgcolor="White">19CS549</th>
            <th colspan="2" bgcolor="White">UI AND UX DESIGNS(UI UX)</th> 
        </tr>
        <tr>
            <th colspan="1" bgcolor="White">6.</th>
            <th colspan="1" bgcolor="White">19CS406</th>
            <th colspan="2" bgcolor="White">COMPUTER NETWORKS(CN)</th> 
        </tr>
        <tr>
            <th colspan="1" bgcolor="White">7.</th>
            <th colspan="1" bgcolor="White">19EY709</th>
            <th colspan="2" bgcolor="White">REASONING ABILITY(REASONING)</th> 
        </tr>
        <tr>
            <th colspan="1" bgcolor="White">8.</th>
            <th colspan="1" bgcolor="White">ECA-M</th>
            <th colspan="2" bgcolor="White">MENTOR MEET(MENTOR)</th> 
        </tr>
    </table>
</body>
</html>
```
## OUTPUT
![WhatsApp Image 2025-04-21 at 12 14 56_bdbad171](https://github.com/user-attachments/assets/c7cedeab-303b-44a7-aa1d-1be6edf2a89d)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
