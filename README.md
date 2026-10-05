# ServiConecta — Demo Aplicación Orientada a Servicios (SOA)

Demo educativa de una plataforma de reservas de servicios profesionales que ilustra los principios de **Arquitectura Orientada a Servicios (SOA)**.

## 🧩 Servicios implementados

| Servicio | Endpoint simulado | Descripción |
|---|---|---|
| Usuarios | `POST /api/usuarios/login` | Autenticación y emisión de token JWT |
| Catálogo | `GET/POST /api/catalogo/servicios` | Listado y publicación de servicios |
| Reservas | `POST /api/reservas` | Orquesta Catálogo + Pagos + Notificaciones |
| Pagos | `/api/pagos` | Cobro y comisión |
| Notificaciones | `/api/notificaciones` | Aviso al proveedor |

## 🚀 Uso

Abre `index.html` directamente en el navegador — no requiere servidor ni dependencias.

## 📐 Principios SOA demostrados

- **Bajo acoplamiento**: cada servicio tiene su propio contrato y estado
- **Autonomía**: los servicios operan de forma independiente
- **Descubrimiento**: Service Registry centralizado
- **Composición**: el Servicio de Reservas orquesta múltiples servicios
- **API Gateway**: enrutamiento y registro de llamadas en tiempo real
