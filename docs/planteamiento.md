# Planteamiento del proyecto

## Pregunta esencial
¿Cómo puede un municipio detectar un ataque a tiempo si sus registros
se borran antes de que alguien los revise?

## Idea grande
Un sistema solo se puede defender si deja rastros. Para eso hay que
registrar los eventos importantes, guardarlos el tiempo suficiente y
revisarlos con alertas. Si los registros son pequeños, están apagados o
nadie los mira, un ataque puede pasar sin que nadie se entere.

## Reto
En el caso "47 Días en Silencio", el reto es configurar la auditoría en
Windows y Linux, conservar los registros durante 47 días y detectar
técnicas de ataque concretas (crear cuentas, tareas programadas y
fuerza bruta). Mi diagnóstico inicial encontró que el log de seguridad
es de solo 128 MB y que Process Creation y Other Object Access Events
no están auditados.





