# [Manual 960 grid system](https://960.gs/)

## Class container_xx:  
Esta clase sirve para definir un contenedor.Existen dos tipos de contenedores, de 12 y 16 columnas, que se forman con las clases container_12 y container_16.

## Class grid_xx:
La clase grid_xx define un elemento del diseño que será colocado en un contenedor. El valor "xx", de grid_xx, expresa el tamaño de la rejilla que se está definiendo.

## Class alpha y class omega:
Estas dos clases sirven para eliminar el margen izquierdo de la primera columna y el margen derecho de la última columna del row

## Class prefix_xx:
Esta clase desja a la izquierda xx columnas (desplazando el resto a la derecha)

## Class suffix_xx:
De una manera similar a prefix_xx, la clase sufix_xx sirve para colocar un espacio vacío a la derecha. de la capa. La capa tendrá una anchura definida

Ejemplo:

```html
<div class="container_12">
    
    <div class="grid_3 alpha prefix_1">Columna de 3 espacios desplazada 1 espacio a la derecha</div>
    <div class="grid_4"></div>
    <div class="grid_3 omega suffix_1">Columna de 3 espacios desplazada 1 espacio a izquierda</div>

    <div class="clear"></div>

</div>
```

Tras cada fila de 12 columnas para cerrar la fila usaré

```html
<div class="clear"></div>
```


