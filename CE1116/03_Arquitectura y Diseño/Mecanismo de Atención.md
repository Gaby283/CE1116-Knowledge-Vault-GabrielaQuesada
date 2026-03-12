---
Fecha de creación: 2026-03-11 20:59
Fecha de Modificación: 2026-03-11 20:59
tags:
  - palabras
  - contexto
  - query
  - key
  - value
  - softmax
  - multi-cabezal
Tema:
---

## 📚 Idea/Concepto 

Es un proceso donde las palabras o partes de la oración intercambian información entre sí según el contexto. Esto se puede describir como un mapeo entre un Query (Q) y un conjunto de pares Key-Value (K, V), donde el resultado es una suma ponderada de valores.
La compatibilidad entre Q y K se calcula mediante un producto punto, y los pesos se normalizan utilizando softmax para obtener la suma ponderada. Además, Q, K y V se obtienen al multiplicar los embeddings por matrices de pesos aprendibles ($W_Q, W_K, W_V$). Este proceso también puede ocurrir en paralelo mediante atención multi-cabezal, lo que permite capturar diferentes tipos de relaciones al mismo tiempo.
## 📌 Puntos Claves (Opcional)
- 

## 🔗 Connections
- [[Arquitectura Transformer]]
- [[Embeddings]]
- [[Ventana de Contexto]]

## 💡 Personal Insight (Opcional)
- 
## 🧾 Recursos (Opcional)
- 