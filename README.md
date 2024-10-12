# Conversor de Monedas - Java

Este proyecto es un programa en Java que actúa como un conversor de monedas. El usuario ingresa una moneda de origen, una moneda de destino y una cantidad a convertir. El programa realiza una solicitud a la API de ExchangeRate-API para obtener los datos y devolver el resultado.

## Funcionalidades:

- Convertir una moneda a otra.
- Ver el historial de conversiones hecha

## Requisitos

- Tener instalado Java 8 o una versión superior.
- Conexión a internet para obtener las tasas de cambio en tiempo real.

## Uso

1. Ejecuta el archivo `Principal.java`.
2. Sigue las instrucciones del menú para realizar conversiones o consultar el historial.

### Ejemplo de uso:

A continuación se muestra cómo compilar y ejecutar el programa:

- Abre una terminal o línea de comandos
- Navega hasta el directorio donde se encuentra el archivo `Principal.java`
- Compila el archivo `javac Principal.java`
- Ejecuta el programa compilado `java Principal`

Al iniciar el programa, aparecerá un menú donde el usuario deberá seleccionar la opción deseada ingresando el número correspondiente.
![Screenshot 2024-10-11 205311](https://github.com/user-attachments/assets/d6ba5daf-69bb-4292-8d93-17a594ddbf6e)

Al seleccionar la opción 1 en el menú principal, se mostrará un nuevo menú donde el usuario deberá elegir la moneda base para la conversión ingresando las tres letras que identifican su denominación.
![Screenshot 2024-10-11 205856](https://github.com/user-attachments/assets/4e839077-b045-4044-a315-c83d7cefe981)


![Screenshot 2024-10-11 205918](https://github.com/user-attachments/assets/f05dc548-261b-466a-b661-4d7d16c5aace)

Una vez que el usuario ha ingresado una moneda base válida, deberá seleccionar una moneda objetivo. Si ingresa una moneda no disponible, se le pedirá que ingrese una moneda válida. Posteriormente, deberá ingresar la cantidad que desea convertir.
![Screenshot 2024-10-11 210007](https://github.com/user-attachments/assets/7f1f1b28-3524-4f4c-a0e9-53754f7fe945)

Si el usuario introduce una cantidad no válida (que no sea un número), deberá volver a ingresar una cantidad correcta. Una vez que el usuario ingrese una cantidad válida, se mostrará el resultado y los detalles de la conversión solicitada.
![Screenshot 2024-10-11 210046](https://github.com/user-attachments/assets/5fd3018b-afe2-40ba-9902-e0b24e2be187)

Desde el menú principal, el usuario puede elegir la opción 2 para ver un registro detallado de las conversiones realizadas, mostrando la fecha y la hora de cada operación.
![Screenshot 2024-10-11 210125](https://github.com/user-attachments/assets/6cb5ee9f-934e-4767-9ef8-a1fb46efc945)

Por último, el usuario puede elegir la opción 3 para finalizar el programa.
![Screenshot 2024-10-11 210137](https://github.com/user-attachments/assets/f00056d0-3d8a-4dc4-b5ba-c5e8eb378fa2)

## Dependencias

- Gson: Se utiliza para gestionar los datos JSON que se obtienen de la API.
- Java HttpClient: Permite realizar solicitudes HTTP a la API de ExchangeRate-API.

## Autor
Andy Ruiz

