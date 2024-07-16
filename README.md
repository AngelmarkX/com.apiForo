# Conversor de Monedas

Challenge conversor de Monedas Alura - Miguel Angel Zuluaga

Este es un conversor de monedas simple en Java que utiliza la API de ExchangeRate-API para obtener los tipos de cambio actuales y realizar conversiones entre diferentes monedas.

## Características

- Obtiene tasas de cambio en tiempo real de la API de ExchangeRate-API.
- Convierte una cantidad especificada de una moneda base a una moneda objetivo.
- Manejo de errores mejorado para casos de códigos de moneda inválidos o errores de API.

## Métodos

- **main(String[] args)**: Método principal que ejecuta el programa. Solicita al usuario la moneda base, la moneda objetivo y la cantidad a convertir. Luego, llama al método `convertirMoneda` para realizar la conversión y mostrar el resultado.

- **convertirMoneda(String base, String objetivo, double cantidad)**: Este método realiza la conversión de la moneda utilizando la API de ExchangeRate-API. Construye la URL de la solicitud, realiza la llamada a la API y procesa la respuesta JSON.

## Variables

- `CLAVE_API`: Clave de la API para autenticarse con ExchangeRate-API.
- `URL_BASE`: URL base para las solicitudes a la API de ExchangeRate-API.


## Llamada a la API

![image](https://github.com/user-attachments/assets/8bc03614-d01a-4723-8b81-7db71ab4478f)
