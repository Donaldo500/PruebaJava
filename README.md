# PruebaJava

![Java](https://img.shields.io/badge/Java-17%2B-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-Java_Extension-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white)

Mi primer programa en **Java**. Sirvió para configurar el entorno de desarrollo en Visual Studio Code, entender la estructura mínima de una clase ejecutable y practicar ciclos, variables y salida por consola.

## Descripción

La clase `ProyectoJava` recorre un ciclo `for` de 1000 iteraciones, incrementa un contador y muestra en consola el valor del contador en cada iteración, separado por una línea divisoria.

Conceptos practicados:

- Estructura de una clase con método `main`.
- Declaración e incremento de variables enteras.
- Ciclo `for`.
- Concatenación de cadenas y `System.out.println`.

## Tecnologías utilizadas

- Java (cualquier JDK 17 o superior)
- Visual Studio Code con la extensión *Extension Pack for Java*

## Estructura del proyecto

```text
PruebaJava/
├── src/ProyectoJava.java   # Código fuente
├── bin/                    # Clases compiladas por VS Code
└── .vscode/settings.json   # Configuración del proyecto Java en VS Code
```

## Instalación y uso

### Desde la terminal

```bash
git clone https://github.com/Donaldo500/PruebaJava.git
cd PruebaJava
javac -d bin src/ProyectoJava.java
java -cp bin ProyectoJava
```

### Desde VS Code

1. Abre la carpeta del proyecto.
2. Abre `src/ProyectoJava.java`.
3. Presiona **Run** sobre el método `main`.

## Ejemplo de uso

Salida real (primeras y últimas líneas):

```text
El contador en la itracion [0] vale: 1
-----------------------------------------
El contador en la itracion [1] vale: 2
-----------------------------------------
...
El contador en la itracion [999] vale: 1000
-----------------------------------------
```

## Contribuciones

Proyecto individual de práctica. Puedes usarlo libremente como referencia.

## Autor

**Donaldo Ibarra** - [@Donaldo500](https://github.com/Donaldo500)
