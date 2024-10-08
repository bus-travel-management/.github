# Bus Travel Management

Este proyecto gestiona itinerarios de autobuses utilizando una arquitectura basada en microservicios. Los microservicios incluyen:

- **Itineraries**: Para gestionar los horarios y rutas de los autobuses.
- **Reservations**: Para gestionar las reservas de los usuarios.
- **Auth**: Servicio de autenticación y gestión de usuarios.
- **Chats**: Servicio de mensajería en tiempo real para la coordinación del personal.

## Arquitectura

![Arquitectura del sistema](https://github.com/user-attachments/assets/2bb6ff1d-0a78-42c0-b0e0-cb4a8070ced6)

El sistema está implementado utilizando **Docker** y orquestado con **Kubernetes**, con soporte para monitoreo a través de **Grafana** y **Prometheus**.
