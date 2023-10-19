Hoy aprendí:
1. A modificar el tamanho de los títulos con font-size: 65 px;
2. a modificar el color del texto con h1 { color: black; }
3. a modificar el fondo de una lista <ul id="elnombrequequierasdarle"> así le atribuyes un id a una lista o a un párrafo, depende de lo que quieras hacer.
Luego con # buscas la id que hiciste para poner ahí lo que quieras. La llamas con el nombre que le diste a la id #nombrequequierasdarle {background-color: yellow; } ahí cambiaste el color de fondo de la lista.
4. Cambiar el fondo de la página entera dentro de <style> 
body {
    background-color: blue;
}
5. a crear una clase. Es lo mismo que una id pero con class. Es mejor pues puedes darle la modificación a más de una tag.




AQUÍ EL EJEMPLO:



<!DOCTYPE html>
<html lang="pt-br">
  <head>
    <meta charset="UTF-8">
    <title>HTML</title>
    <style>
        h1 {
            font-size: 65 px; 
            color: orange;
        }


    .fondo {
        background-color: yellow;
    }

    </style>
  </head>
  <body>
    <h1>Frutas</h1>
    <p class="fondo">Qual é a sua fruta favorita?</p>
    <ul class="fondo">
      <li>Maçã</li>
      <li>Banana</li>
      <li>Goiaba</li>
    </ul>
  </body>
</html>


:)