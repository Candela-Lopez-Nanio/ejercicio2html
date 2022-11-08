# ejercicio2htmlform

<!DOCTYPE html>
<html>
    <head>
        <title> "Ejercicio 02 - Formularios en HTML"</title>
    </head>
    <body>
        <h3>Ejercicio 02 - Formularios en HTML</h3>
        <form action="/">
            <div>
                <label for="nombre">nombre </label>
                <input type="name" name="nombre" id="nombre">
            </div>
            <br>
            <div>
                <label for="edad">edad </label>
                <input type="number" name="edad"  id="edad">
            </div>
            <br>
            <div>
                <label form="frase-favorita"> frase-favorita </label>
                <textarea name="comentarios"id="comentarios"> </textarea>
            </div>
            <br>
        </form> 
        <button type="submit">Enviar</button>
        <button type="reset">Reset</button>
    </body>
</html>
