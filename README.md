# API REST - Regalos Solidarios

Este repositorio contiene la definición de la API REST de **Regalos Solidarios**, una aplicación web orientada a la gestión de listas de deseos solidarios en contextos de infancia vulnerable.

La API se ha definido mediante **OpenAPI** y funciona como contrato entre el frontend y una posible futura implementación del backend. Aunque el proyecto no incluye un backend real, esta especificación permite documentar los recursos principales del sistema, definir las estructuras de datos intercambiadas y facilitar la creación de respuestas simuladas mediante WireMock.

## Objetivo del repositorio

El objetivo de este repositorio es centralizar la especificación de la API REST utilizada por la aplicación.

Esta definición permite:

- Documentar los endpoints disponibles.
- Definir los métodos HTTP utilizados.
- Establecer los formatos de entrada y salida.
- Describir los principales recursos del sistema.
- Facilitar el desarrollo del frontend sin depender de un backend real.
- Servir como base para una futura implementación del servidor.

## Tecnologías utilizadas

- **OpenAPI**: especificación utilizada para definir la API REST.
- **YAML**: formato empleado para describir la especificación.
- **JSON**: formato de intercambio de datos entre cliente y servidor.
- **WireMock**: herramienta utilizada en el proyecto frontend para simular las respuestas del backend.