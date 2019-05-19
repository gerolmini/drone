# drone
Práctica Curso Java (1.0) 

Práctica Curso Java (1.0)
Nombre Equipo:
Fecha tope entrega: 30 de mayo

Hemos sido contratados por una empresa que entre otros ingenios diseña y
fabrica drones para vigilancia forestal. También fabrica otros ingenios que no son
drones pero también voladores.
Nos han pedido implementar el software de control para este tipo de drones.
También la comunicación entre el dispositivo de control y el dron.

El dron es una unidad electrónica que consta de:
- 4 rotores
- 2 pilas
- centro receptor (señales desde dispositivo de control)
- estabilizador

Los servicios básicos que ofrece el dron son:
- iniciar-rotores (solo si las pilas están al 100%)
- apagar-rotores
- despegar
- aterrizar
- subir
- bajar
- volar-izquierda
- volar-derecha
- fotografiar (las coordenadas del punto geográfico a fotografiar
serán almacenadas previamente en el dron)

Estos servicios serán iniciados desde el dispositivo de control (mando) a través de un
usuario 'piloto'

Importante:
En pocos días habrá una feria de drones y otros artilugios y se os ha pedido tener
una primera versión mínimamente funcional (MVP) que se pueda presentar en
dicha feria. Una vez pasada la feria, tendréis tiempo para acabar de implementar
las diferentes funcionalidades que falten.

Parte opcional:
- Implementar un sistema de captación de temperaturas de las plantaciones
vigiladas (sensores temperatura)
- Implementar la carga de coordenadas de puntos geográficos a través de fichero
(csv)

Se requiere:
Implementar un programa que pueda hacer despegar un dron, enviarlo a unas
coordenadas indicadas y que pueda tomar fotografías del lugar. Luego que pueda
volver teniendo en cuenta la autonomía necesaria para volver. Se valorará la
documentación ‘javadoc’ de clases y métodos.
