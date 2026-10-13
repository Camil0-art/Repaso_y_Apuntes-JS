# Introducción a la programación con JavaScript - Errores sintácticos y lógicos

### Codificaremos un nuevo programa y agregaremos adrede una serie de errores tipográficos. Este tipo de errores siempre son detectados por el intérprete de JavaScript, durante la ejecución del programa.

### A los errores tipograficos, como por ejemplo indicar el nombre incorrecto de una funcion, nombres de variables incorrectas, falta de paréntesis, palabras claves mal escritas, etc. los llamamos errores SINTACTICOS.

### Un programa no se puede ejecutar por completo sin corregir los errores sintacticos.

### Existe otro tipo de errores llamados ERRORES LOGICOS. Este tipo de errores en programas grandes (miles de lineas) son mas difíciles de localizar. Por ejemplo un programa que permite hacer la facturación pero la salida de datos por impresora es incorrecta.

```javascript
<script>
let num1=70
let num2=30
let suma=num1+num2
Document.write("La suma de 70 y 30 es ")
document.write(suma)
</script>
```

### El Siguiente error Ocurre por la tipografia y es cuando cambiamos el nombre de document a => Document Lo cual nos genera un error y por consecuencia no se puede ejecutar

### Para nuestra salvacion tenemos varios amigos que nos dice donde se encuentra el error (Consola de Google, el mismo Visual Studio Code etc)

```Consola
Uncaught TypeError: Document.write is not a function at programa002.html:14:14
```