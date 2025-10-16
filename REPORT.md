# Lab 3 Complete a Web API -- Project Report
# Práctica 3 - David Borrel Seral 871643

## Description of Changes
En esta tercera sesión de laboratorio, se han completado e implementado los tests para el `EmployeeController`REST API.
Los cambios realizados son los siguientes:

- Implementación de tests unitarios para los cuatro endpoints:
  - `POST /employees` → test de seguridad e idempotencia (no seguro, no idempotente)
  - `GET /employees/{id}` → test de seguridad e idempotencia (seguro, idempotente)
  - `PUT /employees/{id}` → test de seguridad e idempotencia (no seguro, idempotente)
  - `DELETE /employees/{id}` → test de seguridad e idempotencia (no seguro, idempotente)
- En cada test se han completado los bloques `SETUP` Y `VERIFY` para garantizar que los tests demuestran correctamente
  la seguridad e idempotencia de los métodos.

## Technical Decisions
- En esta práctica no ha sido necesario tomar ninguna decisión relevante, unicamente elegir las configuraciones de los bloques
 `SETUP` y `VERIFY` según el método correspondiente.

## Learning Outcomes
- Comprender la diferencia entre métodos **seguros** y **no seguros** , y su relación con la **idempotencia** en APIs REST.
- Continuar aprendiendo a usar **Mockk** para simular repositorios y controlar respuestas en tests unitarios de Spring Boot
  (ya se usó Mockk en la asginatura de Verificación y validación).
- Implementar pruebas completas que cubran todos los escenarios de comportamiento de los endpoints.

## AI Disclosure
### AI Tools Used
- ChatGPT 4o (OpenAI)
- GitHub Copilot

### AI-Assisted Work
- En esta práctica apenas se ha usado la IA, únicamente para comprender el uso de los bloques `SETUP` y `VERIFY`.
- También se ha usado para consultar algún error de compilación.
- Los conocimientos de la asignatura Verificación y validación han supuesto de gran ayuda para este laboratorio,
 haciendo que se reduzca considerablemente el uso de la IA.
- 10% IA <-> 90% David Borrel

### Original Work
- Comprensión y revisión inicial de toda la estructura del proyecto.
- Implementación y adaptación final de los tests en el proyecto.
- Redacción del REPORT.md.
- Arreglo de errores para hacer funcionar correctamente el workflow de GitHub Actions.
- Esta sesión de laboratorio ha sido de gran utilidad para aumentar los conocimientos sobre tests y la comprensión y
 aprendizaje de conceptos de REST, idempotencia y seguridad de métodos.