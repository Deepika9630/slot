# Ex03 Time Table
## Date:24.04.2025

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
			<title> Deepika R Time Table</title>
		</head>
		<body align="center">
	        <img src="/static/logo.png" height="200" width="800" >
		<table border="2" cellspacing="5" cellpadding="5" width="800" height="50" align="center">
	        <caption> SLOT TIME TABLE-Deepika.R(212224230054)</caption>
			<tr bgcolor="Light blue" align="center">
				<th>Day/Time</th>
				<th>Monday</th>
				<th>Tuesday</th>
	                        <th>Wednesday</th>
				<th>Thursday</th>
				<th>Friday</th>
			</tr>
			<tr bgcolor="gold" align="center">
				<th bgcolor="Light blue">8-10</th>
				<td>os</td>
				<td>FREE SLOT</td>
				<td>career devolepment skills</td>
				<td>os</td>
				<td>FREE SLOT</slot></td>
			</tr>
			<tr bgcolor="gold" align="center">
				<th bgcolor="Light Blue">10-12</th>
				<td>FREE SLOT</td>
				<td>python and lenear algebra</td>
				<td>python and lenear algebra</td>
				<td>web</td>
				<td>data science</td>
			</tr>
			<tr bgcolor="gold" align="center">
				<th bgcolor="LIght blue">12-1</th>
				<td colspan="5" align="center">LUNCH</td>
			</tr>
			<tr bgcolor="gold" align="center">
				<th bgcolor="Light Blue">1-3</th>
				<td>FREE SLOT</td>
				<td>web</td>
				<td>mentor meet</td>
				<td>probability</td>
				<td>FREE SLOT</td>
			</tr>
			<tr bgcolor="gold" align="center">
				<th bgcolor="Light Blue">3-5</th>
	                        <td>sotware engineering</td>
				<td>FREE SLOT</td>
				<td>python and lenear algebra</td>
				<td>data science</td>
				<td>probability</td>
				
</table>
<br>
<table border="2" cellspacing="5" cellpadding="5" width="800" height="50" align="center">
    <tr bgcolor="Light Blue" align="center">
        <th>S.No</th>
        <th>Subject Code</th>
        <th>Subject Name</th>
    </tr>
    <tr bgcolor="gold" align="center">
        <th bgcolor="light blue">1.</th>
        <td>19AI301C</td>
        <td>python and lenear algebra</td>
    </tr align="center">
    <tr bgcolor="gold" align="center">
        <th bgcolor="light blue">2.</th>
        <td>19AI414</td>
        <td>Fundamentals of Web Application Development(FWAD)</td>
    </tr>
    <tr bgcolor="gold" align="center">
        <th bgcolor="light blue">3.</th>
        <td>19CS405</td>
        <td>Operating System</td>
    </tr>
    <tr bgcolor="gold" align="center">
        <th bgcolor="light blue">4.</th>
        <td>19MA222</td>
        <td>Probability</td>
    </tr>
    <tr bgcolor="gold" align="center">
        <th bgcolor="light blue">5.</th>
        <td>19EY708</td>
        <td>Career Devolepment Skills</td>
    </tr>
    <tr bgcolor="gold" align="center">
        <th bgcolor="light blue">6.</th>
        <td>19AI403</td>
        <td>Introduction to Data Science</td>
    </tr>
    <tr bgcolor="gold" align="center">
        <th bgcolor="light blue">7.</th>
        <td>19CS408</td>
        <td>Software Engineering</td>
    </tr>
    <tr bgcolor="gold" align="center">
        <th bgcolor="light blue">8.</th>
        <td>ECA_M</td>
        <td>Mentor Meet</td>
    </tr>

</table>
</body>
```
## Output!
![alt text](<Screenshot 2025-04-24 162510.png>)



## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
