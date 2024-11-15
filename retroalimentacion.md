## Hola Leo
![](https://http2.mlstatic.com/D_NQ_NP_2X_937616-MLM52691732664_122022-F.webp)

Buen trabajo Leo :D tu proyecto cumple los requisitos especificados y la organización de la información permite leer fácilmente la información. Entendiste bien las bases de HTML, sin embargo, noté que tuviste varias fallas en cuanto a la estructura del código en cuanto a la organización y jerarquía de las etiquetas. 

Entre los puntos a destacar:

- Bien por agregar el readme.md con los enlaces de tu proyecto, es una buena práctica. En futuras entregas me gustaría que también trajera la descripción de tu proyecto.

- En tus imágenes agregaste el atributo alt, lo que también es buena práctica de accesibilidad.

- La forma de presentar la información es clara y facilita la lectura.

En cuanto a los puntos de mejora en general, te listo lo siguiente:

- Se te dificultó el orden y uso de las etiquetas semánticas. Una estructura básica debería verse más o menos así:

```html
<!DOCTYPE html>
<html>

    <head>
        <title>Título</title>
    </head>

    <body>
        <header>
            <img src="imgs/logo.jpg">
            <nav></nav>
        </header>

        <main>
            <section>
                <h2></h2>
                <img src="imagen.jpj">
                <p></p>
            </section>

            <section>
                <h2></h2>
                <img src="imagen.jpj">
                <p></p>
            </section>
        </main>

        <footer>
            <p>Derechos Reservados</p>
        </footer>

    </body>
</html>
```

- Hay que ser consistentes en el menú de navegación, es mejor que en todas las páginas siempre aparezcan los 3 enlaces a las otras páginas, para facilitarle la navegación a los usuarios.

- Las imágenes que usaste son de links externos, esto es válido, pero recuerda que al estar alojadas en el servidor de alguien más, dependes de que ese servidor esté funcionando, por lo que es recomendable usar imágenes de tu propio proyecto, en tu servidor.

En el pull request que le hice a tu proyecto, vas a ver como comentario los puntos que hay que corregir en cada archivo.

Te agradezco mucho Leo, espero que este feedback te ayude y que sigas entusiasmado con el curso :D