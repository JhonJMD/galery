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

