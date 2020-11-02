# Maratón Guayerd ReactJS

## Objetivo

Crear una app que nos permita consultar la API de búsquedas en MercadoLibre y mostrar al usuario un listado con los primeros 50 resultados de esa búsqueda.

## Tareas

1. Clonar el repo github https://github.com/maaroarg/guayerdMaratonReact
2. Inicializar el proyecto
3. Armar layput de los componentes (Sólo la parte visual, en el render)
   1. App
   2. SearchBox
   3. ResultList
   4. ResultItem
4. Completar componente App. Qué rol ocupa este componente en la App?
   Desde aquí deberíamos controlar el acceso a la API y actualizar el state de toda la app que luego será consumida por los componentes hijos.
5. Completar componente SearchBox. Controla la interacción con el usuario.
6. Completar componente ResultList. Visualiza los resultados de MELI.
7. Completar componente ResultItem. Visualiza cada item de resultado.
8. Completar la interacción entre App/SearchBox/ResulList y MELI API.
9. Traer por default, una búsqueda del producto "atari 2600" cuando se monta la app
10. Bonus: Agregar la funcionalidad de favoritos.
    1. Componente FavList (Listar los items favoritos)
    2. Agregar acción "Agregar a Favoritos" en ResultItem

## Mockup (Realizado por expertos en UX)

[MockUp Guayerd - MELI](https://github.com/maaroarg/guayerdMaratonReact/blob/master/mockupGuayerdMELI.png)

## `npm start`

Corre la app en modo desarrollo
[http://localhost:3000](http://localhost:3000)

### MELI API

[Documentación MELI API](https://developers.mercadolibre.com.ar/es_ar/items-y-busquedas#Obtener-%C3%ADtems-de-una-consulta-de-b%C3%BAsqueda)
