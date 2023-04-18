# TRELLO - MONGO DB

### ¿Cuáles son los principales objetivos de estos ejercicios?
El objetivo de este proyecto es que los estudiantes exploren las características, ventajas y desventajas de MongoDB, una base de datos NoSQL muy popular en la actualidad, a través de una investigación teórica y práctica. 

## 1.Parte 1. Trello
![Logo Trello](./assets/Trello-logo.png)

# Crear un tablero de Trello para el proyecto:

- Crea un tablero de Trello para el proyecto y compártelo con tu compañero/a.
![Componentes proyecto](./assets/trello1.jpg)

- Agrega una lista para cada etapa del proyecto (por ejemplo, "To do", "Doing", "Done").
- Cada lista debe contener tarjetas para cada tarea específica que se deba completar dentro de esa etapa del proyecto.
![Tablero Creado](./assets/trello2.jpg)

# Repartir el trabajo:

- Asigna las tarjetas a cada uno de los miembros del equipo para que se encarguen de las tareas específicas que se han creado.

![Tareas](./assets/trello3.jpg)

- Utiliza la función de comentarios de Trello para comunicarte con tu compañero/a acerca del progreso y cualquier problema o duda que surja durante el proyecto.
<img src="./assets/trello4.jpg" alt="Comentarios" style="width: 50%;">

# Hacer un seguimiento del progreso:

- Utiliza la función de checklists en las tarjetas para dividir las tareas en subtareas más pequeñas y asegurarte de que todo esté completo antes de marcar la tarjeta como terminada.
<img src="./assets/trello5.jpg" alt="Checklist" style="width: 50%;">

- Utiliza la función de etiquetas para categorizar las tarjetas por tema o importancia.
- Haz un seguimiento del progreso del proyecto a medida que se avanza, moviendo las tarjetas entre las listas a medida que se completan las diferentes etapas.
![Categorias y seguimiento](./assets/trello6.jpg)

# Finalizar el proyecto:

- Cuando se hayan completado todas las tareas, revisa el proyecto en su conjunto para asegurarte de que todo está completo y que no hay tareas pendientes. Asegúrate de que la presentación final se haya completado antes de marcar el proyecto como terminado.
![Categorias y seguimiento](./assets/trello7.jpg)




## 1.Parte 2. Investigación

En parejas, los estudiantes deberán realizar una investigación teórica sobre MongoDB, enfocándose en los siguientes aspectos:

# ¿Qué es MongoDB?

MongoDB es una base de datos NoSQL, lo que significa que no sigue la estructura de tabla relacional tradicional utilizada por bases de datos SQL como MySQL o PostgreSQL. En lugar de eso, MongoDB utiliza un formato de documento flexible llamado BSON (Binary JSON) que permite almacenar y consultar datos de manera más dinámica.

MongoDB también es una base de datos distribuida y escalable horizontalmente, lo que significa que se puede dividir en varios servidores para manejar grandes cantidades de datos y tráfico simultáneamente.

MongoDB es ampliamente utilizado en aplicaciones web modernas, especialmente en aquellas que tienen un gran número de usuarios o que necesitan manejar grandes cantidades de datos. Como es una base de datos NoSQL, es especialmente útil para aplicaciones que requieren un alto rendimiento y una flexibilidad de esquema de datos.

# ¿Cuáles son las características principales de MongoDB?

Algunas de las características principales de MongoDB son:

- Estructura de datos flexible: MongoDB no tiene un esquema fijo y predefinido, lo que significa que puede almacenar datos con diferentes estructuras en un mismo documento.

- Escalabilidad horizontal: MongoDB está diseñado para escalar horizontalmente, lo que significa que se puede agregar más servidores a un clúster para aumentar la capacidad y el rendimiento de la base de datos.

- Alta disponibilidad: MongoDB tiene opciones de replicación integradas que permiten la creación de copias de los datos en diferentes servidores para garantizar la disponibilidad en caso de fallos.

- Consultas eficientes: MongoDB utiliza un lenguaje de consulta poderoso llamado Aggregation Pipeline que permite la realización de consultas complejas y agregaciones de datos.

- Indexación avanzada: MongoDB tiene un sistema de indexación avanzado que permite la indexación de datos por diferentes campos y tipos de datos.

- Integración con lenguajes de programación: MongoDB tiene drivers oficiales para varios lenguajes de programación, incluyendo Java, Python, Node.js, entre otros, lo que lo hace fácil de integrar en aplicaciones web.

- Compatibilidad con la nube: MongoDB se puede utilizar en diferentes proveedores de servicios en la nube, como AWS, Google Cloud y Microsoft Azure.

# ¿Cómo se estructuran los datos en MongoDB?

En MongoDB, los datos se organizan en colecciones y documentos. Una colección es un grupo de documentos, mientras que un documento es un registro individual que se almacena en una colección. Cada documento en una colección se almacena como un objeto BSON, que es un formato de documento binario similar a JSON.

A diferencia de las bases de datos relacionales, los documentos en una colección no tienen un esquema fijo y predefinido. En su lugar, los documentos pueden tener campos diferentes y estructuras diferentes dentro de una misma colección. Esto significa que los documentos en una misma colección pueden tener diferentes tipos de datos y diferentes números de campos.

Por ejemplo, si tuviéramos una colección llamada "usuarios", cada documento en la colección podría tener campos diferentes, como nombre, edad, correo electrónico, ubicación, entre otros. Además, el número de campos y los tipos de datos de cada campo pueden variar de un documento a otro.

La flexibilidad de la estructura de los datos en MongoDB es una de las razones por las que es popular en aplicaciones web modernas, ya que permite manejar datos de manera más dinámica y adaptable.
 
# ¿Qué ventajas ofrece MongoDB en comparación con las bases de datos relacionales?

MongoDB ofrece varias ventajas en comparación con las bases de datos relacionales, entre ellas:

- Flexibilidad en la estructura de datos: Como mencioné anteriormente, MongoDB permite una estructura de datos más flexible que las bases de datos relacionales. Esto permite manejar datos no estructurados o semiestructurados sin tener que preocuparse por la definición de tablas y esquemas.

- Escalabilidad horizontal: MongoDB está diseñado para escalar horizontalmente, lo que significa que se pueden agregar más servidores para manejar grandes volúmenes de datos y tráfico. Las bases de datos relacionales, por otro lado, tienen una capacidad de escala vertical limitada, lo que significa que solo se pueden agregar recursos a un servidor existente.

- Agilidad en el desarrollo: MongoDB es especialmente útil en entornos ágiles de desarrollo de software, donde los requisitos cambian con frecuencia. Al no tener un esquema fijo, se pueden agregar nuevos campos a los documentos sin tener que realizar cambios en la estructura de la base de datos.

- Alto rendimiento en lectura y escritura: MongoDB utiliza un modelo de datos orientado a documentos que permite una lectura y escritura de datos más rápida y eficiente que las bases de datos relacionales.

- Integración con aplicaciones web modernas: MongoDB tiene drivers oficiales para varios lenguajes de programación y frameworks populares utilizados en aplicaciones web modernas. Además, MongoDB tiene integración nativa con tecnologías como Node.js, lo que facilita su uso en aplicaciones web.

En resumen, MongoDB ofrece una mayor flexibilidad, escalabilidad y agilidad en el desarrollo de aplicaciones web modernas, lo que lo convierte en una opción atractiva en comparación con las bases de datos relacionales tradicionales.

# ¿Cuáles son las desventajas de MongoDB? ¿Cuándo no es recomendable utilizarlo?

Si bien MongoDB ofrece varias ventajas, también tiene algunas desventajas y situaciones en las que no es recomendable utilizarlo:

- Falta de transacciones ACID: MongoDB no admite transacciones ACID, que son un conjunto de propiedades de transacciones de bases de datos relacionales que garantizan que las transacciones sean seguras y consistentes. Esto puede ser un problema en algunas aplicaciones donde se requiere un alto nivel de garantía de la integridad de los datos.

- Altos requisitos de recursos: MongoDB puede requerir más recursos que una base de datos relacional comparable debido a su escalabilidad horizontal y a su modelo de datos orientado a documentos. Esto puede hacer que el alojamiento y el mantenimiento de una instancia de MongoDB sea más costoso.

- Falta de herramientas de análisis y reporting: MongoDB no tiene tantas herramientas de análisis y reporting como las bases de datos relacionales. Esto puede dificultar la realización de análisis complejos de los datos almacenados en MongoDB.

- No es adecuado para todas las aplicaciones: A pesar de su flexibilidad y escalabilidad, MongoDB no es adecuado para todas las aplicaciones. Las aplicaciones que requieren transacciones complejas, relaciones complejas entre tablas y un alto grado de integridad de los datos pueden ser mejor servidas por una base de datos relacional tradicional.

- En resumen, MongoDB no es adecuado para todas las aplicaciones y puede tener algunos problemas con la integridad de los datos y los requisitos de recursos. Sin embargo, sigue siendo una opción popular y viable para muchas aplicaciones web modernas que requieren una estructura de datos flexible y escalabilidad horizontal.

# ¿Cómo se instala y configura MongoDB? ¿Cuáles son los requisitos mínimos de hardware y software?

La instalación y configuración de MongoDB varían según el sistema operativo utilizado. A continuación, se describen los requisitos mínimos de hardware y software para la instalación de MongoDB:

Requisitos de hardware:

Procesador de 64 bits.
Al menos 2 GB de RAM.
Espacio de disco duro disponible para los datos y los registros de MongoDB.
Requisitos de software:

Sistema operativo compatible, como Windows, macOS o Linux.
MongoDB Community Server, que es una distribución gratuita y de código abierto de MongoDB.
MongoDB Compass, que es una interfaz gráfica de usuario opcional para MongoDB.
Para instalar MongoDB, puede seguir los siguientes pasos generales:

Descargar la última versión de MongoDB Community Server desde el sitio web oficial de MongoDB.
Instalar MongoDB en su sistema operativo siguiendo las instrucciones específicas para su sistema operativo.
Configurar el archivo de configuración de MongoDB para especificar la ubicación de los datos y los registros de MongoDB.
Iniciar el servicio de MongoDB en el sistema operativo para comenzar a utilizar MongoDB.
Es importante seguir cuidadosamente las instrucciones específicas para su sistema operativo y su versión de MongoDB para asegurarse de que MongoDB se instale y configure correctamente.

Además, puede configurar MongoDB para ajustar su rendimiento y su seguridad, como la autenticación y el cifrado. Se recomienda que revise la documentación oficial de MongoDB para obtener más detalles sobre cómo configurar MongoDB según sus necesidades específicas.


## Autores ✒️

* **Guillermo Soler Fernández** - *Trello - Mongo* - [GuilleSoler87](https://github.com/GuilleSoler87)

* **Adrian Martínez Teba** - *Trello - Mongo* - [adrianMartinezTeba](https://github.com/adrianMartinezTeba)