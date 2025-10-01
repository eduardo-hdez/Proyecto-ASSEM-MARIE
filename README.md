# Procesamiento de Temperaturas en Ensamblador (MARIE)

El proyecto consiste en un programa en ensamblador para la arquitectura educativa MARIE que trabaja con una lista de 30 temperaturas en grados Celsius. El programa busca el valor más bajo y más alto junto con su posición, ordena la lista usando Bubble Sort, calcula la mediana y convierte las temperaturas a Fahrenheit con una tabla ya definida. 

Además, el proyecto está relacionado con el estudio de sistemas de control electrónico (ECU), que son cruciales en tecnologías como los sistemas antibloqueo de frenos (ABS) en autos. En el reporte técnico se explica cómo estos sistemas han evolucionado desde computadoras básicas hasta sistemas inteligentes que integran sensores y actuadores para mejorar la seguridad y eficiencia en sectores como la automoción y la aeroespacial. También se incluyen diagramas del flujo del programa, que ayuda a entender cómo funcionan las diferentes partes del código y cómo se manejan los datos paso a paso usando punteros e índices.

## Funcionalidades

* **Búsqueda de mínimo y máximo**:
Encuentra la temperatura más baja y más alta, mostrando su valor y posición en segundos (cada 10 segundos).

* **Ordenamiento con Bubble Sort**:
Ordena la tabla de temperaturas usando el algoritmo de ordenamiento "Bubble Sort", directamente en memoria.

* **Cálculo de mediana**:
Obtiene la mediana de la lista ordenada.

* **Conversión de Celsius a Farenheit**:
Convierte cada temperatura utilizando una tabla auxiliar de valores pre-calculados y muestra los resultados.

## Estructura

* Código con **subrutinas** para cada funcionalidad principal (min/max, mediana, conversión).

* Uso explícito de **punteros**, **índices** y **tablas de memoria**.

* Con **comentarios en español** para facilitir el análisis de código y la comprensión del flujo de control.

## Ejecución

Para ejecutar este programa, es necesario descargar el archivo (.mas) que se encuentra en el repositorio:

`reporte_tecnico_codigo`
 
Luego, se debe abrir el simulador MARIE, que puede ser usado en la siguiente versión web:

https://marie.js.org/

Una vez en el simulador, se debe cargar el archivo descargado utilizando la opción de cargar archivo, y posteriormente ensamblar el código para generar el archivo ejecutable. 

Finalmente, se puede ejecutar o simular el programa dentro del entorno de MARIE para observar los resultados de las operaciones sobre la lista de temperaturas.


## Créditos

Este proyecto fue desarrollado como parte de la materia de **"Modelación de sistemas mínimos y arquitecturas computacionales"** del Tecnológico de Monterrey.
