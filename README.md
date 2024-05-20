<h1 align="center">PORTAFOLIO-DEC135-RC22051</h1>
<h1 align="center">UNIVERSIDAD DE EL SALVADOR</h1>
<p align="center">
Facultad Multidisciplinaria De Occidente<br>
Departamento de Ingeniería y Arquitectura<br>
Ingeniería en Desarrollo de Software<br>
  <br><img src="https://upload.wikimedia.org/wikipedia/commons/c/c8/Logo_UES.jpg" alt="Descripción de la imagen" width="400" height="500"><br>
</p>

## Asignatura:
Diseño y Estructura de Computadoras
Ciclo V / Tercer año

## Tema:
“Portafolio de ejercicios”

## Coordinador de Cátedra:
MEd. Jonathan Muñoz

## Tutor GT02:
Ing. Jonathan Roberto Muñoz Ramirez

## Alumno:
Guillermo Alexander Rodríguez Cortez

## Carnet:
RC22051

## Fecha:
19/5/2024



# Resolución de Ejercicios en Ensamblador

En este trabajo se realizo la resolución de los tres ejercicios propuestos para el portafolio, los cuales son los siguientes:

## 1. Resta de tres enteros.
En este jercicio se creo un código en lenguaje ensamblador que implementa la resta de tres números enteros utilizando registros de 16 bits.

[Ver archivo de Ejercicio 1](https://github.com/Guill2/PORTAFOLIO-DEC135-RC22051/blob/3208097dc390a840e71bc0cacc1ba7b43f33dd82/Ejercicio%201%20-%20Resta%20-%20RC22051)


Propósito: Este ejercicio nos ayuda a comprender cómo se manipulan y operan los datos en registros de menor tamaño.

## 2. Multiplicación. 
En este programa se realiza la multiplicación de dos números enteros utilizando registros de 8 bits.

[Ver archivo de Ejercicio 2]([src/Ejercicio 1 - Resta - RC22051](https://github.com/Guill2/PORTAFOLIO-DEC135-RC22051/blob/308f8e09ca69afd0ae0ca2c82a42ca3fdc9c7582/Ejercicio%202%20-%20Multiplicaci%C3%B3n%20-%20RC22051)

Propósito: Este ejercicio nos ayuda a entender los conceptos básicos de multiplicación y cómo se realizan estas operaciones a un bajo nivel.

## 3. División.   
En este ultimo ejercicio se creo un programa que realiza la división de dos números enteros utilizando registros de 32 bits.

[Ver archivo de Ejercicio 3]([src/resta.asm](https://github.com/Guill2/PORTAFOLIO-DEC135-RC22051/blob/7d939225b33e08b182ff545be727ad6607903f12/Ejercicio%203%20-%20Divisi%C3%B3n%20-%20RC22051))

Propósito: Este ejercicio brinda una comprensión más profunda de cómo se implementan las operaciones aritméticas básicas en lenguaje de bajo nivel y cómo manejar los resultados de la división.


El codigo con la resolución de cada uno viene en su respectivo archivo .txt

## Ensamblado y ejecucición de los programas

Para probar correctamente cada uno de los programas se debe hacer lo siguiente:

ir a la terminal y digitar lo siguiente para ensamblar el programa:
```bash
nasm -f elf32 nombrePrograma.asm
```
Luego para enlazar el archivo escribimos lo siguiente:
```bash
ld -o nombrePrograma nombrePrograma.o
```
y para finalizar ejecutamos los programas usando:
```bash
./nombrePrograma 
```


