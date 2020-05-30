# Tutorial Flex box

El layout flex box se basa en que sus flexItems se han flexibles.

```html
    <!-- Estructura básica de un flex container(padre) con sus flex items(hijos)-->
    
    <div style="display:flex" id="flexContainer">
        <div id="flexItem1">
            contenido
        <div id="flexItem2">
    </div>
```

Acá podemos observar los elementos que lo conforman:

-   Flex container (padre)
-   Flex item (hijos)
-   main axis (eje principal por defecto de izquierda a derecha)
-   cross axis (eje secundario por defecto de arriba hacia   abajo)
-   main size (ancho horizontal del padre)
-   cross size (altura vertical del padre)

![Alt imagen flexbox](./img/estructura-flex-container.png "Title")