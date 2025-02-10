# Gestión de Ventas Mensuales
Este proyecto implementa un programa en Python y Java para gestionar ventas mensuales en una matriz bidimensional. Cada fila representa un mes del año y cada columna representa un departamento (Ropa, Deportes, Juguetería).

Funcionalidades

El programa ofrece tres funciones principales:

Insertar una venta: Permite registrar una venta en un mes y departamento específicos.

Buscar una venta: Localiza una venta específica en la matriz y devuelve su ubicación.

Eliminar una venta: Remueve una venta de la matriz estableciendo su valor en 0.

Estructura de la matriz

La matriz tiene dimensiones 12x3, representando:

Filas (0-11): Meses del año, desde enero hasta diciembre.

Columnas (0-2): Departamentos: Ropa, Deportes y Juguetería.

Uso

Python

Ejecutar el script ventas_python.py para probar las funciones:

matriz_ventas = crear_matriz()
insertar_venta(matriz_ventas, 0, 0, 5000)  # Enero, Ropa
print(buscar_venta(matriz_ventas, 5000))
eliminar_venta(matriz_ventas, 0, 0)
print(buscar_venta(matriz_ventas, 5000))

Java

Compilar y ejecutar Ventas.java:

javac Ventas.java
java Ventas

Requisitos

Python 3.x para la versión en Python

JDK 8+ para la versión en Java

Contribución

Sube tus cambios al repositorio de GitHub y crea un Pull Request si deseas mejorar el código.


