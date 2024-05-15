# TOWER ROGUELIKE RPG

El jugador está situado en una torre de la que tiene que escapar derrotando al jefe final que se encuentra en la última sala de dicha torre.

## Estructura de la Torre

La torre inicial cuenta con 5 niveles o pisos. En cada piso se generan aleatoriamente hasta un máximo de 10 habitaciones. El jugador tendrá que ir avanzando de habitación en habitación sin morir para ir subiendo de piso hasta llegar a la última habitación.

### Tipos de Habitaciones

- **Habitación con Enemigos:** Es una habitación con un número aleatorio de enemigos. Al derrotarlos a todos se pasa a la siguiente habitación. Habrá una pequeña probabilidad de que te den dinero o equipamiento al derrotarlos a todos.
- **Habitación de Equipamiento:** Esta habitación únicamente es una sala donde hay un equipamiento (arma, armaduras, objeto, etc) aleatorio el cual puedes equiparte.
- **Habitación de Tienda:** Un vendedor te ofrecerá 3 objetos a diferentes precios que podrás comprar para mejorar tu equipamiento. También se podrán vender los objetos que tengas por dinero.
- **Habitación Mini Jefe:** En esta habitación aparecerán enemigos “débiles” que deberás derrotar antes de enfrentarte al mini jefe.
- **Habitación Jefe Final:** La última habitación de la torre con un jefe muy fuerte. Si lo matas, ganas la partida.

## Inventario del Personaje

El personaje tendrá un inventario organizado así:

- **Arma**
- **Armadura**
- **Objetos de Utilidad (máximo 3)**
  - Los objetos podrán ser utilizables o que den efectos pasivos.

## Combate

- **Contra Enemigos Débiles:** El combate será directo. Es decir, un intercambio de golpes donde al final se te informa si has matado o no al enemigo y cuánta vida te ha quitado.
- **Contra los Jefes:** Será un estilo de combate por turnos.

## Consulta de Información

En todo momento el jugador podrá consultar el mapa, el inventario y sus estadísticas.
