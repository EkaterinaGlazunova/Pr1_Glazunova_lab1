# Pr1_Glazunova_lab1
<!DOCTYPE HTML>
 <html>
 <head> 
<title>Задание 102</title>
</head> 
<body> 
<form> 
 </form>
<script>
var x0=1;
var x;
var k = prompt('Введите количество','');
var i;
var m=0;
k = parseInt(k);
for(i=0;i<=k;i++)
{
x=x0;
x0 = (2-(Math.pow(x,3)))/5;
document.write(i+":"+x+"<br>");
}
x0=1;
x=1;
do 
{
x=x0;
x0 = (2-(Math.pow(x,3)))/5;
}
while (Math.abs(x0-x)>0.00001)
document.write("Результат: "+x0+"<br>");
</script>
 </body>
 </html> 
