# Ejercicio 13 - JavaFX

## Descripción

Este proyecto corresponde al ejercicio 13 del bloque BC5 de JavaFX.

El objetivo del ejercicio es crear un formulario que permita introducir una dirección en un campo de texto y mostrar un mensaje de confirmación al pulsar un botón.

## Tecnologías utilizadas

- Java
- JavaFX
- Maven
- IntelliJ IDEA

## Funcionamiento

La aplicación muestra una ventana con:

- Una etiqueta indicando al usuario que introduzca una dirección.
- Un campo de texto para escribir la dirección.
- Un botón para confirmar la dirección.
- Una etiqueta donde aparece el resultado.

Si el usuario pulsa el botón sin escribir nada, aparece un mensaje de error.

Si el usuario escribe una dirección y pulsa el botón, aparece un mensaje confirmando la dirección introducida.

## Conceptos utilizados

- `Application`: clase base para crear aplicaciones JavaFX.
- `Stage`: ventana principal de la aplicación.
- `Scene`: contenido visual de la ventana.
- `Label`: control utilizado para mostrar texto.
- `TextField`: campo de texto donde el usuario puede escribir.
- `Button`: botón que ejecuta una acción.
- `setOnAction`: método utilizado para controlar el evento del botón.
- `getText`: método que obtiene el texto escrito en el campo.
- `setText`: método que cambia el texto de una etiqueta.
- `isEmpty`: método usado para comprobar si el campo está vacío.
- `VBox`: layout que organiza los elementos en vertical.

## Estructura del proyecto

```text
Ejercicio13_JavaFX
 ├── pom.xml
 └── src
     └── main
         └── java
             └── org
                 └── example
                     └── Main.java
```

## Cómo ejecutar el proyecto

Para ejecutar el proyecto desde IntelliJ IDEA:

1. Abrir el proyecto en IntelliJ.
2. Sincronizar el archivo `pom.xml` con Maven.
3. Abrir el panel Maven.
4. Ejecutar:

```bash
mvn javafx:run
```

## Autor

Andrés Huéscar Fernández
