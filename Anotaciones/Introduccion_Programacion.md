# Introduccionn a la programacion con JavaScript

## Conceptos Basicos.

#### Programa: Conjunto de Instrucciones, que entiende una computadora, para realizar una actividad.

#### Algoritmo: Son los pasos a seguir para resolver un problema.

#### Diagrama de Flujo: Representacion grafica de un Algoritmo.

---

## Elementos graficos de un diagrama de flujo

#### - Simbolo de ovalo o capsula (Terminal): Inidica el Inicio y el Fin del Diagrama

#### - Símbolo de paralelogramo (Entrada de datos): Representa la entrada de datos 

#### (Vamos a considerar que las entradas de datos se realizan siempre por el teclado de la computadora).

#### - Símbolo de documento con borde inferior ondulado / rectángulo con base curva (Salida de datos): Representa la salida de datos 

#### (Vamos a considerada que las salidas de datos se realizan siempre por la ventana del navegador).

#### - Símbolo de rectángulo (Operación): Representa un proceso u operación.   

#### - Símbolo de rombo (Condición): Representa una decisión o condición

---

## Variable

#### Una variable es un depósito donde hay un valor.

#### Consta de un nombre y pertenece a un tipo: numeric, string etc.

#### Utilizamos la palabra clave let para definir una variable y el operador de asignación que es el carácter = si queremos cargar un valor inmediatamente:

```javascript
let nombre = "Juan"
let edad = 50


#### Si al valor lo ingresamos por teclado deberemos utilizar la función prompt:

```javascript
let nombre = prompt("Ingrese el nombre")
let edad = parseInt(prompt("Ingrese la edad"))


#### Las variables son nombres que ponemos a los lugares donde almacenamos la información.

#### En JavaScript, deben comenzar por una letra, pudiendo haber además dígitos luego de la primera posición. Una variable no puede tener el mismo nombre que una palabra clave del lenguaje.

#### El lenguaje JavaScript es sensible a mayúsculas y minúsculas, es decir que las variables edad y EDAD son distintas:

```javascript
let edad = 50
let EDAD = 10

#### Las palabras claves del lenguaje deben escribirse siempre con minúsculas: let, if, while, etc.








