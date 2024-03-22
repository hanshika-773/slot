# Ex03 Time Table
## Date: 22.03.2024

## AIM.
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
<title>Slot Timetable</title>
</head>
<body bgcolor="black">
<center>
<img src="/static/logo.png" height="100" width="540">
</center>
<br>
<table align="center" width="600" cellspacing="2" cellpadding="4" border="3" bgcolor="white" bordercolor="black">
<caption><b><font color="white">SLOT TIME TABLE - Hanshika Varthini R (212223240046)</font></b></caption>
<tr align="center">
<th bgcolor="white">Day/Time</th>
<th bgclor="grey">Monday</th>
<th bgcolor="grey">Tuesday</th>
<th bgcolor="grey">Wednesday</th>
<th bgcolor="grey">Thursday</th>
<th bgcolor="grey">Friday</th>
<th bgcolor="grey">Saturday</th>
</tr>
<tr align="center">
<th bgcolor="silver">8-10</th>
<td bgcolor="plum">Fundamentals of Web Application Development</td>
<td bgcolor="lavender">Transforms and its Applications</td>
<td bgcolor="pink">Advance in C Programming</td>
<td bgcolor="rosybrown">Free slot </td>
<td bgcolor="gold">Computer Networks</td>
<td bgcolor="rosybrown">Free slot</td>
</tr>
<tr align="center">
<th bgcolor="silver">10-12</th>
<td bgcolor="skyblue">Embedded Board Design</td>
<td bgcolor="rosybrown">Free slot</td>
<td bgcolor="gold">Computer Networks</td>
<td bgcolor="lavender">Transforms and its Applications</td>
<td bgcolor="wheat">Creative Skills for Communication</td>
<td bgcolor="rosybrown">Free slot</td>
</tr>
<tr>
<th bgcolor="silver">12-1</th>
<td colspan="6" align="center" bgcolor="palegoldenrod">L U N C H</td>
</tr>
<tr align="center">
<th bgcolor="silver">1-3</th>
<td bgcolor="tan">Engineering Mechanics and Product Development</td>
<td bgcolor="rosybrown">Free slot</td>
<td bgcolor="pink">Advance in C Programming</td>
<td bgcolor="plum">Fundamentals of Web Application Development</td>
<td bgcolor="plum">Fundamentals of Web Application Development</td>
<td bgcolor="tan">Engineering Mechanics and Product Development</td>
</tr>
<tr align="center">
<th bgcolor="silver">3-5</th>
<td bgcolor="rosybrown">Free slot</td>
<td bgcolor="rosybrown">Free slot</td>
<td bgcolor="rosybrown">Free slot</td>
<td bgcolor="skyblue">Embedded Board Design</td>
<td bgcolor="rosybrown">Free slot</td>
<td bgcolor="rosybrown">Free slot</td>
</tr>
</table>
<br>
<table align="center" cellspacing="2" cellpadding="4" border="2" bordercolor="black">
<tr align="center" bgcolor="silver">
<th>S.No.</th>
<th>Subject Code</th>
<th>Subject Name</th>
</tr>
<tr bgcolor="tan">

<td align="center">1.</td>
<td align="center">19AI303</td>
<td>Engineering Mechanics and Product Development</td>
</tr>
<tr bgcolor="pink">
<td align="center">2.</td>
<td align="center">19AI305</td>
<td>Advance in C Programming</td>
</tr>
<tr bgcolor="plum">
<td align="center">3.</td>
<td align="center">19AI414</td>
<td>Fundamentals of Web Application</td>
</tr>
<tr bgcolor="gold">
<td align="center">4.</td>
<td align="center">19CS406</td>
<td >Computer Networks</td>
</tr>
<tr bgcolor="skyblue">
<td align="center">5.</td>
<td align="center">19CS542</td>
<td>Embedded Board Design</td>
</tr>
<tr bgcolor="wheat">
<td align="center">6.</td>
<td align="center">19EY702</td>
<td>Creative Skills for Communication</td>
</tr>
<tr bgcolor="lavender">
<td align="center">7.</td>
<td align="center">19MA219</td>
<td>Transforms and its Application</td>
</tr>
</font>
</table>
</body>
</html>
```

## OUTPUT
![Screenshot 2024-03-22 202255](https://github.com/hanshika-773/slot/assets/153576501/267db72e-cb56-4699-8de5-3b0af943ab4d)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
