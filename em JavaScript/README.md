# Algoritmos em JavaScript

### Recursão
~~~JavaScript
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>JS - Recursão</title>
</head>
<body>
    <h1>JavaScript - Recursão</h1>
    <script> 

    function pre(i, N){
        if (i==N) return;
        console.log("i: ", i);
        pre(i+1,N);
    }
    
    function pos(i, N){
        if (i==N) return;
        pos(i+1,N);
        console.log("i: ", i);
    }
    console.log("Impressão Pre-recursão: ");
    pre(0,3);
    
    console.log("Impressão Pos-recursão: ");
    pos(0,3);

    
    </script>
</body>
</html>
~~~
