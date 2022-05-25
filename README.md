# calculator

<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="utf-8">
        <meta http-equiv="X-UA-Compatible" content="IE=edge">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <link rel="stylesheet" href="style.css">

        <title>Calculator</title>
    </head>

    <body>
        <form class="calculator" name="calc">
            <input class="value" type="text" name="txt" readonly="">
            <span class="num clear" onclick="document.calc.txt.value= ''">C</span>
            <span class="num" onclick="document.calc.txt.value += '/'"> / </span>
            <span class="num" onclick="document.calc.txt.value += '*'"> * </span>
            <span class="num plus" onclick="document.calc.txt.value +='+' "> + </span>
            <span class="num" onclick="document.calc.txt.value += '-'"> - </span>
            <span class="num" onclick="document.calc.txt.value +='00' "> 00 </span>
            <span class="num" onclick="document.calc.txt.value += '9'"> 9 </span>
            <span class="num" onclick="document.calc.txt.value += '8'"> 8 </span>
            <span class="num" onclick="document.calc.txt.value += '7'"> 7 </span>          
            <span class="num" onclick="document.calc.txt.value += '6'"> 6 </span>
            <span class="num" onclick="document.calc.txt.value += '5'"> 5 </span>
            <span class="num" onclick="document.calc.txt.value += '4'"> 4 </span>
            <span class="num" onclick="document.calc.txt.value += '3' "> 3 </span>
            <span class="num" onclick="document.calc.txt.value += '2' "> 2 </span>
            <span class="num" onclick="document.calc.txt.value += '1' "> 1 </span>
            <span class="num" onclick="document.calc.txt.value += '0' "> 0 </span>
            
            <span class="num equal" onclick="document.calc.txt.value= eval(calc.txt.value)">=</span>
        </form>

    </body>
</html>
