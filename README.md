# Calculadora de Índice de Masa Corporal (IMC)

Este proyecto es parte del módulo uno del curso de Python. El objetivo es crear un programa que calcule el Índice de Masa Corporal (IMC) basado en los datos proporcionados por el usuario: nombre, apellido paterno, apellido materno, edad, peso y estatura. El programa valida los datos ingresados y asegura que el IMC solo se calcule para usuarios mayores de edad.

## Descripción

El Índice de Masa Corporal (IMC) es una medida que se utiliza para determinar si una persona tiene un peso saludable en relación con su estatura. El IMC se calcula utilizando la siguiente fórmula:

\[ \text{IMC} = \frac{\text{peso (kg)}}{\text{estatura (m)}^2} \]

El programa realiza las siguientes acciones:
1. Solicita al usuario su nombre, apellido paterno, apellido materno, edad, peso y estatura.
2. Valida que la edad sea mayor a 18 años.
3. Calcula el IMC.
4. Determina el estado del IMC (peso bajo, peso normal, sobrepeso, obesidad leve, obesidad media, obesidad mórbida).
5. Imprime los datos ingresados y el resultado del IMC junto con su clasificación.

## Requisitos

- Python 3.x

## Cómo usar el programa

1. Clona este repositorio o descarga los archivos del proyecto.
2. Ejecuta el archivo principal del programa (por ejemplo, `main.py`).
3. Sigue las instrucciones en pantalla para ingresar los datos solicitados.

## Ejemplo de uso

Ingrese solo su primer nombre: Juan
Ingrese su Apellido Paterno: Pérez
Ingrese su apellido Materno: López
Ingrese su edad: 25
Ingrese su estatura en formato 'Metros' (Eg 1.75): 1.80
Ingrese su peso en formato 'Kilos' (Eg 85.3): 75.5

Buen día Juan Pérez López
De acuerdo a los datos proporcionados:
Edad: 25, Estatura: 1.80 m, y Peso: 75.5 kg
se pudo determinar un Índice de Masa Corporal de 23.31,
lo que nos indica que usted se encuentra en 'Peso Normal'.
