---
Fecha de creación: 2026-04-30 16:09
Fecha de Modificación: 2026-04-30 16:09
tags:
  - Redundancia
  - Almacenamiento
Tema: Infraestructura en la nube
---


## 📚 Idea/Concepto 

Los datos se guardan mediante replicación síncrona (se copian al mismo tiempo) dentro del mismo centro de datos, distribuidos en diferentes racks con sistemas de energía y red independientes (PDUs y switches) para que la distribución sea realmente redundante. El software de almacenamiento descompone los datos en chunks para distribuirlos entre diferentes dominios de falla, garantizando la durabilidad ante fallos de nodos o discos. Si una máquina falla, otra copia está disponible sin perder nada. Esto solo protege contra fallos de hardware individual, no contra desastres que destruyan todo el centro de datos (como incendios o inundaciones).
## 📌 Puntos Claves (Opcional)
- 

## 🔗 Connections
- [[Redundante en zona en el cloud]]
- [[Redundante geo-redundante en el cloud]]
- [[Cloud Público]]

## 💡 Personal Insight (Opcional)
- 
## 🧾 Recursos (Opcional)
- 