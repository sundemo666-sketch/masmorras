# Masmorras

Este repositorio contiene una propuesta inicial para un juego de calabozos y masmorras con mecánicas realistas.

## Idea principal

Un juego de exploración de calabozos donde la interacción con el entorno y el botín sea coherente con el mundo. Por ejemplo, los enemigos con armadura dejan su equipo al morir y el jugador puede retirarlo o desmantelarlo.

## Mecánicas sugeridas

- **Botín realista**: al derrotar enemigos con armadura, el equipo pasa a ser saqueable. Se pueden definir estados (intacto, dañado, inútil) según el combate.
- **Sistema de peso**: el jugador debe decidir qué equipo llevar debido a la limitación de carga.
- **Desgaste de equipo**: armas y armaduras se deterioran, incentivando reparación o reemplazo.
- **Puzzles**: salas con palancas, presión, runas o mecanismos ambientales que requieran observar pistas en el entorno.
- **Exploración modular**: calabozos generados con secciones combinables para rejugabilidad.

## Próximos pasos

1. Definir el alcance: un prototipo pequeño con 3-5 salas, 1 jefe y 2 puzzles.
2. Documentar el loop principal de juego (explorar → combatir → loot → resolver puzzles).
3. Crear un listado de enemigos y sus sets de armadura para el sistema de botín.
4. Diseñar un puzzle básico y uno avanzado con pistas visuales o sonoras.
