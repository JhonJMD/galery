# **Galería de Imágenes**

------

**transition:** Permite definir la transición entre dos estados de un elemento.

```
.grid-item{
    transition: transform 0.3s ease-in-out;
}
```

**filter:** Permite aplicar efectos visuales a elementos como imágenes, texto entre otros.

```
.grid-item:hover{
    filter: opacity(0.9);
}
```

**transform:** Permite modificar la apariencia y la posición de un elemento.

```
.grid-item:hover{
    transform: scale(1.04);
}
```

**grid-auto-flow: dense; :** Permite controlar la forma en que se colocan automáticamente los elementos en una cuadricula.  

```
.grid-container{
    grid-auto-flow: dense;
}
```

**minmax:** Permite establecer un rango de tamaño para un elemento en una cuadricula o un diseño flexible. 

```
.grid-container{
    grid-auto-rows: minmax(200px, auto);
}
```

**Media-Query:** Permite aplicar estilos específicos a un documento HTML en función de las características del dispositivo en el que se esta visualizando.   

```
@media (){

}
```

**min-width: ** Permite establecer el ancho mínimo que un elemento debe tener. 

```
@media (min-width: 600px){

}
```

**span:** Permite especificar la cantidad de columnas o filas que un elemento de la cuadricula ocupara en un diseño de cuadriculas CSS.

```
@media (min-width: 600px){
    .wide{
        grid-column: span 2;
    }

    .tall{
        grid-row: span 2;
    }
}
```

**background-size: cover; :** Permita hacer que una imagen de fondo cubra completamente el área del elemento al que se le aplica. 

```
.grid-item{
    background-size: cover;
}
```

**background-position: center; :** Permite establecer la posición central de la imagen de fondo dentro del contenedor al que se le aplica. 

```
.grid-item{
    background-position: center;
}
```

**background-repeat: no-repeat; :** Permite asegurar que la imagen de fondo no se repita en el contenedor al que se le aplica. 

```
.grid-item{
    background-repeat: no-repeat;
}
```

