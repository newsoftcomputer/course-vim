

# COMMANDS

## In & Out

    - In 

		$ nvim

         or 

        Execute Nvim (.deb, .tar, .app, .exe )


	- Out

		-Cierre
    ZQ
		
      or

    - Cierre
    :q

      or

    - Cierre todo
    :qa
wnn


## Insert Mode

	- Es el modo en el que podemos insertar texto

	- In: Entrar modo insert:

		i : Inicia inserccion sobre la letra del puntero

		a : Inicia inserccion despues de la letra del puntero 

	- Out: Salir del modo insert

		Esc



## Save & Exit

    ZZ

     or
    
    :wq

     or 

    :x 


## Save All

  - Es usado cuando se tienen multiples archivos abiertos, editados y se desean guardar todos
  
    :wall


## Save & editar siguiente, anterior

    :wn 
    
     or

    :wN 



## Deshacer cambios

    - Uso en modo normal

    u


## Quitar lineas en modo normal

    dd

      or

    d + shift 4

      or 

    d + 0 + d




:e f . . . . . editar archivo f, a menos que hayan cambios
:e! f . . . . editar archivo f siempre (recargar el actual)

:n :N. . . . . . editar archivo siguiente, anterior de la lista
:rw . . . . . . . . . . . . . . . . . guardar rango r en archivo actual
:rw f . . . . . . . . . . . . . . . . . . . . guardar rango r a archivo f
:rw>>f . . . . . . . . . . . . . . . . . . .agregar rango r al archivo f
:q :q! . . . . . . . salir y confirmar, salir e ignorar cambios
hupi hdowni . . recordar comandos anteriores (historial)
:r f . . . .insertar contenido archivo f debajo del cursor
:r! c. . insertar salida del comando c debajo del cursor
:all. abrir una vent. por cada arch. pasado en los arg.


## mostrar lista de argumentos

:args