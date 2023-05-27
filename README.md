# Ex.07 JavaScript - Simple Calculator
## AIM
  To write a program in JavaScript for implementing a simple calculator.

## ALGORITHM
### STEP-1
  Open notepad and type the HTML code.

### STEP-2
  Define a function to implement the simple calculator.

### STEP-3
  Using branching statements to find the corresponding operation.

### STEP-4
  Open the file in a browser and verify the output.
  
## CODE
```
<html>
<head>
<script type="text/javascript">
function calc()
{
var a=prompt("Enter 1st Value");
var b=prompt("Enter 2st Value");
var op=prompt("Enter Operation to Perform 1.Addition 2.Subtraction 3.Multiplication 4.Division");
var d;
if(op==1)
{
d=a+b;
alert(d);
}
else if(op==2)
{
d=a-b;
alert(d);
}
else if(op==3)
{
d=a*b;
alert(d);
}
else if(op==4)
{
d=a/b;
alert(d);
}
else
{
alert("Invalid Operation");
}
}
</script>
</head>
<body onload="calc()">
<h1>
Simple Calculator
</h1>
<hr color="red">
<p> 
Enter option for doing the corresponding operation
</p>
</body>
</html>
```
## OUTPUT
![calcul sc-1](https://github.com/Kiruthigamoorthi/Ex07_Web-Design/assets/127816726/c2be9606-01ad-4f03-8e94-e77dded7ccfa)
![calcul sc-2](https://github.com/Kiruthigamoorthi/Ex07_Web-Design/assets/127816726/4712359f-3ba0-4885-9b3d-833ee1373d36)
![calcul sc-3](https://github.com/Kiruthigamoorthi/Ex07_Web-Design/assets/127816726/12685d32-c4f3-4b77-aaad-85959a8d5625)
![cacul sc -4](https://github.com/Kiruthigamoorthi/Ex07_Web-Design/assets/127816726/045841e3-c4b3-43e1-8103-c6b17fe162f8)
![calcul sc-5](https://github.com/Kiruthigamoorthi/Ex07_Web-Design/assets/127816726/4fbaef4b-c28e-4bc0-892b-601eeee189e6)


## RESULT
  Implementation of a Simple Calculator using JavaScript is done successfully.
