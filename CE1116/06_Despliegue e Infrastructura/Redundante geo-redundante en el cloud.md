---
Fecha de creación: 2026-04-30 16:09
Fecha de Modificación: 2026-04-30 16:09
tags:
  - Redundancia
  - Geo-redundancia
Tema: Infraestructura en la nube
---


## 📚 Idea/Concepto 
Es similar a la redundancia de zona, pero en este caso las copias se guardan mediante replicación entre regiones geográficas (por ejemplo, en distintos continentes). Por la gran distancia, se usa replicación asíncrona, lo que significa que hay un pequeño retraso entre la copia original y la copia remota. Este retraso se cuantifica técnicamente mediante RPO (Recovery Point Objective) y RTO (Recovery Time Objective), que definen cuántos datos se pueden perder y cuánto tiempo toma recuperarse en un failover regional. Esto protege contra desastres regionales completos, aunque no es instantáneo como la replicación síncrona. Replicar datos entre continentes impacta la soberanía de datos y el cumplimiento normativo (como GDPR), por lo que no siempre es legal o recomendable dependiendo de la ubicación de los usuarios y las leyes locales.

## 📌 Puntos Claves (Opcional)
- 

## 🔗 Connections
- [[Redundante localmente en el cloud]]
- [[Redundante en zona en el cloud]]
- [[Cloud Híbrido (Hybrid cloud)]]
- [[Cloud Público]]

## 💡 Personal Insight (Opcional)
- 
## 🧾 Recursos (Opcional)
- 