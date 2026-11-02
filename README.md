# Atelier · Gestión Premium

Aplicación piloto de gestión de sastrería basada en HTML, CSS y JavaScript, sin dependencias.

## Abrir

Versión privada publicada: https://atelier-gestion-premium-giovanny.paperyheron.chatgpt.site

Para ejecutar localmente: `python -m http.server 8000` y abrir http://localhost:8000.

## Módulos

Clientes, solicitudes y cotizaciones, asignación mixta de profesionales, comisiones configurables (20, 18, 16 y 15 %), recogidas y entregas, pasaporte digital, bitácora de conversaciones, pagos externos, membresías y garantías.

## Alcance

Los registros se guardan en localStorage del navegador. Exportar respaldos desde Configuración. No contiene datos de clientes en el repositorio. No dispone de autenticación por roles, base de datos compartida, mensajería multiusuario ni pasarela de pagos. Las membresías y los pagos son registros administrativos; no generan cobros. No usar como plataforma comercial multiusuario sin implementar esos servicios.

## Archivos

- index.html: estructura.
- style.css: diseño responsive.
- app.js: lógica, formularios y persistencia local.

Comprobación realizada: `node --check app.js`. Revisión funcional completa pendiente.
