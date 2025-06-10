# AgenciaVentaVehiculos
Backend para agencia automotriz que gestiona pruebas de vehículos con integración de API externa, cálculos complejos y sistema de notificaciones.


⚙️ Funcionalidades Clave
- **Modelado de entidades**: Diseño de tablas para vehículos, clientes, empleados y pruebas
- **Cálculos técnicos**: Consumo de API externa para parámetros de coordenadas permitidas en las pruebas
- **Sistema de notificaciones**: Alertas automáticas cuando los resultados difieren de lo esperado, carga automática a la base de datos de notificación
- **Registro histórico**: Trazabilidad completa de todas las pruebas realizadas


📡 Endpoints para los reportes.

localhost:8888/informes/incidentes
localhost:8888/informes/detalle/#id_empleado
localhost:8888/informes/detalle/vehiculo/#id_vehiculo

🧪 Endpoints para la generacion de notificaciones para vehiculos fuera de coordenadas permitidas

localhost:8888/prueba/validar-posicion/#coordenada_latitud/#coordenada_longitud/#id_vehiculo

