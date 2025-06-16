# Virtual Threads Demo con Spring Boot 3.2 y Java 21

Este proyecto es una demo sencilla para probar el uso de **virtual threads** en Java 21 con Spring Boot 3.2.5. El endpoint `/api/slow` simula una operación bloqueante para observar cómo los virtual threads manejan múltiples solicitudes concurrentes.

---

## 🖥️ Entorno de desarrollo

Este proyecto fue desarrollado en un entorno **WSL 2 (Windows Subsystem for Linux)** con la siguiente configuración:

- **Distribución**: Ubuntu 22.04 LTS
- **Java**: 21
- **Spring Boot**: 3.2.5
- **Maven**: Usando wrapper (`./mvnw`)
- **Editor**: Visual Studio Code (accediendo desde WSL)

---

## 🚀 Cómo ejecutar el proyecto

./mvnw spring-boot:run

