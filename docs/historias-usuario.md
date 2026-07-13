# Historias de Usuario — MONITIA

## HU-01
**Como** técnico de mantenimiento,
**quiero** que me llegue una alerta cuando algo ande mal,
**para** poder actuar antes de que la máquina falle de plano.

**Criterios de aceptación:**
- Si el puntaje de anomalía pasa el umbral, la alerta llega en menos de 5 min
- La alerta dice qué máquina es, qué pieza y qué tan grave está
- Puedo marcar la alerta como atendida

## HU-02
**Como** operador de planta,
**quiero** ver el estado de cada máquina en un dashboard,
**para** saber cómo va la línea sin tener que preguntar a nadie.

**Criterios de aceptación:**
- El dashboard usa un semáforo (verde/amarillo/rojo) por máquina
- Los datos se van actualizando solos
- Puedo filtrar por línea de producción

## HU-03
**Como** gerente de mantenimiento,
**quiero** consultar el historial de fallas y predicciones,
**para** decidir en dónde invertir primero.

**Criterios de aceptación:**
- El reporte muestra cuántas anomalías hubo por máquina y por periodo
- Se puede exportar en PDF o Excel
- Muestra cuánto se ahorró por adelantarse a la falla
