
🛡️ Proyecto: EdinxoProtege - Auditoría de Red Residencial
Este repositorio documenta la intervención y endurecimiento (hardening) de una red local comprometida, aplicada como práctica profesional de ciberseguridad.

📝 Descripción del Caso
Se detectó una intrusión activa en la red de un cliente local. La red presentaba latencia alta y dispositivos desconocidos en la tabla de asignación DHCP.

🚀 Acciones Realizadas
Fase 1: Respuesta ante Incidentes
Detección de Intrusos: Identificación de dispositivos no autorizados mediante el análisis de la lista de clientes del router.

Recuperación de Acceso: Uso de Hotspot móvil para mantener la conectividad de dispositivos críticos (Smart TV) mientras se realizaba el saneamiento de la red principal.

Expulsión: Reset de credenciales inalámbricas y cambio de protocolos de seguridad.

Fase 2: Endurecimiento (Hardening) de Red
Optimización de Frecuencias: Configuración independiente para las bandas 2.4 GHz y 5 GHz para mejorar el rendimiento.

Control de Acceso (Capa 2): Implementación de Filtrado por Direcciones MAC (Whitelist), permitiendo exclusivamente el acceso a dispositivos de confianza del cliente.

Cifrado Robusto: Migración de seguridad básica a WPA2-AES para prevenir ataques de fuerza bruta.

Fase 3: Estrategia de Firewall (Próximamente)
Análisis de puertos críticos (21, 23, 445).

Desactivación de respuesta a PING (ICMP) desde la WAN para lograr invisibilidad en internet.

🛠️ Herramientas Utilizadas
Gestión de Router (Acceso vía Web GUI).

Análisis de direcciones MAC.

Documentación técnica en tiempo real.