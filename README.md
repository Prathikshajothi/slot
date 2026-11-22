# Ex04 Time Table
## Date:18/11/2026

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
slot.html

<html>
    <head>
        <title>Time Table</title>
        <img src="logo.png" style="display:block ; margin: auto; margin-left:auto; margin-right: auto ; width: 100%; max-width: 580px ; height: auto;"><br><br>
    </head>
    <body>
        
     <table align="center" border="1" cellspacing="2" cellpading="12" >
     
        <tr bgcolor="lightpink" align="center">
            <td> Day/Time </td>
            <td> Monday </td>
            <td> Tuesday </td>
            <td> Wednesday </td>
            <td> Thursday </td>
            <td> Friday </td>
            <td> Saturday </td>
        </tr>

        <tr align="center">
            <td bgcolor="lightgrey"> 08:00-09:30 </td>
            <td> free slot </td>
            <td> free slot </td>
            <td> FWAD </td>
            <td> free slot </td>
            <td> CA </td>
            <td> CMA </td>
        </tr>
        
        <tr align="center">
            <td bgcolor="lightgrey"> 09:30-11:15 </td>
            <td> FWAD </td>
            <td> Python </td>
            <td> free slot </td>
            <td> python </td>
            <td> free slot </td>
            <td> python </td>
        </tr>

        <tr>
            <td bgcolor="lightgrey"> 11:30-12:15 </td>
            <td colspan="6" align="center"> Mentor Meet or Event </td>
        </tr>

         <tr>
            <td bgcolor="lightgrey"> 12:15-01.15 </td>
            <td colspan="6" align="center"> Lunch Break </td>
        </tr>

        <tr align="center">
            <td bgcolor="lightgrey"> 01.15-02.44 </td>
            <td> SE </td>
            <td> FWAD </td>
            <td> Free Slot </td>
            <td> SE </td>
            <td> free slot</slot> </td>
            <td> CA </td>
        </tr>

        <tr align="center">
            <td bgcolor="lightgrey"> 03:00-04:30 </td>
            <td> Free Slot </td>
            <td> EDM </td>
            <td> CMA </td>
            <td> free slot </td>
            <td> Free Slot </td>
            <td> EDM </td>
        </tr>

     </table><br><br>
     <table align="center" border="1" cellspacing="2" cellpading="12">
      <caption align="center" style="font-family:'Times New Roman', Times, serif; font: size 45px;"><b>SLOT TIME TABLE - Prathiksha J[26015225]</b></caption>

     <tr bgcolor="lightblue" align="center">
        <td> S.No </td>
        <td> Subject Code </td>
        <td> Subject Name </td>
     </tr>
     <tr align="center">
        <td> 1. </td>
        <td> 19AI414 </td>
        <td> Fundamentals of Web Application Development(FWAD) </td>
     </tr>
     <tr align="center">
        <td> 2. </td>
        <td> 19AI301 </td>
        <td> Python Programming(Python) </td>
     <tr align="center">
        <td> 3. </td>
        <td> 19AI302 </td>
        <td> Engineering Design And Modelling(EDM) </td>
     <tr align="center">
        <td> 4. </td>
        <td> 19CS305 </td>
        <td> Computer Architecture(CA)</td>
     <tr align="center">
        <td> 6. </td>
        <td> 26ODJO17 </td>
        <td> Calculus and matrix algebra(CMA)</td>
     <tr align="center">
        <td> 7. </td>
        <td> 260oDJ146 </td>
        <td> Software engineering(SE)</td>
     </tr>
    
     </table>
    </body>
</html>

```


## OUTPUT
![alt text](<Screenshot (45).png>)
![alt text](<Screenshot (46).png>)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
