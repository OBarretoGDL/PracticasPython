# Máquina de Galton

La Máquina de Galton es un dispositivo inventado por Sir Francis Galton para demostrar la ley de los grandes números y la distribución normal. Este proyecto simula una Máquina de Galton utilizando Python y grafica la distribución de las canicas que caen a través de los niveles del dispositivo.

## Descripción del Proyecto

Este proyecto consta de dos partes principales:

1. **Simulación de la Máquina de Galton**: Una función que simula el comportamiento de una Máquina de Galton.
2. **Generación de la Gráfica**: Una función que grafica la distribución de las canicas utilizando `matplotlib`.

## Requisitos

Para ejecutar este proyecto, necesitarás tener instaladas las siguientes bibliotecas de Python:

- `numpy`
- `matplotlib`

Puedes instalarlas utilizando `pip`:

```sh
pip install numpy matplotlib

# Explicación del Código
Función MaquinaDeGalton:

Esta función simula el comportamiento de una Máquina de Galton.
Toma como parámetros el número de canicas (noCanicas) y el número de niveles (noNiveles).
Utiliza un bucle para simular el recorrido de cada canica a través de los niveles, aumentando o disminuyendo un contador basado en un valor booleano aleatorio.
Al final, retorna una lista con la distribución de las canicas.
Función plt_Graf:

Esta función toma los resultados de la simulación y los grafica utilizando matplotlib.
Utiliza un histograma para mostrar la distribución de las canicas a lo largo de las posiciones finales.
Ejecución de la Simulación y Generación de la Gráfica:

Se definen los parámetros noCanicas y noNiveles.
Se llama a la función MaquinaDeGalton para obtener los resultados de la simulación.
Se llama a la función plt_Graf para graficar los resultados.
Conclusión
Este proyecto proporciona una simulación sencilla y visualización de una Máquina de Galton. Permite observar cómo las canicas se distribuyen a lo largo de los niveles y cómo tienden a formar una distribución normal. Este ejemplo puede ser extendido y modificado para explorar diferentes aspectos de la teoría de probabilidades y estadísticas.
