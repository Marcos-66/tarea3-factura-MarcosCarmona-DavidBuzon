# Tarea 3 · La factura bajo el microscopio
Pareja: (nombre 1) y (nombre 2) · GitHub: (usuario 1), (usuario 2)

## Reto 1 · Compilar desde la terminal
- Comando usado y resultado (captura: capturas/reto1.png)
- ¿Qué es Factura.java?: Es el código fuente. El archivo que estamos utilizando en esta practica.
  ¿Y Factura.class?: Archivo compilado en bytecode, generado al utilizar javac.
  ¿Quién ejecuta el .class?: Lo ejecuta la JVM (Java Virtual Machine)
- ¿Por qué no se ha generado Factura.class la primera vez?: Debido a los errores que contiene el código.

## Reto 2 · Errores de compilación
| Nº | Línea | Mensaje de javac             | Tipo (léxico / sintaxis / semántica) | Corrección                                    |
|----|-------|------------------------------|--------------------------------------|-----------------------------------------------|
| 1  |   15  |error: illegal character: '#' |léxico                                |double precio                                  |
| 2  |   17  |error: ';' expected           |sintaxis                              |int cantidad = sc.nextInt.();                  |
| 3  |    29 |error: "int" no es compatible |semantica                             | double total = (base - descuento) * (1 + IVA);|

Captura del programa funcionando: capturas/reto2.png




## Reto 3 · Depuración del error lógico
| Variable | Valor esperado | Valor real |
|----------|----------------|------------|
| descuento |               |            |
| total     |               |            |
- Línea del error y explicación:
- Corrección:
- Mi propia prueba (producto, precio, cantidad, socio → total):
Captura del depurador: capturas/reto3.png

## Reto 4 · Reutilización
- Métodos creados y para qué sirve cada uno:
- ¿Qué ventaja tiene frente al código anterior?

## Reto 5 · ¿Qué lenguaje elegirías?
- Caso A (web de la tienda):
- Caso B (propuesta en ensamblador):