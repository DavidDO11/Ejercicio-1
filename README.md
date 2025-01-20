<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <script>

        // Aquí se define la función pintarNombre
        function pintarNombre(nombre, direccion, edad){
            Const	MAYORIA_EDAD = 18
			document.write(`El usuario se llama ${nombre} y tiene la direccion ${direccion} - `)

            if(edad>=MAYORIA_EDAD){
                document.write("Es mayor de edad <br>")
            }else{
                document.write("Es menor de edad <br>")
            }
        }

        //Aquí se llama a la función y se ejecuta.
        pintarNombre("David", "Diaz", parla)
		pintarNombre("Iker", "Sierra", parla)
		pintarNombre("Saúl", "Palomino", parla)
    </script>
    
</body>
</html>
