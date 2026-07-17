> [!info] Notas
> Acá iría toda la basura que no quiero que se pierda porque son cosas importantes pero temporales, es decir, no quiero saturar el roadmap de basura ni mis mds ni nada. Así que las ideas que se me ocurren, capturas o lo que sea, van acá. Y después cuando el bot se termine, esto se borra O NO. no sé. Capaz queda como archivo

# 19-06-2026
## Armas y munición
![[Pasted image 20260619122719.png]]
Siento que el sistema de arma sin recargar está incompleto. Es más, no voy a hacer que tengas que recargar arma en el momento, si no la idea es, disparas, si te quedaste sin balas en el cargador recargás si tenés balas pero gastás tu turno. En cambio el botón verde es por si antes del combate querés recargar.

Ah, y gastas una caja de munición entera, no existe eso de cargar 1 bala sola, en el counter de hecho lo que hacen es ahora que vos no puedas recargar como en el 1.6, tenes que tirar 1 cargador entero lo cual es un bajon pero a mi me sirve porque no tengo que micromanejar lo de las balas individuales

Los atascos en este sistema hipotético tendrían 2 factores: 
La fecha en la que fue comprado
La cantidad de disparos que hiciste alguna vez, que estará trackeado en una propiedad custom
Y no la vas a poder reparar negro, perdón, pero no es así el rol. Se te queda jodida y la usas a tu riesgo o te compras una nueva

Las armas melee no van a estar atrapadas en este sistema, tipo, da igual. Es imposible trackear el desgaste y es más molestia que otra cosa.

Y las armaduras un poco se parece el problema pero yo puedo hacer otra cosa: Que vos cuando se te rompa, tengas que poner el comando de usar el item como una forma de hacer como que se te rompió y sacartelo del inventario. Es medio cutre pero no tengo muchas alternativas ni se me ocurre nada

Pensé incluso en un sistema VATS en las armas, es decir, podes elegir que parte del cuerpo disparar y podes errar. Porque en un sistema narrativo el riesgo es que todos disparen a la cabeza y en la realidad apuntar a la cabeza es más difícil realmente. No estoy seguro si lo voy a meter igual, capaz. No me convence del todo porque es otra barrera más pero puede solucionar un problema real y darle personalidad. Tambien con esto podria meter estilos distintos, especializacion de armas y solo podes ser uno, no podes ser sniper y vaquero a la vez ponele

El principio es que los items son líquidos y las técnicas sólidas. O bueno, no sólidas, pero se quedan. Solo 1 tipo de técnica en el inventario, sin estancias y con sus propias propiedades falopa.

He decidido de que, si lo meto, no lo voy a meter hoy. Lo meteré en una update y queda en la nota

![[Pasted image 20260619132923.png]]

Podría pedirle a Roy que me haga emojis para el servidor y lo meto en los creditos, todo

¿Explosivos? Capaz
## Items y gasto
Tengo que ver como manejar los items unicos 
Como dijimos anteriormente, los items son liquidos. Se gastan, se compran. Por ende, la pileta de cosas que comprar en el rol se achica.
Por hoy, tenemos armas de fuego y munición. Pero debe haber algo más
Servicios médicos también, si no pagas y te hirieron, más vale que tengas a un curador o algo así porque te vas a morir. No existen los botiquines acá ni los stimpaks (aún), osea si existen pero no te vas a curar por agarrar un botiquin me explico? Y las vendas son pura narrativa realmente. No hace la diferencia.
Drogas puede ser sinceramente, para los que no tienen estilos podrían ser sus tecnicas y que tengan efectos raros, tratar de traducirlo a discord. Con riesgo de sobredosis, y peor porque si querés usar la tecnica tenes que tomar otra dosis. Después tiene efecto resaca, es decir, tiene efecto narrativo de que andas re duro por un tiempo hasta que se te pasa. Te afecta como disparas también puede ser

- Gastos:
	- Servicios medicos
	- Suscripciones para entrar a canales de forma legal
	- Hoteles y moteles
	- Armas
		- de fuego
		- incendiarias
		- explosivas
	- Munición
	- Armaduras
	- Drogas
- Ingresos:
	- Salario
	- Misiones globales
	- Contratos individuales
- Inversiones:
	- Cambio de divisas
	- Merval
	- Negocios

NADA de viviendas. Nadie va a tener un canal a su nombre a menos de que sea alguien importante o estén en un evento. Las casas son implícitas como comer, trabajar y bañarse. Al final decidí que no hay mucha ganancia en tenerlas

Las colecciones serán 

- Empresas
- Gobierno (y el banco central)
- Negocios
- Bancos 

Hasta negocios dudo si no ponerlo en empresas dentro de un array, pero bueno, tiene su propia complejidad, anda a saber si me entra. El primero que voy a hacer es el del gobierno porque tiene que ver con lo que estoy haciendo de lo de la moneda.

# 23-06-2026
Estos días fueron bastante pesaditos porque no sabía bien que carajo hacer aunque creo que ya tengo una dirección. Al final los bancos no existirán porque es complejidad al pedo y no veo demasiados beneficios ni para mí ni para el usuario
# 24-06-2026 
Después de vueltas y vueltas decidí posponer el sistema bancario y el sistema empresarial con todo lo que significa a algun momento, cuando? Ni idea. No sé si lo haré siquiera, supongo que sí, no sé si con merval, pero el server tiene que salir lo más pronto y estoy perdiendo tiempo con algo que no me entusiasma en lo más minimo

En algun momento quizás meteré el tablero que propuso Steppenwolf, pero primero quiero ver como sienta a la gente el combate actual
# 12-07-2026

Finalmente he decidido cambiar el nombre de los estratos a "nivel de vida", porque me parece que es un concepto que los jugadores van a entender más.

# 15-07-2026
Acá dejo el modulo sin usar hasta que lo recoja para que no estorbe en el roadmap
```
# Fase ???: Sin asignar
Radio
Videos de Youtube, deepfake? Found footage, notas. IDK
## Módulo I: Empresas
### Estructura interna del bot
- [ ] Types
	- [ ] Empresa
	- [ ] Negocio
- [ ] Collection
	- [ ] Empresas
	- [ ] Negocios
### Mecanicas
- [ ] Casas nobles
- [ ] Empresas
- [ ] Mercado de valores
	- [ ] Bonos (estado, empresas, bancos)
	- [ ] Acciones
- [ ] Propiedades
	- [ ] Viviendas
	- [ ] Negocios
- [ ] Brokers con hilo privado por usuario (categoría financiera?)

### Comandos
- [ ] noble
	- [ ] impuesto
- [ ] burgues
	- [ ] merval
	- [ ] tienda
- [ ] [[tienda]]


## Módulo II: Transacciones
> [!todo] Tarea
> La moneda puede sufrir inflación y los precios pueden verse distorsionados por los impuestos del noble vigente. El sistema bancario tendrá dos capas: el banco central (Gobierno/Principado) y los bancos comerciales, accesibles desde una categoría financiera donde también estarán los brokers.

### Estructura interna del bot
- [x] Cambiar Estratos ✅ 2026-06-22
- [x] Types ✅ 2026-06-23
	- [x] Gobierno ✅ 2026-06-23
	- [x] Modificar Personaje ✅ 2026-06-23
- [x] Collection ✅ 2026-06-23
	- [x] Gobierno ✅ 2026-06-23
	- [x] Modificar Personajes ✅ 2026-06-23
	- [x] Modificar Monedas ✅ 2026-06-23
	- [x] Modificar Estratos ✅ 2026-06-23

### Mecanicas
- [ ] Préstamos
- [ ] Tasas de interés
- [ ] Inflación por consumo
- [ ] Variación controlada de monedas extranjeras (EEUU: piso 80, techo 120)

### Comandos
- [x] manager ✅ 2026-05-26
	- [x] personaje ✅ 2026-05-26
		- [x] dardinero ✅ 2026-05-26
		- [x] quitardinero ✅ 2026-05-26
	- [x] borrar ✅ 2026-06-23
- [x] dinero ✅ 2026-05-26
	- [x] ver ✅ 2026-05-26
	- [x] dar ✅ 2026-05-26
	- [x] cambiar ✅ 2026-05-26
- [ ] banco
	- [ ] depositar
	- [ ] retirar
	- [ ] pedirdinero
	- [ ] pagardeuda
- [ ] lista
	- [ ] monedas

```

El tablero lo pateo hasta después del desarrollo básico la verdad.

# 17-07-2026
Pensaba meter un comando llamado /staff mensaje que iba a ser para que el staff pudiese mandar mensajes. Pero era increiblemente complejo, me iba a freír la cabeza, prefiero usar un comando burner y que los otros se ocupen con discohook