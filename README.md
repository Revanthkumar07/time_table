# Ex03 Time Table
# Date:07-04-2025
# AIM
To write a html webpage page to display your slot timetable.

# ALGORITHM
## STEP 1
Create a Django-admin Interface.

## STEP 2
Create a static folder and inert HTML code.

## STEP 3
Create a simple table using `<table>` tag in html.

## STEP 4
Add header row using `<th>` tag.

## STEP 5
Add your timetable using `<td>` tag.

## STEP 6
Execute the program using runserver command.

# PROGRAM
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Time Table 📆</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #fff0f5;
            text-align: center;
            padding: 20px;
        }

        img {
            max-width: 100%;
            height: auto;
        }

        h2 {
            color: #c71585;
        }

        table {
            margin: 20px auto;
            border-collapse: collapse;
            width: 90%;
            background-color: rgb(228, 119, 163);
        }

        th, td {
            border: 2px solid #fff;
            padding: 10px;
            text-align: center;
        }

        th {
            background-color: #d87093;
            color: white;
        }

        .day-header {
            background-color: rgb(228, 119, 163);
        }

        .subject-table {
            background-color: lavender;
        }

        .subject-table th, .subject-table td {
            background-color: plum;
        }

        .lunch-cell {
            writing-mode: vertical-rl;
            text-orientation: mixed;
            font-weight: bold;
        }
    </style>
</head>
<body>

    <img src="\static\WhatsApp Image 2025-04-07 at 20.08.18_f597b1d1.jpg" alt="Screenshot">
    
    <h2>TIME TABLE - REVANTH</h2>

    <table>
        <thead>
            <tr>
                <th>DAYS</th>
                <th>8-10</th>
                <th>10-12</th>
                <th>12-1</th>
                <th>1-3</th>
                <th>3-5</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <th class="day-header">MONDAY</th>
                <td>-</td>
                <td>EVS</td>
                <td rowspan="6" class="lunch-cell">LUNCH ~</td>
                <td>-</td>
                <td>BEEE</td>
            </tr>
            <tr>
                <th class="day-header">TUESDAY</th>
                <td>-</td>
                <td>PYTHON</td>
                <td>WEB APPLICATIONS</td>
                <td>-</td>
            </tr>
            <tr>
                <th class="day-header">WEDNESDAY</th>
                <td>-</td>
                <td>PYTHON</td>
                <td>Mentor Meeting</td>
                <td>PYTHON</td>
            </tr>
            <tr>
                <th class="day-header">THURSDAY</th>
                <td>-</td>
                <td>C PROGRAMMING</td>
                <td>-</td>
                <td>-</td>
            </tr>
            <tr>
                <th class="day-header">FRIDAY</th>
                <td>-</td>
                <td>C PROGRAMMING</td>
                <td>WEB APPLICATIONS</td>
                <td>-</td>
            </tr>
            <tr>
                <th class="day-header">SATURDAY</th>
                <td>-</td>
                <td>PYTHON</td>
                <td>REASIONING ABILITY</td>
                <td>BEEE</td>
            </tr>
        </tbody>
    </table>

    <h2>Subject Codes & Details</h2>
    <table class="subject-table">
        <thead>
            <tr>
                <th>S.no</th>
                <th>SUBJECT CODE</th>
                <th>SUBJECT NAME</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>1.</td>
                <td>19AI304</td>
                <td>C PROGRAMMING</td>
            </tr>
            <tr>
                <td>2.</td>
                <td>19AI301C</td>
                <td>PYTHON</td>
            </tr>
            <tr>
                <td>3.</td>
                <td>19AI414</td>
                <td>WEB APPLICATIONS</td>
            </tr>
            <tr>
                <td>4.</td>
                <td>19CY801</td>
                <td>EVS</td>
            </tr>
            <tr>
                <td>5.</td>
                <td>19EE305</td>
                <td>BEEE</td>
            </tr>
            <tr>
                <td>6.</td>
                <td>19EY709</td>
                <td>REASIONING ABILITY</td>
            </tr>
            <tr>
                <td>7.</td>
                <td>ECA-M-SCOFT</td>
                <td>Mentor Meet</td>
            </tr>
        </tbody>
    </table>

</body>
</html>

```
# OUTPUT
![alt text](<Screenshot 2025-04-07 203146.png>)
# RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
