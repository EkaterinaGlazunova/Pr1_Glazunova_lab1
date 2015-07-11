# Pr1_Glazunova_lab1
<!DOCTYPE HTML>
<html>
<head> 
<title>Задание 33</title> 
</head>
<body>

<script>

function task1()
{  
var x = prompt('Введите x', ''); 
var y = prompt('Введите y', '');
var res;
if (x>y)
{ res= y;
 
}
 else
{ res = x;
  
}
var max;
document.write("<p>Максимальное значение: "); 
max = res; 
document.write(res + "</p>"); 
}

function task2()
{
var x = prompt('Введите x', ''); 
var y = prompt('Введите y', '');
var min;  
if (y>x)
{ min= y;
 
}
 else
{ min = x;
  
}
var min;
document.write("<p>Минимальное значение: "); 
result = min; 
document.write(result + "</p>"); 
}


function task3()
{  
var x = prompt('Введите x', ''); 
var y = prompt('Введите y', '');
var res; var min;
if (x>y)
{ res= y;
 
}
 else
{ res = x;
  
}
var max;
document.write("<p>Максимальное значение: "); 
max = res; 
document.write(res + "</p>"); 


if (y>x)
{ min= y;}
 else
{ min = x;}
var result;
document.write("<p>Минимальное значение: "); 
result = min; 
document.write(result + "</p>"); 
}




</script>

<button onclick="task1()">А</button>
<button onclick="task2()">Б</button>
<button onclick="task3()">B</button>

</body>
</html>
