# ISO2-2026-B2.01-Testing-P1

## Enunciado

Se trata de escribir y probar un método que, aceptando dos objetos de tipo fecha/hora (representando el ticket de entrada y el de salida de un aparcamiento), devuelva el coste total de la estancia.

En caso de que la fecha de salida sea anterior a la de entrada, o se pasen objetos nulos, se tiene que lanzar una excepción que indique esta situación. Valore la posibilidad de realizar estas comprobaciones a nivel de constructor, usando los métodos que aseguran el encapsulamiento.

Además, complete lo que se necesite para incluir los siguientes aspectos:

- La interfaz de usuario será en línea de comandos. Desarrolle un componente con clases y métodos específicos para leer datos de teclado y escribir en pantalla.
- Las reglas de negocio estipulan que los primeros 30 minutos son gratuitos. A partir de ahí, se cobra a 0,05 € el minuto, con un tope máximo diario de 20 €.
- Utilice excepciones para controlar el flujo del programa donde sea necesario.
- No acople las clases de la lógica de dominio con la interfaz de usuario.

## Parejas

| Pareja   | Integrantes                              |
|----------|------------------------------------------|
| Pareja 1 | Víctor Bravo y Juan Zopeque              |
| Pareja 2 | Álvaro García y Marcelino Izquierdo      |
| Pareja 3 | Raúl Arroyo y Abraham Escalona           |

## Tareas

| Tarea                    | Pareja responsable |
|--------------------------|--------------------|
| Implementación           | Pareja 1           |
| Diseño de pruebas        | Pareja 2           |
| Implementación de pruebas| Pareja 3           |
