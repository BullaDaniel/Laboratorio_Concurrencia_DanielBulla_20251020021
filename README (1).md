# Laboratorio de Concurrencia en Java

## Autor

Daniel Esteban Bulla López\
Universidad Distrital Francisco José de Caldas\
Ingeniería de Sistemas --- Programación Avanzada

------------------------------------------------------------------------

## Descripción del proyecto

Este proyecto contiene la implementación de 10 ejercicios prácticos de
programación concurrente en Java, donde se abordan problemas clásicos de
sincronización de hilos y acceso a recursos compartidos.

Los ejercicios incluyen el uso de:

-   synchronized
-   wait() / notifyAll()
-   Semaphore
-   ReentrantLock
-   BlockingQueue
-   Threads (Thread y Runnable)

El objetivo es comprender el comportamiento de los hilos en ejecución
concurrente y aplicar mecanismos de sincronización para evitar errores
como condiciones de carrera y deadlocks.

------------------------------------------------------------------------

## Objetivos

-   Comprender el funcionamiento de la programación concurrente en Java.
-   Implementar mecanismos de sincronización entre hilos.
-   Resolver problemas clásicos de concurrencia.
-   Analizar el acceso a recursos compartidos.
-   Aplicar buenas prácticas en el diseño de sistemas concurrentes.

------------------------------------------------------------------------

## Requisitos

Para ejecutar el proyecto se requiere:

-   Java JDK 8 o superior
-   IDE compatible con Java (recomendado):
    -   IntelliJ IDEA
    -   Eclipse
    -   NetBeans

Verificar instalación con:

    java -version

------------------------------------------------------------------------

## Instalación

1.  Descargar el archivo .zip del proyecto.
2.  Descomprimir el archivo.
3.  Abrir el IDE de preferencia.
4.  Importar el proyecto:

### IntelliJ IDEA

-   File → Open
-   Seleccionar la carpeta del proyecto
-   Esperar a que el IDE indexe los archivos

### Eclipse

-   File → Import
-   Existing Projects into Workspace
-   Seleccionar la carpeta del proyecto

------------------------------------------------------------------------

## Ejecución

1.  Localizar la clase `Main` dentro de cada ejercicio.
2.  Abrir el archivo correspondiente.
3.  Ejecutar el programa:

En IDE: - Click derecho → Run

Por consola:

    javac Main.java
    java Main

Cada ejercicio tiene su propio método `main`, por lo que deben
ejecutarse de manera independiente.

------------------------------------------------------------------------

## Contenido del proyecto

El proyecto incluye los siguientes ejercicios:

1.  Contador compartido
2.  Simulación de cajeros automáticos
3.  Productor--Consumidor
4.  Lectores y Escritores
5.  Barrera de sincronización
6.  Deadlock y solución
7.  Filósofos comensales
8.  Control de acceso con semáforos
9.  Cola de tareas concurrente
10. Simulación de tráfico con locks

Cada ejercicio incluye:

-   Código fuente
-   Explicación del funcionamiento
-   Diagrama de clases
-   Ejemplo de ejecución

------------------------------------------------------------------------

## Objetivo académico

Aplicar conceptos de concurrencia y sincronización en Java para
comprender problemas reales de acceso concurrente a recursos
compartidos.

------------------------------------------------------------------------

## Licencia

Uso académico.
