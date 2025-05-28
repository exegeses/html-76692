# Notas clase 2

## Imágenes en html
> Primero mencionaremos sitios para descargar imágenes y luego algún que otro sitio para generar imágenes
> También es necesario mencionar algún software de edición de imágenes

    íconos   
        https://www.flaticon.com/  
        https://www.iconfinder.com/  
        https://www.svgrepo.com/  

    fotografías  
        https://unsplash.com/es
        https://www.pexels.com/es-es/
        https://www.freepik.es/


> Sitios para generar imágenes con IA

    https://app.leonardo.ai/
    https://app.photoroom.com/
    https://grok.com/


> Si quiero cambiar el tamaño de una imagen o su encuadre podría utilizar

    https://imageresizer.com/


> Software para edición de imágenes a nivel fotográfico

    Photoshop


### Accesibilidad

> Cuando intentamos una imagen podemos configurar el la "alt"
> Este atributo fue creado para poder contarles a ciertos visitantes con una discapacidad visual de qué se trata la imagen
> A menos que tengamos nuestro navegador configurado para que nos lea ese texto, no vamos a poder apreciar ese contenido

## Combinando elementos

> ¿cómo harías si quisieras insertar el logo de una empresa y que ésta sea un enlace a la página de la empresa?
> Deberíamos anidar una imagen dentro de un enlace

    <a href="URL">  
        <img src="PATH">  
    </a>  


## Estructura de un documento html

> Cuando creemos una página HTML, siempre tenemos que tener en cuenta la estructura que necesita este documento
> En el caso en que no tengamos esta estructura base nuestro documento estará mal formado


<!DOCTYPE html>
<html lang="en">
    <head>
        Elementos NO visuales
    </head>
    <body>
        Elementos visuales        
    </body>
</html>

> Si un documento está mal formado tendrá una penalización a nivel posicionamiento orgánico (SEO & SEM)  

    SEO: Search Engine Optimization  
    SEM: Search Engine Marketing  

## Enunciados

> Los enunciados sirtven para posicionar el tema de la página. 
> estos tienen gerarquías que venmm desde el nivel 1 (h1) hasta el nivel 6
