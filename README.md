# Repaso modulo 2

Hola! Nos encontramos de nuevo para pelear contra este boss final del M2 que es React-Redux y sus hooks. Principalmente los hooks a usar van a ser useState y useEffect.

Se uso el npx create-react-app con template de redux.


# App de gifs

La idea de este repaso es poder crear una app que sirva para visualizar gifs, tener una navbar, una searchbar y un contenedor de gifs.
Se van a usar las tecnologias aprendidas que son React y Redux. Y tambien un poco de peticiones a una API de Giphy.

## Para empezar
Instalar todas las dependencias con:

 - `npm install`

FORKEARRRRRRRRR
## Requisitos
 - No usar clases.
 - Usar los hooks useEffect y useState.
 - Usar mapStateToProps, mapDispatchToProps y connect.
 - No usar hooks de react-redux.

## API key

La pueden conseguir en el siguiente link [de Giphy](https://developers.giphy.com)

Tienen que investigar la API de Giphy, [ACAAAA](https://developers.giphy.com/docs/api#quick-start-guide)
## Pasos

 - Crear la navbar que va a contener un logo a la izquierda, la searchbar en el centro y a la derecha el nombre de ustedes.
 - El logo debe dirigir al root de la pagina, es decir '/'.
 - La searchbar debe buscar por nombre los gifs que coincidan con el input.
 - Al presionar el nombre ustedes, debe redirigirlos al path '/aboutme' donde van a poner info de ustedes en un componente llamado AboutMe.jsx.
 - Un contenedor abajo de la navbar para ver los gifs.
 - Al presionar un gif debe redirigirme a '/gif/:id' donde id va a ser el id del gif clickeado.
 - En la pagina del detalle del gif debe aparecer el gif en el centro, la navbar, el nombre del autor, y los datos que gusten que aparezcan.
 - La navbar debe renderizarse en todas las paginas de la app, pero solo en el root de la pagina debe renderizarse la searchbar.
 ## Extra Credit
 
 - Apenas ingresen a la pagina se debe mostrar los 20 gifs trending de Giphy.
 - Al hacer una busqueda de algun gif, solo deben mostrarse los primeros 20 gifs que coincidan con la busqueda y los trending no se deberian ver mas.

