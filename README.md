<html>
<head>
<title> Pattern in JavaScript</title>
</head>
<body>
<script type="text/javascript">
var i,j;
for (i = 0; i < 10; i++) { 
for (j = 0; j < 10 / 2; j++) { 
if ((j == 0 || j == 10 / 2) && i != 0 || i == 0 && j != 0 && j != 10 / 2 || i == 10 / 2) 
document.write('*'); 
else
document.write(' '); 
} 
document.write(<br/>); 
} 
</script>
</body>
</html>                       
