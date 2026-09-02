PERO QUE MIERDA HICE AL PONER UN INVENTARIO INTERACTUABLE. CREÉ UN MONSTRUO
Veamos el hilo
El inventario responde con un container que abre un collector con las flechas del paginado, que está bien, capaz podríamos universalizarlo. Pero después están los botones dentro del container por cada item, que llevan a la función de infoItem, que te muestra un info del item de tu inventario y hay un awaitmessagecomponent que te lleva a usoItem que a su vez inicia la funcion de itemUso específica que responde con un mensaje y hace otras cosas.
Es un quilombo.