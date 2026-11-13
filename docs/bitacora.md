# Bitacora - Reto 4 "47 Dias en Silencio" (Silver Suns)

|Fecha y hora | Integrante | Actividad | Resultado / evidencia |
|---|---|---|---|
|2026-11-12 18:24|Moises Serrano| Snapshot "Linea base insegura" en SRV-LNX01 | Creado, captura en evidencias/linux/ |
|2026-11-12 19:10 | Moises Serrano| Evidencia inicial: auditctl, journald, puertos | auditctlsin reglas; journal no persistente |
|2026-11-12 19:40| Moises Serrano| Lynnis inicial | Hardening index: 63 (lynis-inicial.txt) |
   ## 13 nov 2026 - Windows (DC01)
   - Instalé Windows Server 2022 (DC01) en VMware.
   - Lo promoví a controlador de dominio.
   - Tomé el snapshot "Línea base insegura".
   - Guardé evidencias: auditpol, tamaño del log de seguridad, puertos y sistema.
   - Hallazgo: Process Creation y Other Object Access Events sin auditoría.
   - Pendiente: medir la tasa diaria de eventos del log.


