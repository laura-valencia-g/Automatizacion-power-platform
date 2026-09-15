# Automatización de Procesos con Microsoft 365 y Power Platform

Diseño e implementación de flujos de automatización de ejemplo usando Power Automate (Web y Desktop), Power Apps y Power BI, como parte de una consultoría de transformación digital para una empresa de comercio internacional.

*Proyecto de práctica profesional — Universidad EAFIT, 2025.*

> **Nota:** Los flujos, aplicaciones y datos mostrados aquí son ejemplos ilustrativos construidos con datos de prueba, diseñados para demostrar el alcance técnico de una propuesta de automatización — no reflejan procesos, cifras ni información real de ninguna empresa.

## Objetivo

Diseñar y documentar ejemplos funcionales de automatización de procesos operativos (recepción de documentos, aprobaciones, notificaciones, generación de reportes) usando el ecosistema Microsoft 365 / Power Platform, evaluando su viabilidad técnica y de costos para una pyme.

## Flujos desarrollados — Power Automate (Web)

- **Creación de archivo desde adjunto de correo**: al llegar un correo con un documento adjunto, el flujo lo descarga automáticamente y lo organiza en OneDrive, con notificación de confirmación.
- **Recordatorio programado de envío de informes**: flujo de ejecución periódica que notifica a los usuarios (vía Teams) sobre pendientes de reporte.
- **Creación programada de tareas en Planner**: generación automática y mensual de tareas de seguimiento.
- **Notificación de recepción de paquetes (integrado con Power Apps)**: al registrarse un nuevo paquete en la app, se guarda en una lista de SharePoint y se dispara una notificación automática.
- **Solicitud y aprobación de permisos (Forms)**: formulario de solicitud que dispara un flujo de aprobación/rechazo con notificación automática al solicitante.
- **Envío de reporte de cartera**: flujo mensual que lee una base de datos en Excel, genera una tabla personalizada por cliente y envía el reporte, actualizando el estado de notificación.
- **Registro automático de facturación electrónica**: extracción de archivos XML/PDF desde un correo con adjunto ZIP, organización en carpetas y registro automático en Excel.

## Flujos desarrollados — Power Automate (Desktop)

- **Reporte de utilidades**: automatización de lectura de ventas y costos en Excel para calcular utilidades sin intervención manual.
- **Extracción de datos desde API**: consulta a una API pública (JSONPlaceholder) para poblar automáticamente un archivo Excel — demuestra el patrón de integración API → Excel aplicable a cualquier sistema con API disponible.

## Power Apps — App de recepción de paquetes

Aplicación low-code para captura estructurada de información en bodega:
- **Recepción**: número de bodega, orden de compra y número de parte.
- **Inspección**: peso, dimensiones, observaciones y adjunto de fotos.
- **Notificación**: confirmación automática de recepción.
- Conectada a una lista de SharePoint, con funcionalidad offline temporal y validación de campos obligatorios.

## Power BI

Diseño de dashboards conectados directamente a SharePoint y Excel, con actualización automática, para visualizar indicadores de ventas, tiempos de entrega y eficiencia operativa.

## Evidencia visual

Ver la carpeta `capturas/` para pantallazos de los flujos configurados en Power Automate, la lógica de extracción vía API, y la estructura de datos de prueba usada para validar cada flujo.

## Stack técnico

`Power Automate` (Web y Desktop) · `Power Apps` · `Power BI` · `SharePoint` · `Microsoft Forms` · Integración con APIs REST

## Habilidades aplicadas

Automatización de procesos (RPA/low-code) · Diseño de flujos de aprobación y notificación · Integración de sistemas vía API · Diseño de aplicaciones low-code · Arquitectura de soluciones en Microsoft 365

