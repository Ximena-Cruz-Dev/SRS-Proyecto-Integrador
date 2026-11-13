
# Investigación: Especificación de Requisitos de Software (SRS/ERS)

## Introducción

Antes de comenzar a desarrollar un sistema de software, es importante conocer qué necesita el usuario y cuáles serán las funciones que deberá cumplir el producto. Para organizar esta información se utiliza el documento conocido como SRS o ERS, que permite establecer los requisitos del sistema de una manera clara y ordenada.

En esta investigación se explica qué es un SRS, cuáles son sus beneficios, qué estructura propone la norma IEEE 830, qué características debe tener un buen requerimiento y qué herramientas existen para elaborar y controlar los cambios de este tipo de documentos.

## 1. ¿Qué es un SRS/ERS y qué problemas evita?

SRS significa *Software Requirements Specification* y ERS significa *Especificación de Requisitos de Software*. Es un documento donde se describen las necesidades, funciones y características que debe cumplir un sistema de software.

Su objetivo es que todas las personas involucradas en un proyecto, como los clientes, usuarios y desarrolladores, tengan una idea clara de lo que se va a construir. No explica cómo se programará el sistema, sino qué debe hacer y qué condiciones debe cumplir.

Por ejemplo, en una aplicación de biblioteca, un requisito puede indicar que el sistema debe permitir buscar libros por título o autor.

### Problemas que evita un SRS

- **Malentendidos:** ayuda a que los usuarios y desarrolladores comprendan lo mismo sobre el funcionamiento del sistema.
- **Falta de organización:** permite establecer las funciones y necesidades antes de comenzar a programar.
- **Funciones olvidadas:** ayuda a identificar todas las características que debe tener el producto.
- **Cambios descontrolados:** permite registrar y revisar las modificaciones de los requisitos.
- **Errores durante el desarrollo:** facilita detectar necesidades incompletas o confusas antes de construir el sistema.
- **Problemas en las pruebas:** sirve como base para comprobar que el software cumple con lo solicitado.

Un ejemplo sería cuando un cliente pide que una aplicación sea rápida. Esa indicación puede interpretarse de diferentes maneras. En cambio, si se establece que el sistema deberá mostrar los resultados de búsqueda en un máximo de dos segundos, será más sencillo comprobar si cumple con lo solicitado.

## 2. ¿Qué secciones propone IEEE 830 y qué contiene cada una?

La norma IEEE 830-1998 propone una estructura para organizar correctamente una Especificación de Requisitos de Software. Su estructura principal se divide en tres secciones: introducción, descripción general y requisitos específicos.

Aunque esta norma fue sustituida por ISO/IEC/IEEE 29148, continúa siendo una referencia importante para comprender cómo se organiza un SRS.

### 2.1 Introducción

Esta sección explica el propósito del documento y presenta información general sobre el proyecto. Incluye:

- **Propósito:** explica para qué se realiza el documento y quiénes lo utilizarán.
- **Alcance:** describe el producto que se desarrollará, sus objetivos y sus límites.
- **Definiciones y abreviaturas:** explica los términos técnicos y las siglas utilizadas.
- **Referencias:** presenta las fuentes y documentos relacionados con el proyecto.
- **Descripción general:** explica cómo está organizado el documento.

### 2.2 Descripción general

Presenta una explicación general del sistema y de las condiciones en las que funcionará. Incluye:

- **Perspectiva del producto:** explica cómo se relaciona el sistema con otros programas o servicios.
- **Funciones del producto:** presenta las principales actividades que realizará el software.
- **Características de los usuarios:** describe quiénes utilizarán el sistema y qué conocimientos pueden tener.
- **Restricciones:** establece los límites técnicos o condiciones que deben respetarse.
- **Suposiciones y dependencias:** menciona las condiciones que se consideran ciertas y los elementos externos necesarios para el funcionamiento.

### 2.3 Requisitos específicos

Es la sección donde se describen detalladamente las funciones y condiciones que debe cumplir el sistema. Puede incluir:

- **Interfaces externas:** explica cómo se comunicará el sistema con los usuarios, dispositivos y otros programas.
- **Requisitos funcionales:** describen las acciones que deberá realizar el software.
- **Requisitos de rendimiento:** establecen condiciones como tiempos de respuesta y capacidad de trabajo.
- **Requisitos de bases de datos:** indican qué información deberá almacenarse y cómo se organizará.
- **Restricciones de diseño:** señalan las condiciones técnicas que deben respetarse.
- **Atributos de calidad:** incluyen aspectos como seguridad, confiabilidad, disponibilidad y facilidad de uso.
- **Otros requisitos:** contemplan necesidades adicionales, como condiciones legales o de operación.

### Apéndices e índice

Los apéndices contienen información complementaria que puede ayudar a comprender el proyecto, mientras que el índice facilita localizar los diferentes apartados del documento.

**Ejemplo:** en un sistema de biblioteca, la introducción explicaría el propósito del sistema, la descripción general mencionaría que será utilizado por estudiantes y bibliotecarios, y los requisitos específicos indicarían cómo buscar libros, registrar préstamos y controlar devoluciones.

## 3. ¿Qué características debe tener un buen requerimiento?

Un requerimiento es una condición o función que el sistema debe cumplir para satisfacer una necesidad del usuario. Para que sea útil, debe estar redactado de manera que cualquier persona involucrada en el proyecto pueda comprenderlo.

Las principales características de un buen requerimiento son:

1. **Claro:** debe entenderse fácilmente y no permitir diferentes interpretaciones.
2. **Completo:** debe contener toda la información necesaria para comprender lo que se solicita.
3. **Correcto:** debe representar una necesidad real del usuario.
4. **Consistente:** no debe contradecir otros requisitos.
5. **Verificable:** debe ser posible comprobar si se cumple mediante pruebas o revisiones.
6. **Factible:** debe poder realizarse con los recursos y la tecnología disponibles.
7. **Necesario:** debe tener una razón para formar parte del sistema.
8. **Trazable:** debe poder relacionarse con su origen y con las pruebas que permiten verificarlo.
9. **Atómico:** debe expresar una sola necesidad o función principal.

### Ejemplo de un requerimiento malo

"El sistema debe ser rápido y fácil de utilizar para todos".

**¿Por qué está mal?**

Porque no explica qué significa que sea rápido ni qué tan fácil debe ser utilizarlo. Cada persona podría interpretarlo de una manera diferente y no existe una forma clara de comprobar si se cumple.

### Ejemplo de un requerimiento bueno

"RF-01: El sistema deberá mostrar los resultados de búsqueda de libros en un máximo de 2 segundos, bajo una carga de hasta 1,000 registros y 50 usuarios concurrentes".

**¿Por qué está bien?**

Porque establece una función específica, indica un tiempo máximo de respuesta y menciona las condiciones en las que debe cumplirse. Esto permite realizar pruebas para verificar su funcionamiento.

Los valores utilizados son un ejemplo y deben revisarse para comprobar que sean adecuados para el proyecto.

## 4. ¿Qué plantillas y herramientas existen para escribir y versionar un SRS?

Para elaborar un SRS existen diferentes plantillas y herramientas que permiten organizar los requisitos, facilitar su redacción y mantener un registro de los cambios realizados.

### Plantillas que se pueden utilizar

- **Plantilla IEEE 830:** organiza el documento en introducción, descripción general y requisitos específicos.
- **Plantilla ISO/IEC/IEEE 29148:** permite organizar los requisitos siguiendo una norma más actual de ingeniería de requisitos.
- **Plantillas institucionales:** son formatos adaptados a las necesidades de una escuela, empresa o proyecto.
- **Plantillas Markdown:** permiten escribir documentos utilizando títulos, listas y tablas mediante archivos con extensión `.md`.

### Herramientas para escribir y administrar un SRS

| Herramienta | Utilidad |
|---|---|
| Microsoft Word | Permite redactar y dar formato a los documentos. |
| Google Docs | Facilita la escritura y revisión colaborativa. |
| Visual Studio Code | Permite editar archivos Markdown y trabajar con Git. |
| Git | Permite registrar y controlar las versiones de los archivos. |
| GitHub | Permite almacenar documentos, compartir cambios y colaborar en equipo. |
| Jira | Ayuda a organizar requisitos, tareas y actividades del proyecto. |
| IBM DOORS Next | Permite administrar requisitos y mantener su trazabilidad. |
| Jama Connect | Facilita la gestión, revisión y seguimiento de requisitos. |

### ¿Qué significa versionar un SRS?

Versionar un SRS significa guardar un historial de los cambios realizados en el documento. Esto permite conocer qué se modificó, cuándo se hizo y recuperar versiones anteriores cuando sea necesario.

Por ejemplo, si el equipo decide cambiar el tiempo de respuesta de una aplicación, puede registrar esa modificación para que todos los integrantes conozcan cuál es la versión actual del requisito.

Git y GitHub permiten realizar este proceso mediante:

1. La creación de un repositorio para almacenar los documentos.
2. La organización de los archivos en carpetas.
3. La edición de los documentos.
4. Los *commits*, que registran los cambios realizados.
5. El historial de versiones, que permite consultar modificaciones anteriores.
6. Las ramas y solicitudes de cambios (*pull requests*), que facilitan revisar las aportaciones de los integrantes antes de integrarlas.

Para proyectos escolares pequeños, Markdown y GitHub pueden ser suficientes. En proyectos más grandes se pueden utilizar herramientas especializadas como IBM DOORS Next o Jama Connect.

## Resumen de hallazgos

Al realizar esta investigación comprendí que un SRS o ERS es un documento importante dentro del desarrollo de software, ya que permite organizar las necesidades de los usuarios y establecer lo que debe cumplir un sistema. También ayuda a evitar confusiones, errores y problemas durante el desarrollo, porque todos los integrantes pueden consultar los mismos requisitos.

La estructura propuesta por IEEE 830 se divide principalmente en introducción, descripción general y requisitos específicos. Cada sección tiene una función diferente y permite presentar la información de manera ordenada. También aprendí que un buen requerimiento debe ser claro, completo, consistente y verificable, para que no existan dudas sobre lo que se necesita desarrollar.

Finalmente, existen diferentes herramientas para elaborar y administrar estos documentos. Algunas de ellas son Word, Google Docs, Visual Studio Code, Git y GitHub. Estas herramientas facilitan el trabajo individual y colaborativo, además de permitir conservar un historial de los cambios. En conclusión, realizar una buena especificación de requisitos ayuda a que un proyecto de software esté mejor organizado y responda a las necesidades reales de sus usuarios.

## Declaración sobre el uso de inteligencia artificial

Se utilizó ChatGPT como apoyo para organizar las ideas y dar estructura a la investigación. También ayudó a mejorar la redacción de algunos apartados. El contenido se revisó tomando como referencia las fuentes consultadas.

## Referencias (formato APA 7)

Institute of Electrical and Electronics Engineers. (1998). *IEEE recommended practice for software requirements specifications* (IEEE Std 830-1998). https://standards.ieee.org/ieee/830/1222/

International Organization for Standardization. (2018). *Systems and software engineering—Life cycle processes—Requirements engineering* (ISO/IEC/IEEE 29148:2018). https://www.iso.org/standard/72089.html

National Aeronautics and Space Administration. (s. f.). *Appendix C: How to write a good requirement—Checklist*. NASA. https://www.nasa.gov/reference/appendix-c-how-to-write-a-good-requirement/

