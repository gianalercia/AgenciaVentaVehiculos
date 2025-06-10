# AgenciaVentaVehiculos
El objetivo de este proyecto es hacer un backend para una agencia de venta de vehiculos que gestiona pruebas de manejo para aquellos clientes interesados en comprar. Cuenta con monitoreo en tiempo real mediante geolocalización, los parametros de dicha geolocalización provienen de una API externa, los endpoints permiten realizar estos cálculos y en respuesta se generan notificaciones en caso de que dichas pruebas se vuelvan incidentes al salirse de los parámetros establecidos.


⚙️ Funcionalidades Clave
- **Modelado de entidades**: Diseño de tablas para vehículos, clientes, empleados y pruebas
- **Cálculos técnicos**: Consumo de API externa para parámetros de coordenadas permitidas en las pruebas
- **Sistema de notificaciones**: Alertas automáticas cuando los resultados difieren de lo esperado, carga automática a la base de datos de notificación
- **Registro histórico**: Trazabilidad completa de todas las pruebas realizadas
- **Generación de reportes**: Se realizan reportes sobre los incidentes en pruebas de vehiculos, los incidentes registrados de cada empleado y los incidentes registrados para cada vehiculo con sus pruebas correspondientes.


📡 Endpoints para los reportes.

localhost:8888/informes/incidentes

localhost:8888/informes/detalle/#id_empleado

localhost:8888/informes/detalle/vehiculo/#id_vehiculo

🧪 Endpoints para la generacion de notificaciones para vehiculos fuera de coordenadas permitidas


localhost:8888/prueba/validar-posicion/#coordenada_latitud/#coordenada_longitud/#id_vehiculo

