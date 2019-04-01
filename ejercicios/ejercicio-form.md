Crear un archivo form.html con la estructura básica del documento html,
que dentro del body contenga:

1. Un elemento h1 que diga: "Encuesta de satisfacción fantástica"
2. Un elemento p que diga: "Por favor, responda las preguntas con la mayor seriedad posible. Su contribución ayudará a 
generar una base de datos sobre la población de la nación que nos servirá para poder brindarle una mejor calidad de fantasías".
3. Un elemento form, que contenga:

    1. Un elemento label(*) que diga: "Apodo de fantasía"
    2. Un elemento input del tipo text, con el placeholder "Ingrese su apodo de fantasía"
    3. Un elemento label que diga: "Lugar fantástico favorito"
    4. Un elemento input del tipo text, con el placeholder "Ingrese su lugar fantástico favorito"
    5. Un elemento label que diga: "Color más delicioso"
    6. Un elemento input del tipo color
    7. Un elemento label que diga: "Comida para un día de picnic en la luna"
    8. Un elemento select que contenga los siguientes elementos option dentro suyo:
        a. "Hamburguejas al vapor"
        b. "Grajeas de todos los sabores"
        c. "Hamburguesas de Don Cangrejo"
        d. "Tomacco"
        e. "Slurm"
        f. "Fideos con chocolate"
    9. Un elemento label que diga: "Selecciona todos los checkbox correctos"
    10. Un elemento input del tipo checkbox, que a continuación diga: "Este checkbox es incorrecto"       
    11. Un elemento input del tipo checkbox, que a continuación diga: "El anterior checkbox es incorrecto"       
    12. Un elemento input del tipo checkbox, que a continuación diga: "El anterior checkbox es incorrecto"       
    13. Un elemento input del tipo checkbox, que a continuación diga: "Ya te dije anoche que no"
    14. Un elemento input del tipo checkbox, que a continuación diga: "¿Puede darme dinero?"       
    15. Un elemento label que diga: "Selecciona que clase de animal serías si no fueses un animal"
    16. Un elemento input del tipo radio, con el atributo name="animal", que a continación diga: "Una nube"
    17. Un elemento input del tipo radio, con el atributo name="animal", que a continación diga: "Una nota musical"
    18. Un elemento input del tipo radio, con el atributo name="animal", que a continación diga: "Un cumpleaños"
    19. Un elemento label que diga: "Escriba su primer sueño al revés"
    20. Un elemento textarea
    21. Un elemento button que diga: "Eso es todo amigas"

(*)Label significa etiqueta, y se utiliza para aclarar a qué refiere cada campo. La etiqueta se escribe de la siguiente forma:

<label>Apodo de fantasía</label>
<input type="text" placeholder="Bla, bla, bla..." />

Recordá separar cada label y cada elemento con saltos de línea utilizando <br />

PD. No hace falta que contestes la encuesta