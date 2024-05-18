Claro, aquí tienes un README para el programa conversor de moneda en Java:

# Conversor de Divisas

Este programa es un conversor de divisas que permite convertir una cantidad de una moneda a otra. El usuario puede seleccionar la moneda de origen y la moneda de destino, así como la cantidad a convertir. El programa mostrará el resultado de la conversión y guardará un historial de las conversiones realizadas.

## Requisitos

- Java 17 o superior

## Cómo ejecutar el programa

1. Clona o descarga el repositorio.
2. Compila el código fuente ejecutando el siguiente comando en la terminal dentro del directorio del proyecto:

```
javac Principal.java
```

3. Ejecuta el programa con el siguiente comando:

```
java Principal
```

## Funcionalidades

- Conversión de divisas: El programa permite convertir entre las siguientes divisas: USD, ARS, EUR, BRL, MXN, CNY, CHF, GBP y JPY.
- Historial de conversiones: El programa mantiene un historial de las conversiones realizadas, incluyendo la fecha y hora, la divisa de origen, la divisa de destino, la cantidad convertida y la tasa de cambio utilizada.
- Interfaz de línea de comandos: El programa utiliza una interfaz de línea de comandos para interactuar con el usuario.

## Estructura del proyecto

- `Principal.java`: Clase principal que contiene el método `main` y controla el flujo principal del programa.
- `ConversorDivisas.java`: Clase que contiene la lógica para realizar las conversiones de divisas.
- `HistorialConversiones.java`: Clase que mantiene el historial de las conversiones realizadas.
- `Conversion.java`: Clase que representa una conversión individual, con información sobre la divisa de origen, la divisa de destino, la cantidad convertida, la tasa de cambio y la fecha y hora de la conversión.
- `Divisas.java`: Clase que contiene una lista de las divisas soportadas por el programa.
- `SelectorDivisas.java`: Clase que muestra un menú al usuario para seleccionar una divisa.

## Contribuciones

Las contribuciones son bienvenidas. Si encuentras algún error o tienes sugerencias para mejorar el programa, por favor, crea un nuevo issue o envía una pull request.

## Licencia

Este proyecto está licenciado bajo la [Licencia MIT](LICENSE).
