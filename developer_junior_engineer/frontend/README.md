- [Qué vamos a valorar](#qué-vamos-a-valorar)
- [Introducción](#introducción)
- [Requisitos mínimos de la prueba](#requisitos-mínimos-de-la-prueba)
- [Para nota](#para-nota)
- [¿Cómo entregar la prueba?](#cómo-entregar-la-prueba)

# Qué vamos a valorar

Desde nuestro punto de vista no existen pruebas bien hechas o pruebas mal hechas. Nos interesa entender cómo piensas, cómo afrontas los problemas y cómo adquieres conocimientos. Si tienes cualquier duda estamos a tu disposición.

Vamos a valorar que la solución planteada esté bien documentada y que seamos capaces de ejecutar tu solución “sin pensar”.

Vamos a valorar **mucho** como has llegado a la solución que nos propones, documenta el proceso que has seguido y las urls de las páginas o libros que has utilizado para documentarte.

No establecemos qué lenguaje, herramienta o framework tienes que utilizar, elige el camino que prefieras y dinos por qué lo has elegido.

Si por tus conocimientos no eres capaz de realizar el 100% de la prueba, ¡no te frustres! Llega hasta el punto que seas capaz. Explica las decisiones que has tomado y los problemas que te has encontrado

# Introducción

El profesor Serbal nos has pedido una aplicación web en la que poder consultar todos los Pokemon que habitan en la región de Sinnoh.

Los Pokemon tienen una gran cantidad de información y, aunque el profesor nos ha comentado que lo más importante para él es la imagen y el nombre de los Pokemon, cuanta más información podamos representar que sea interesante, siempre será mejor. Eso sí, le gustaría poder representar toda esta información tanto en formato cuadrícula como en formato lista.

Además, como en la vista lista no podemos representar toda la información cuando hagamos clic sobre ellos también es necesario poder consultar más datos acerca de cada Pokemon, como sus puntos de experiencia, su tipo, ataque, defensa y ataque especial.

Al profesor Serbal le encantaría, además, poder tener un modo oscuro de la aplicación para cuando la consulta por las noches.

Para terminar, el profesor Serbal también ha dejado caer que para él, aunque no sea imprescindible, sería fantástico poder marcar sus Pokemon favoritos y consultarlos en otra pantalla de la aplicación.

# Requisitos mínimos de la prueba

Se desarrollará una aplicación web en JavaScript utilizando la API pública [PokéAPI](https://pokeapi.co/) para la obtención de los datos. Los requisitos a cumplir son:


* Tienes que gestionar una aplicación con dos vistas:
  * Una vista listado con la información resumida de los Pokemons.
  * Una vista detalle con la información detallada del Pokemons seleccionado.
* ¡Cuidado! en la región de Sinnoh hay innumerables Pokemon, por lo que se recomienda paginar los resultados.
* Ordenar la información y estructurar la aplicación. Lo fácil sería que te pasáramos un mockup o diseño, pero queremos que pienses cual es la mejor forma de estructurar, agrupar y mostrar la información.
* Añadir una acción para poder cambiar entre modo oscuro o modo claro la aplicación.
* En el listado de Pokemons, habilitar una opción para poder cambiar la visualización de modo cuadrícula a modo lista.

> La imágenes de los Pokemon se podrán obtener a partir de la siguiente url: `https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/other/official-artwork/{POKEMOM_ID}.png`)

> El listado de Pokemon se puede obtener con la siguiente llamada `https://pokeapi.co/api/v2/pokemon`, consulta la documentación del [API Documentation - PokéAPI](https://pokeapi.co/docs/v2).




# Para nota

Además de los requisitos mínimos para la prueba, hemos definido una serie de bolas extras para que puedas lucirte:

* **Testing.** No es imprescindible, pero si vienes con nosotros vas a tener que aprender a testear tu código, puede ser un buen momento para empezar.
* **Variables CSS.** CSS no es un lenguaje de programación pero existen técnicas que hacen el código CSS más mantenible.
* **Typescript.** Javascript no es un lenguaje tipado, Typescript ha venido para quedarse.
* **Responsive Design.** ¿Mobile, desktop o tablet? O mejor si funciona tu  aplicación en todos ellos.
* **Favoritos**
  * Poder marcar los Pokemon como favoritos.
  * Desarrollar una página que muestre nuestros Pokemons favoritos.
  * Mantener el estado de los Pokemon guardados como favoritos aunque se recargue la página.

# ¿Cómo entregar la prueba?

Tendrás que publicar tu prueba en un repositorio público, github por ejemplo.

Documenta en el repositorio el proceso que has seguido y las fuentes que has utilizado para documentarte, es decir, redacta una pequeña memoria explicando los pasos que has dado, los problemas que te has encontrado y cómo los has solventado.

