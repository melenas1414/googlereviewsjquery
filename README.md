# googlereviewsjquery

Implementación con Jquery de Google Reviews con Jquery y PHP sobre un template con Bootstrap 4
Se requiere acceso a la api de Google Place

## Dependencias:

### Instalación completa

```sh
npm install
```

### Instalación por separado

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


## Versiones

### 1.0

Se usa PHP para hacer la conexión con la api de Google Places

#### 1.0.1

Se incorpora la instalación automática de dependecias con npm install 
