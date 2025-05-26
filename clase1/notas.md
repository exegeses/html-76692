# Notas clase 1

> En este curso vamos a aprender a crear páginas web y sitios web

> Para ello necesitamos aprender inicialmente dos lenguajes

1. HTML
2. CSS

## HTML (Hyper Text Markup Language)
> HTML es un lenguaje para crear páginas web, su nombre viene de Hyper Text Markup Language.
> Inicia sigla la palabra clave es Markup qué significa marcado. Esto quiere decir que cada uno de los elementos de este lenguaje es una marca: quiere decir que cumple una funcionalidad 

> Ese lenguaje que vamos a utilizar para crear los contenedores dentro de una página web
> Podríamos pensar un contenedor como una caja y a su vez dentro de esta caja podemos insertar contenido o bien otros contenedores

> Cada uno de estos contenedores se llama "elemento" (anteriormente llamados etiquetas)
> Cada elemento tiene una funcionalidad
> Hay un elemento para:

    Insertar una imagen   
    Insertar un enlace o vínculo   
    Insertar un video  
    Insertar un botón  

## CSS (Cascading Style Sheets)   
> CSS Es un lenguaje para generar la parte estética de un sitio.
> Estamos hablando de colores, tamaños, posiciones y todo lo que tenga que ver con la presentación visual o diseño de cada uno de los elementos.

### Elementos
> HTML todos los elementos son contenedores
> Tienen una sintaxis específica
> Si encierran entre <>

> Sintaxis básica:

    <elemento>contenido</elemento>

### Anidamiento
>  En algún momento, vamos a querer combinar elementos.
> Para poder combinar estos elementos lo que vamos hacer es insertar uno dentro de otro
> Esta es la base de la estructura de una página web

    <elemento>  
        <elemento>  
            contenido  
        </elemento>  
    </elemento>  

### Atributos
> Los atributos son modificadores de un elemento

<elemento atributo="valor">contenido</elemento>
<elemento atributo="valor" atributo2="valor">contenido</elemento>

### Vínculos o enlaces
> Para insertar un vínculo en HTML 
> utilizamos el elemento "a"

<a href="url" target="_blank">
    Texto
</a>

> El atributo Target se utiliza para abrir un enlace en una nueva pestaña

