
# Métodos ágiles

### Introducción

- Alternativa a los procesos de softwares tradicionales; rígidos y no basados en la **documentación**
- Creación de "The Agile Alliance" -< dedicaba a promover conceptos del desarrollo ágil
- Punto de Inflexión con el **Manifiesto ágil**

## Manifiesto ágil
### ¿Qué valora el manifiesto?
- **Individuo** e interacciones del desarrollo (sobre e proceso y desarrollo)
- Se abandona la necesidad de **buena documentación**
- Colaboración con el **cliente**
- Responder a los **cambios**, en vez de seguir un esquema rígido
### Principios ágiles
- Asumir la **simplicidad**
- Abrazar el **cambio**
- Entregas **frecuentes**
- Cliente y desarrollador trabajan **juntos**
- Individuos motivados
- Dialogo cara a cara
- Se **mide el progreso con software funcional**
- Promover el **desarrollo sostenible**
- Atención continua al buen diseño
- **Simplicidad**
- Equipos -> organizados por **sí mismos**
- El comportamiento es organizado en base a **efectividades**
	- **Efectividad** -> Llegar al **resultado** pase lo que pase

_Algunos principios extra_

- Primar el contenido en contra de la representación
- **Aprender** siempre
- Conocer los **modelos y herramientas**
- Ir **adaptando** el proceso
- Comunicación **abierta**
- Importancia de los **instintos del personal**
	- Todos los miembros tienen **importancia**
### Prácticas centrales
- Participación **activa** de los usuarios
- Aplicar los artefactos-**S.O correctos**
- Propiedad **colectiva**
- Considerar la **realización de pruebas**
- Creación de modelos en **paralelo**
- Crear **contenido simple**
- Representación **simple** de los modelos
- Mostrar **públicamente los modelos**
- Iterar sobre otros artefactos (Todos linux, windows...)
- "Model In Small Increments"

_Algunas prácticas adicionales_

- Aplicar **estándares**
	- Ha decaído en la actualidad
	- Entiendase por estándar, por un manifiesto de normas
- Los **patrones** tienen que ser aplicados **suavemente**
- Descartar modelos temporales
- Formalizar modelos del contrato
- Modelar para comunicar
- "**Be lazy**"
	- **Reusar** código si ya fue hecho (código **bien documentado** y reciente)
- Actualización sólo cuando sea preciso
	- Posibles problemas de compatibilidades...

_Repetición del profesor a adherirse siempre al contrato_

### Buenas ideas
#### Diseños de Test-Primero
Se crea un **caso de prueba antes de empezar** a codificar. Así se forzará en pensar el propio **diseño** de la aplicación
#### Refactorizar
Pequeños cambios en el código , llamados refactorizaciones, para soportar nuevos requisitos-mantener diseño...

### Modelos ágiles
![[Pasted image 20231010135226.png]]

_**Objeto dinámico**: Objeto que fenece y se crea todo el rato_

### Modelos
#### AMDD Proceso
Necesario el hacer algún modelo inicial para identificar una arquitectura plausible, con el alcance y esfuerzo a realizar
![[Pasted image 20231010135545.png]]
#### Proceso SCRUM

_Busca cuantificar lo que se va a entregar, y si fue rentable +-_

- Existencia de un SCRUM-Master
- Establecemos primero los **backlogs** (documentación, trabajo, código)
- Hacemos un **sprint** (Desde que recogemos los entregables, hacemos una carrera para llegar a los entregables, llegar al plazo establecido)
- Organización
	- Primero un **incremento de 2-4 semanas**
	- Interacciones **diarias**
- Obtención final del producto con sus n-versiones documentadas
![[Pasted image 20231010135840.png]]
_No es un ciclo en espiral_


**Historia de usuario**: Descripción de lo que quiere el usuario como producto finalizado

## Programación extrema
### Proceso

_La **programación extrema** parte del caso habitual de una compañía que haga software a medida dividida en roles_

- Equipo de **gestión**
- Equipo de **desarrolladores**
- **Cliente** (No busca venderle una idea, le da la libertad de tomar el control del desarrollo que esta pidiendo)

### Interacción con el cliente
- En programación extrema el **cliente** es **parte del equipo** de desarrollo
- Tiene que **realimentar** al equipo después e cada iteración con los problemas, mostrando sus **prioridades**
- Existencia de **métodos de aceptación** que ayudará a que la labor del cliente sea fructífera
- **Eliminación** de la fase inicial que capture **requisitos**, con la implementación de estos durante el desarrollo
- Puede **cambiar de opinión** sobre la marcha, pero tiene que estar disponible

 El proceso de captura de requisitos de XP gira entorno a una lista de **características** que el cliente desea que existan en el **sistema final**. Estas características se denominan **Historias de usuario**

#### Primera fase
Describe con sus palabras las características y designa al **jefe de equipo**. Con su costo y a través del dialogo lo deja por **escrito**
#### Segunda fase
Se cogen las primeras historias y se implementan y se dividen en **tareas necesarias**. El cliente sigue participando pero no tiene tanto peso
#### Características 
- El **cliente** tiene que escribir lo que quiere en forma de **tarjetas**
- Los desarrolladores se encargan de **catalogar las historias de los usuarios** y su duración
- **Uso de tarjeta** -> facilitación del cliente a la hora de **especificar su importancia** relativa (Así como la tarea)
- Este formato de tarjeta es útil al realizar **pruebas de aceptación**
- Búsqueda de horarios algo más flexible
- Una semana de programación ideal (cinco trabajo) de desarrollo sin interferencias
- Las historias deberían de ser abordadas entre 1 y 3 semanas
- Al hacer la planificación se aplica un factor de corrección medido de proyectos anteriores
##### CRC
![[Pasted image 20231023211818.png]]
![[Pasted image 20231023211840.png]]

## Planificación
- Las **entregas** deben de ser hechas **cuanto antes**, y cada iteración del cliente, recibe una nueva versión
- Cuanto más se **tarde en traer algo esencial**, menos se podrá trabajar en ello
- Se aconseja **muchas entregas** y muy frecuentes
	- Así  si hay un error en la parte esencial se encontrará antes
- Requisitos anteriores no deben suponer horas extras
- Lo que se trabaja de más de un día, se deja de trabajar al siguiente
- Las pruebas unitarias, integración continua, juego de la planificación eliminan muchos motivos por los que trabajar horas extra
- Lo común es equivocarse, así que **hay mecanismos de revisión**
_faltan las últimas dos diapos de planificación_

### Diseño, ... y pruebas.
- El **desarrollo** es la pieza **clave** de todo el proceso de **programación extrema** 
	- Las tareas tienen el objetivo que se desarrollen a **máxima velocidad**
	- Sin interrupciones
	- Dirección correcta
- Gran **importancia al diseño** y revisión de este
- Se contrapone al "Gran diseño previo" común en otras metodologías
- La clave del proceso de desarrollo de Xtreme Programming es la **comunicación**
- Un termino estrella de la XP es la **metáfora** (significado literal)
	- Debe ser expresada en términos que todo el grupo lo entienda
	- Correcta selección de nombres durante el proyecto, claridad, simplicidad, reusabilidad.
