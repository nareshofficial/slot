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
<!DOCTYPE html>
<html lang="en">
<head>
<title>Slot Timetable</title>
</head>
<body>
<center>
<img src="logo.png" height="100" width="540">
</center>
<br>
<table align="center" width="540" cellspacing="2" cellpadding="4" border="5" bgcolor="cyan">
<caption><b>SLOT TIME TABLE - Naresh PS (</b></caption>
<tr align="center">
<th bgcolor="yellow">Day/Time</th>
<th bgcolor="yellow">Monday</th>
<th bgcolor="yellow">Tuesday</th>
<th bgcolor="yellow">Wednesday</th>
<th bgcolor="yellow">Thursday</th>
<th bgcolor="yellow">Friday</th>
</tr>
<tr align="center">
<th bgcolor="yellow">8-10</th>
<td colspan="1">FREE SLOT</td>
<td>CP T01</td>
<td>EDM</td>
<td>FREE</td>
<td>CP F01</td>

</tr>
<tr align="center">
<th bgcolor="yellow">10-12</th>
<td>EDM</td>
<td>FREE</td>
<td>SOFT SKILL</td>
<td>FREE</td>
<td>WEB</td>
</tr>
<tr>
<th bgcolor="yellow">12-1</th>
<td colspan="1" align="center">L U N C H</td>
<td colspan="1" align="center">MENTOR</td>
<td colspan="3" align="center"> L  U  N  C  H</td>
</tr>
<tr align="center">
<th bgcolor="yellow">1-3</th>
<td colspan="1">WEB</td>
<td>MATH</td>
<td>C</td>
<td>C</td>
<td>MATH</td>
</tr>
<tr align="center">
<th bgcolor="yellow">3-5</th>
<td colspan="1"> PHY </td>
<td>WEB</td>
<td>FREE</td>
<td>MATH</td>
<td>FREE</td>
</tr>
</table>
<br>
<table align="center" cellspacing="2" cellpadding="4" border="2">
<tr align="center">
<th>S. No.</th>
<th>Subject Code</th>
<th>Subject Name</th>
</tr>
<tr>
<td align="center">1.</td>
<td align="center">19AI414</td>
<td>Fundamentals of Web Application Development (FWAD)</td>
</tr>
<tr>
<td align="center">2.</td>
<td align="center">19AI302</td>
<td>ENGINEERING DESIGN AND MODELLING(EDM)</td>
</tr>
<tr>
<td align="center">3.</td>
<td align="center">19PH205</td>
<td>COMPUTATIONAL PHYSICS (PHY)</td>
</tr>
<tr>
<td align="center">4.</td>
<td align="center">19CS302</td>
<td>PROGRAMMING IN C (C)</td>
</tr>
<tr>
<td align="center">5.</td>
<td align="center">19MA201</td>
<td>Calculus and Matrix Algebra (MATH)</td>
</tr>
<tr>
<td align="center">6.</td>
<td align="center">19EY701</td>
<td>Soft Skills (SS)</td>
</tr>
</table>
</body>
</html>

## OUTPUT
![Screenshot 2024-01-02 033207](https://github.com/nareshofficial/slot/assets/155141830/15a6784f-141c-4c2e-9755-cc76f9aed8f5)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
