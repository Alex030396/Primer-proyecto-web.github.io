<h1 align="center">Primer proyecto de programación</h1>
<p>Este primer proyecto realizado fue para aprender a desarrollar una pagina web desde cero usando HTML y CSS, curso dictado por Juan de la Torre de, https://codigoconjuan.com/. </p>
<p>Esta página es una presentación de cómo me daría a conocer como desarrollador web, cuenta con 4 enlaces: Inicio, Nosotros, Clientes y Contactos. </p>
<p>Como es un proyecto básico de aprendizaje, da a conocer lo esencial de como crear tu primer índex en HTML y con lo que debe contar.  Como el código de inicio usando “!” para crear la base de la página: <html>, <head> y <body> como a continuación: </p>
<h2 align="center">Index.html</h2>
  
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Desarrollados Web</title>
</head>
<body>
    
</body>
</html>
```

<h2 align="center">Style.css</h2>

<p>En este índex se agregó el <link rel="stylesheet" href="css/style.css"> para darle los estilos de CSS a nuestra pagina web, como: colores a las letras, tamaño de la página, centrado de los títulos, colores de fondo de navegación y muchos otros estilos para realizar la página.</p> 
<p>Lo principal fue crear los parámetros más importantes como: las variables, tamaño de los títulos y las palabras, tamaño de la página, de las imágenes y los parámetros del HMTL y el BODY.</p>

```css
:root {
    --fuenteHeading: 'PT Sans', sans-serif;
    --fuenteParrafo: 'Open Sans', sans-serif;
    --primario: #784d3c;
    --gris: #e1e1e1;
    --Blanco: #fff;
    --Negro: #000;

}
html {
    box-sizing: border-box;
    font-size: 65.2%;
}
*, *:before, *:after {
    box-sizing: inherit;
}
body {
    font-family: var(--fuenteParrafo);
    font-size: 1.6rem;
    line-height: 2;
}
/**Globales**/
.contenedor {
    margin: 0 auto;
    max-width: 120rem;
    width: 90%;
    width: min(90%, 120rem);
}
a {
    text-decoration: none;
}
h1,h2,h3,h4{
    font-family: var(--fuenteHeading);
    line-height: 1.2;
}
h1{
    font-size: 4.8rem;
}
h2{
    font-size: 4rem;
}
h3{
    font-size: 3.2rem;
}
h4{
    font-size: 2.8rem;
}
img {
    width: 100%;
}
```

<h2 align="center">Normalize.css</h2>

<p>Se agregaron varios links para que el proyecto estuviera mas variedad de texto y un archivo CSS llamado NORMALIZE.CSS. Para que el proyecto de desarrollo web se vea mucho mejor. Estas son las actividades necesarias que se van a repetir en los siguientes proyectos.</p>

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Desarrollados Web</title>
    <link rel="preload" href="css/normalize.css" as="style">
    <link rel="stylesheet" href="css/normalize.css">
    <link href="https://fonts.googleapis.com/css2?family=Krub:wght@400;700&display=swap" rel="stylesheet">
    <link rel="preload" href="css/style.css" as="style">
    <link rel="stylesheet" href="css/style.css">
</head>
```
<h2 align="center">Visualización del proyecto</h2>
<p>Portada del proyecto con sus cuatro enlaces, el proyecto también tiene un formulario, que también entro en la práctica como todo lo que se puede observar si entra a la pagina de visualización. # https://alex030396.github.io/Primer-proyecto-web.github.io/ </p>


<img  src="https://github.com/Alex030396/Primer-proyecto-web/raw/main/Captura%20de%20pantalla%202024-03-17%20134144.png" alt="alex">
<img  src="https://github.com/Alex030396/Primer-proyecto-web/raw/main/Captura%20de%20pantalla%202024-03-17%20153604.png" alt="alex">
<img  src="https://github.com/Alex030396/Primer-proyecto-web/raw/main/Captura%20de%20pantalla%202024-03-17%20153616.png" alt="alex1">



