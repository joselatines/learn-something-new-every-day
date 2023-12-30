# learn-something-new-every-day

## Day 1 30-12-2023

## Modelos arquitectonicos

La arquitectura de software se refiere a la estructura que ha de tener un software, las partes que vamos a construir y la forma en la que las vamos a combinar y juntar para poder trabajar con ellas.

Cabe destacar que la arquitectura de software no es una definición unica si no que se le puede dar otras definiciones dependiendo de puntos de vistas entre cada profesional.


Tipos de arquitecturas de software
Existen diferentes tipos de arquitecturas de software, entre las que se pueden encontrar: 

Cliente-servidor
Red entre pares
Modelo-vista-controlador (MVC)
Arquitectura orientada a eventos (EDA)
Arquitectura de Microservicios

Cliente-servidor
Este tipo de patrón de arquitecturas de software refiere a la existencia de un servidor que proporciona un servicio a un cliente (persona o empresa). Cuando el cliente solicita determinados datos al servidor, el servidor acepta el proceso y entrega los datos que solicitó el cliente.

Entre las ventajas de este patrón, se tiene en cuenta que todos los datos se encuentran en un mismo lugar, requiere poco mantenimiento y la recuperación de los datos es posible.

Como desventajas, los clientes pueden verse afectados por virus, troyanos y phishing. Además, los servidores son propensos a sufrir ataques de denegación de servicio (también conocidos como ataques DoS), y los datos pueden ser modificados durante su transmisión

Modelo-vista-controlador (MVC)
El patrón MVC se utiliza porque permite separar componentes de un programa basándose en la responsabilidad de cada uno, por ende, si se requiere hacer una modificación en una parte específica del código, el resto permanece intacto. 

Emplea tres componentes: modelo, vista y controlador. El modelo se hace cargo de los datos, ya sean actualizaciones, búsquedas u otros. El controlador recibe las órdenes del cliente para, posteriormente, solicitar los datos al modelo y comunicar a la vista, que es la representación visual de los datos (interfaz gráfica).

En este tipo de arquitecturas de software, el proceso de desarrollo es más rápido, ya que varios desarrolladores pueden trabajar a la vez. Además, las modificaciones, de la misma forma que pasa con el patrón anterior, no afectan a la arquitectura entera.

Sin embargo, en lo que respecta a las desventajas, podemos señalar que es un patrón complejo. Los desarrolladores deben estar correctamente entrenados para trabajar con las partes asignadas.

Arquitectura de Microservicios
La arquitectura de microservicios es una de las más buscadas en la actualidad. Consiste en la creación de componentes de software que se dedican a realizar una única tarea y son autosuficientes, por lo que evolucionan de forma independiente.

Vale aclarar también que, cuando nos referimos a microservicios, hablamos de pequeños programas (aplicaciones) que brindan servicios con el fin de resolver determinadas tareas. Como gran ventaja, la arquitectura de microservicios destaca por sus componentes encapsulados, ya que pueden evolucionar a la velocidad requerida y cada microservicio se puede desarrollar con distintas tecnologías (bases de datos).

Por último, si nos enfocamos en las desventajas, este tipo de arquitecturas de software necesita un buen equipo que pueda administrar los componentes de manera correcta, puesto que puede ser un poco complicado.

Arquitectura en capas
La arquitectura por capas nace para suplir los problemas derivados de la arquitectura spaghetti. Su principal objetivo es contar con capas que tienen diferentes usos.

Por ejemplo, mientras que una de ellas se encarga de la visualización de datos, otra tiene que servir para acceder a la base de datos. De esta manera, cada tarea se reparte en una capa diferente, de modo que se facilita el trabajo en ellas.

Arquitectura hexagonal
La arquitectura hexagonal aísla las entradas y salidas de aplicación de la lógica interna de la aplicación. Gracias a este aislamiento, se generan partes independientes que no dependen de los cambios externos, de esta forma, estos pueden cambiarse de forma individual sin afectar al resto.

Day 2 - 31-12-2023 - Patrones de arquitectura de software 


