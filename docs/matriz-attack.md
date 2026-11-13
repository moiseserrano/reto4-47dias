# Matriz ATT&CK (borrador, 13 nov 2026)

| Técnica | Evento Windows | Evento Linux | Detección | Evidencia |
|---------|----------------|--------------|-----------|-----------|
| T1136 Crear cuenta | 4720 (cubierto: User Account Management en Success) | useradd en auditd, cambios en /etc/passwd | pendiente | pendiente |
| T1053 Tarea programada | 4698 (hoy NO se registra: Other Object Access Events sin auditoría), Sysmon 1 (schtasks.exe) | cambios en cron vía auditd | pendiente | pendiente |
| T1110 Fuerza bruta | 4625 y 4624 (cubierto: Logon en Success and Failure) | auth.log, journalctl -u ssh | pendiente | pendiente |

Nota: la ejecución de procesos (4688) tampoco se registra hoy porque Process Creation está sin auditoría.




