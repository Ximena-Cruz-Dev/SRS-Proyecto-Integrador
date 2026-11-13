# 1. Introduccion
El presente proyecto consiste en desarrollar un videojuego educativo dirigido a niños de 5 a 7 años, con el propósito de fomentar el cuidado y uso responsable del agua potable. Mediante actividades, retos y dinámicas interactivas, se busca enseñar a los niños la importancia de ahorrar agua y adoptar buenos hábitos desde temprana edad, utilizando la tecnología como una herramienta de aprendizaje divertida y educativa.

## 1.1 Propósito
Describir las características y los requerimientos necesarios para desarrollar el videojuego, estableciendo sus objetivos y funciones principales.

## 1.2 Alcance
El videojuego busca enseñar a los niños a ahorrar agua, evitar desperdiciarla y desarrollar buenos hábitos mediante retos y actividades interactivas.

## 1.3 Glosario
- Videojuego educativo: Juego diseñado para enseñar mientras se juega.
ODS 6: Objetivo que promueve el agua limpia y el saneamiento.
- Usuario: Persona que utiliza el videojuego.
- Requerimiento funcional: Función que debe realizar el videojuego.
- Requerimiento no funcional: Características de calidad, como facilidad de uso y rapidez.
Agua potable: Agua apta para el consumo humano.

# 2. Descripción general

## 2.1 Usuarios
El videojuego está dirigido principalmente a niños de 5 a 7 años de Manzanillo, Colima, que aprenderán mediante juegos y actividades interactivas cómo cuidar el agua potable.

## 2.2 Restricciones
- Debe ser sencillo y fácil de utilizar.
- El contenido debe ser adecuado para niños de 5 a 7 años.
- Debe contar con instrucciones claras e imágenes llamativas.
- Su desarrollo dependerá de los conocimientos y recursos disponibles del equipo.

## 2.3 Supuestos
- Se considera que los niños tendrán acceso a una computadora para utilizar el videojuego.
- Los usuarios podrán comprender instrucciones sencillas con apoyo de imágenes.
- Los niños contarán con apoyo de un adulto si lo necesitan.
- Se espera que las actividades ayuden a mejorar sus hábitos sobre el cuidado del agua.

# 3. Requerimientos del sistema

## 3.1 Requerimientos funcionales

Los requerimientos funcionales describen las acciones y funciones que deberá realizar el videojuego para que los niños puedan interactuar con las actividades relacionadas con el cuidado del agua.

### RF-01. Selección de respuestas y acciones
**Descripción:** El videojuego deberá permitir que el jugador seleccione respuestas o acciones durante las actividades relacionadas con el cuidado responsable del agua.

**Prioridad:** Alta.

**Criterios de aceptación:**
- El jugador puede seleccionar una opción durante una actividad.
- El sistema identifica la opción seleccionada.
- La selección permite continuar con la actividad.

### RF-02. Retroalimentación de respuestas
**Descripción:** El videojuego deberá mostrar mensajes de retroalimentación cuando el jugador seleccione una respuesta, indicando si su elección es correcta o incorrecta.

**Prioridad:** Alta.

**Criterios de aceptación:**
- El sistema identifica si la respuesta seleccionada es correcta o incorrecta.
- Se muestra un mensaje que explica el resultado de la selección.
- La retroalimentación es comprensible para niños de 5 a 7 años.

### RF-03. Sistema de recompensas
**Descripción:** El videojuego deberá otorgar gotas de agua o puntos al jugador por completar correctamente las actividades, con el propósito de motivar su participación.

**Prioridad:** Alta.

**Criterios de aceptación:**
- El jugador recibe gotas o puntos al cumplir correctamente una actividad.
- El sistema muestra la cantidad de gotas o puntos obtenidos.
- Las recompensas se relacionan con el avance del jugador.

### RF-04. Avance por niveles
**Descripción:** El videojuego deberá permitir que el jugador avance por diferentes niveles o actividades conforme vaya completando los retos relacionados con el cuidado del agua.

**Prioridad:** Media.

**Criterios de aceptación:**
- El jugador puede acceder al siguiente nivel al completar el anterior.
- El sistema reconoce cuándo se ha terminado una actividad.
- El avance del jugador se muestra de manera sencilla.

### RF-05. Visualización de resultados finales
**Descripción:** Al finalizar las actividades, el videojuego deberá mostrar los resultados obtenidos por el jugador, incluyendo las gotas o puntos acumulados y su progreso durante el juego.

**Prioridad:** Media.

**Criterios de aceptación:**
- El sistema muestra los puntos o gotas acumulados.
- Se indica que las actividades han finalizado.
- Los resultados se presentan de manera clara y comprensible.

## 3.2 Requerimientos no funcionales

Los requerimientos no funcionales establecen las características de calidad, facilidad de uso y presentación que deberá cumplir el videojuego.

### RNF-01. Interfaz visual atractiva
**Descripción:** El videojuego deberá contar con una interfaz colorida y atractiva, utilizando elementos visuales relacionados con el agua y el medio ambiente para captar la atención de los niños.

**Prioridad:** Alta.

**Criterios de aceptación:**
- La interfaz utiliza colores llamativos y agradables.
- Los elementos visuales se relacionan con la temática del agua.
- Las pantallas mantienen un diseño uniforme.

### RNF-02. Facilidad de lectura
**Descripción:** El videojuego deberá utilizar letras grandes, textos breves e imágenes que faciliten la comprensión de las instrucciones para niños de 5 a 7 años.

**Prioridad:** Alta.

**Criterios de aceptación:**
- Los textos se pueden leer fácilmente.
- Las instrucciones son cortas y claras.
- Las imágenes ayudan a comprender las actividades.

### RNF-03. Tiempo de respuesta
**Descripción:** El videojuego deberá responder de manera rápida a las acciones realizadas por el jugador, evitando retrasos que dificulten la interacción.

**Prioridad:** Alta.

**Criterios de aceptación:**
- Las opciones seleccionadas generan una respuesta del sistema.
- Los mensajes de retroalimentación aparecen sin retrasos perceptibles.
- La navegación entre actividades funciona correctamente.

### RNF-04. Lenguaje sencillo
**Descripción:** El videojuego deberá utilizar un lenguaje sencillo y apropiado para la edad de los usuarios, evitando palabras complicadas o explicaciones demasiado extensas.

**Prioridad:** Alta.

**Criterios de aceptación:**
- Las instrucciones utilizan palabras fáciles de comprender.
- Los mensajes son adecuados para niños de 5 a 7 años.
- Las explicaciones permiten entender las actividades sin dificultad.

### RNF-05. Contenido apropiado para los usuarios
**Descripción:** El videojuego deberá presentar información y actividades educativas adecuadas para niños de 5 a 7 años, promoviendo buenos hábitos relacionados con el cuidado del agua.

**Prioridad:** Alta.

**Criterios de aceptación:**
- Las actividades contienen ejemplos apropiados para la edad.
- La información fomenta el cuidado responsable del agua.
- No se presentan contenidos violentos o inapropiados para los usuarios.
