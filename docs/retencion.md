# Cálculo de retención de 47 días

Fórmula: eventos por día x 47 días x tamaño promedio por evento

Datos medidos (13 nov 2026, DC01):
- Tamaño máximo del log de Seguridad: 128 MB, circular
- Tamaño actual: 2.07 MB con 2 099 eventos
- Tamaño promedio por evento: cerca de 1 KB
- Tasa diaria de eventos: pendiente de medir

Ejemplo ilustrativo (no es una medición): con 57 877 eventos por día
serían unos 2,6 GB en 47 días, y el log de 128 MB se llenaría en
unos 2 días.

Conclusión preliminar: el log de 128 MB circular no alcanza para
conservar 47 días. Se medirá la tasa real después de activar la
auditoría avanzada y se dimensionará el tamaño y la exportación de logs.






