# Disparates
> [!info] 
> Se usaría esta categoría para tirar ideas sueltas que puedo ordenar o no, pero que necesito tener anotadas.

Crear los perks
PROBAR CADA COMANDO
VER QUE SE PUEDE OPTIMIZAR
¿Carpeta de perks? Tal vez importación dinámica en vez de un switch. Sería lo más ordenado tal vez
MI IDEA IGUAL SERÍA SACAR CONTENIDO DEL BOT A CACHOS, TIPO, LA TIMBA LA SACO DESPUÉS A PESAR DE TENERLA HECHA YA

Me tengo que acordar de buildearlo a dist para js y ver si funciona, porque capaz que prende pero no andan los comandos, es más común de lo que parece
# Lista de comandos a hacer
- [ ] Juego
	- [ ] Blackjack
	- [ ] Craps (anteriormente generala, pero quedó descartado)
	- [x] List (En realidad, es la de sin args) ✅ 2025-08-12
	- [ ] Rasca y Gana (Pero no es subcommand, si no invocado por item usar)
	- [x] Ruleta ✅ 2025-08-13
	- [ ] Tragaperras
	- [ ] Truco
# Prioridades
## Primera prioridad (Presente)
Optimizar los códigos redundantes o grandes, ya sea creando funciones, con bucles o lo que sea. Pero tendría que detectarlos
- Perks (Conjuras y servidor)
	- Slot
	- Antipoda
	- Berserk
	- Honor
	- Presagio
	- Provocación
	- Tacleada
	- Tanque
	- Viveza

## Segunda prioridad (Futuro cercano)
COMANDOS A PULIR/Reworkear:

Inventario, tienda, item lista (otra vez): Controlar que cuando se exceda de caracteres, mandar otro embed o manejarlo con páginas, botones. No lo hago porque no veo la necesidad todavía, pero cuando la tenga lo voy a hacer

Los comandos que tienen importaciones dinámicas: Todavía no he hecho la función de importación dinámica porque se me hace muy difícil pero después lo haré
- Trabajos y comandos principales.
- Apuestas (juegos).
## Tercera prioridad (Futuro lejano)
Basurero, chatarrero: Trabajos que si bien tengo alguna idea suelta, no he creado una estructura sólida.

Cocinero: Estilo Papa's pizzeria con sus pestañas de cocina, caja, corte y esas cosas, cada uno con su mecánica

Conserje: Juego 2d de scroll automático a la derecha donde sos un conserje que está lavando el piso y tiene que evitar caerse a pozos o chocar con cosas

Granjero: Juego de granja idle

Ladrón: Puede que sea descartado, aunque las ideas de abrir autos y puertas con ganzúa podrían ser una mecánica separada

Blackjack: No conozco bien las reglas  pero parece fácil

Generala: No conozco bien las reglas

Rasca y gana: Me da paja empezarlo porque es más complicado de lo que parece

Tragaperras: Lo mismo de arriba

Truco: De los más complejos, multijugador, sistema de cantos, cartas, dibujar las cartas yo para que tenga estilo el server, etc.
## Cuarta prioridad (Futuro incierto)
En vez de links, muchas veces podría simplemente usar adjuntos para las imagenes y tal. Más práctico y más mejor. De hecho no sé si puedo hacer que el bot publique las cosas de mecánicas y tal en los canales, porque si es así mejor, descargo las imagenes y no tengo que poner links que se pueden caer en cualquier momento. SIN COMANDOS EH, no quiero un comando para publicar cosas



Librería
Si llego a hacer lo de los personajes distintos, entonces capaz que debería hacer otro comando llamado personajes con una estructura así
- Ver (Tuyos, o de otro)
- Lista (de todos los personajes del server)
- Seleccionar (para usar ese)
- Borrar (exclusivo para admins)
- Crear (exclusivo para admins)
- **Sistema de empresas/Facciones**: Crear o unirse a empresas con automatización parcial. Minijuego económico.
    
- **Inflación e impuestos**: Sistema simple y manejado manualmente, con modificaciones de precios según políticas en el rol.
    
- **Sistema de personajes**: Idealmente sin límite de cantidad, aunque quizás limitado por memoria (3 o 4 máximo).


Algo que sería genial serían más estadísticas, a nivel servidor y a nivel usuario. Cada usuario tendría registro de sus puntos de los minijuegos que jugó, cuántas veces los jugó y capaz puntos totales por todos los miniuegos jugados. ¿Habrá alguna recompensa por estos puntos? Capaz, capaz. 
También el dinero apostado en total (y en cada juego), el ganado y el perdido.
Y mi idea de los leaderboards se mantiene firme, que cada minijuego tenga su leaderboard mostrando quién hizo más puntos, en lo del casino no aplicaría porque la apuesta máxima es fija, 1000 (número que tal vez suba, veré) pero capaz podría recolectar otros datos como cuántas veces se jugó cada color, número, cosas así, simpáticas.
Pero eso es más adelante cuando aprenda a usar mongoose y realmente me importe, por ahora terminar los trabajos y los juegos de azar es mi prioridad

Si el bot puede usar emojis animados, en vez de poner las cartas y todas las utilidades en los emojis normales, uso los animados pero quietos y listo.



    
- Misiones y contratos (no negociables).
    
- Tour.
    
- Eventos aleatorios (más pulido que en Machtness).
    
- Packs iniciales.
    
- Sistema de fichas más práctico.
    
- Versión especial de trabajos (según el canal: ej. cajero, repartidor de morgue, etc.).
    
    
- Optimización y mejoras generales que no se alcanzaron al inicio.