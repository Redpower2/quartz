## Personaje crear
Lee los 2 json
Después de poner al personaje en cuestión en personajes.json, revisa si el id del usuario existe en usuarios.json. En caso de que no, lo crea con su id de interacción y su username como alias. Y el personaje creado se pone como personajeactivo. Si está, bueno, revisa si hay personajeactivo, y si no, lo pone.

## Personaje borrar
Lee los 2 json
Lo de crear afecta directamente acá, porque si lo borran, y después tiene a ese como personajeactivo, queda bugueado citando un id vacío. Así que acá debería hacer una comprobación de usuarios.json, ver si es el personaje activo, y si si, entonces hacer lo de crear una lista de los personajes que tiene el usuario en personajes.json y si se puede, elegir el primero. En caso de que el usuario no tenga más personajes, se borra la propiedad entera