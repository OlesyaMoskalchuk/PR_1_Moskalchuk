# PR_1_Moskalchuk
<!DOCTYPE HTML> 
<html>
 <head> <title>Задание1_42</title> 
</head> 
<body> 
<script> 
var x = prompt ('Введите число х',1);
var y = prompt ('Введите число у, не равное х',2);
+x;
+y;

var a; 
var b;

if (x==y)
{alert("Ошибка! Число х не должно равняться у!")}

if (x>y)
  {
   a = 2*x*y;
   b = x/2+y/2;
   alert (a); alert (b);
   }

else 
  if (x<y)
  {
   a = x/2+y/2;
   b = 2*x*y;
   alert (a); alert (b);
   }

</script> 
</body>
</html> 
