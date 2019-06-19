# googlereviewsjquery
Implementación con Jquery de Google Reviews con Jquery y PHP sobre un template con Bootstrap 4
Se requiere acceso a la api de Google Place

*Se requiere instalar:*

Bootstrap

```sh
npm install bootstrap
```

JQuery

```sh
npm install jquery
```

## USO

Se debe incluir el siguiente javascript: 

```html
<script src="js/jQuery.googlereviews_plugin.js"></script>
```

Y se hace el llamado en javascript indicando el id o la clase donde se va a incluir ese contenido:

```js
$('.reviews').getReviews(apiKey,place_id);
```


#### NOTAS

Se usa append para incluir insertar las reviews.
