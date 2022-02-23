# Practica Final React

## API: 'https://pokeapi.co/api/v2/pokemon'

- Vamos a crear una aplicacion de pokemones con create-react-app
- Implementar routing con react-router-dom
- La aplicacion debera tener un header, main y footer
- El header y el footer siempre estaran presentes
- El header tendra un logo a la izquierda y la navegacion del sitio a la derecha
- El footer simplemente tendra una leyenda que dira: PokeDex 2022 - Todos los derechos reservados™
- El main sera quien muestre las distintas rutas, estas seran:
  - Home
  - PokeDex
  - Contacto
- En Home debera haber algunas imagenes y textos que expliquen de que va la aplicacion (utilizar nuestra imaginacion para pensar un maquetado sencillo pero estetico)
- En PokeDex deberemos implementar algunas funcionalidades para poder mostrar todos los pokemons que vengan de la API y debera haber una barra de busqueda que nos permita buscar algun pokemon particular, bien sea por id (si lo conocemos) o por nombre. En caso de encontrar un match, debera reemplazar el listado de todos los pokemons por uno puntual con mas informacion sobre ese pokemon.
- Todos los llamados deberan ser con async/await
- Tambien en PokeDex debemos implementar que si el usuario hace clic en alguno de los pokemones que se ven en pantalla deberia mostrarse tambien mas informacion sobre ese pokemon especificamente.
- BONUS: agregar boton para volver a listado en vez de mostrar un solo pokemon
- En Contacto deberiamos implementar un formulario que contenga los siguientes campos:
  - Nombre Completo \*
  - Email \*
  - Telefono
  - Mensaje \*
  - Acepto terminos y condiciones \*
  - Boton de envio
    Este formulario deberia imprimir en consola un objeto con todos los datos del formulario al hacer clic en el boton de envio. Tambien debe validarse que los campos con \* tengan contenido de manera obligatoria. Prevenir el envio por defecto.
- Implementar un modo oscuro que se controle desde el Header y trabaje para toda la aplicacion
