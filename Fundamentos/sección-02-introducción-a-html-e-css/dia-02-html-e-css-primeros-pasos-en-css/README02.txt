Hoy aprendí aprendí:
1. modificar las fuentes con font-family: arial;
2. modificar el tamanho de la fuente font-size: 15px;
3. modificar el grosor de la fuente font-weight: 300; o en negrita font-weight: bold;
4. modificar el estilo de la fuente a cursiva font-style: italic;
5. mdificar el espaciado line-height: 30px;
6. modificar la alineación de un texto text-align: center o right o left;
7. modificar la decoración de un texto text-decoration: underline; por ejemplo.
8. modificar el color de fondo de la página web body { background-color: marron; }


AQUÍ DEJO EL LENGUAJE DE MARCACIÓN:



<!DOCTYPE html>
<html lang="pt-br">
  <head>
    <meta charset="UTF-8">
    <title>HTML</title>
    <style>
    

h1 {
    font-family: sans-serif;
    color:chocolate;
    text-align: center;
}

h3 {
    color:rgb(97, 46, 10);
    text-align: center;
}

p {
    font-weight: 50;
    font-style: inherit;
    line-height: 25px;
    color:coral;
    text-align: left;
}

body {
    font-size: 16px;
    background-color: rgb(255, 255, 255);
    font-family:Lucida Sans;
}

ul {
    color:rgb(97, 46, 10);
    line-height: 30px;
}

    
    </style>
  </head>
  <body>
    <h1>Colors</h1>
    <h3>Qué piensas acerca de los colores?</h3>

    <p>
        Sabias que existen diversos tipos de colores que pueden realzar o perjujdicar el estado anímico de tu hijo o hija?, así es, los colores tienen el poder de afectar positiva como negativamente la mente de nuestros pequenhos. <br>
        Los colores pastel influyen en la paz y armonía en la mente de los ninhos, trae consigo tranquilidad en el ambiente. 
        <br>
        <br>
        Mientras que los colores más fuertes conllevan a desregular el estado de ánimo de nuestros ninhos, los lleva a ser más hiperactivos, ansiosos y trae consigo problemas de concentración. 
        <br> 
        <br>
        Y qué hablar de los colores fluorescentes... Estimula en demasía el cerebro de los ninhos, les limita a la hora de colorear un dibujo debido a que ningún color llama demasiado su atención, pues los colores fluorescentes acaparan la belleza de los otros colores. 
        <br>
        <br>
        En fin, ahora sabes cómo influyen los colores en la mente y estado anímico de nuestros hijos, espero puedas decidir bien a la hora de escoger un color para su habitación.
    </p>
    <ul>
      <li>Amarillo pastel</li>
      <li>Salmón</li>
      <li>Marrón</li>
      <li>Verde agua</li>
      <li>Celeste</li>
      <li>Turquesa</li>
      <li>Rosa pálido</li>
    </ul>
  </body>
</html>