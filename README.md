# Formulario-html
num1 e num2


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Formulario</title>
</head>
<body>
    <h1>Formulario</h1>

<menu>
<a href="/hello.html">Voltar</a>

</menu>

<form method="POST" action="/recebeDados.php">

</form>
   <!-- Aqui dentro e um form-->
   Primeiro numero: <input type="number" name="num1" placeholder="Digite seu numero aqui">
   <br>
   Segundo numero: <input type="number" name="num2" placeholder="Digite seu numero aqui">
   <br>
  
   <input type="submit" value="Enviar">
    </form>

</body>
</html>


=========================================================================================================
recebeDados.php

<?php

$num1 = $_POST['num1'];
$num2 = $_POST['num2'];

Echo  "Digite um numero :</br>" ;
Echo  "Digite outro numero: </br>";

$soma == $num1 + $num2;
echo "A soma dos numeros e :</br> $soma";

$sub == $num1 - $num2;
echo "A subtração dos numeros e :</br> $sub";

$mult == $num1 * $num2;
echo "A multiplicação  dos numeros e :</br> $mult";

$div == $num1 / $num2;
echo "A divisão   dos numeros e :</br> $div";

//var_dump($num1);
//var_dump($num2);
