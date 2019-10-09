Los siguientes ejercicios deben realizarse usando metodología BEM.
Será necesario crear el html y las clases asociadas tanto en el archivo .html como en el .css.

*No es necesario añadir ningún tipo de propiedad CSS. No es la intención de esta practica*

1. Crear un elemento `<button>` teniendo en cuenta que el bloque se llamará *b-btn* y vamos a 
añadirle estilos al estado :hover


2. Crear 5 elementos `<button>` adicionales:
    - El primero tendrá el modificador *small*
    - El segundo tendrá el modificador *big*
    - El tercero tendrá el modificador *secondary*
    - El cuarto tendrá el modificador *secondary*, *big* y *rounded*
    - El quinto tendrá el modificador *secondary* y *small*, *light*, *with-icon* y *no-border*


3. Crear un elemento `<div>` con el bloque *b-card* y la siguiente estructura:

```
<div> BLOQUE --> b-card
    <figure> ELEMENTO --> item
        <img> ELEMENTO --> img
        <figcaption></figcaption> ELEMENTO --> title
    </figure>
    <p></p> ELEMENTO --> text
</div>
```

4. Duplica el anterior ejemplo y añade el modificaor *dark* al bloque y el modificador *short* al elemento `<p>` :
