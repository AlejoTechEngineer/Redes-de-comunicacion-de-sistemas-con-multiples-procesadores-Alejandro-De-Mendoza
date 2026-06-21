<div align="center">

# Redes de Comunicación de Sistemas con Múltiples Procesadores

![Architecture](https://img.shields.io/badge/Arquitectura-Paralela-FF6B35?style=for-the-badge)
![Networking](https://img.shields.io/badge/Interconexión-Procesadores-2E86AB?style=for-the-badge)

> Análisis de redes de comunicación en arquitecturas de cómputo paralelo con múltiples procesadores.

## Descripción

</div>

---

Estudio de las topologías de interconexión empleadas en sistemas de procesamiento paralelo: redes estáticas (malla, hipercubo, árbol) y dinámicas (crossbar, omega), protocolos de comunicación entre procesadores, latencia, ancho de banda y métricas de rendimiento en arquitecturas HPC.

## Contenido

| Archivo | Descripción |
|---|---|
| `*.pdf` | Informe técnico del análisis de redes de interconexión |
| `*.docx` | Desarrollo completo del trabajo académico |

## Temas cubiertos

- Topologías de interconexión: bus, malla 2D/3D, hipercubo, árbol fat
- Protocolos de paso de mensajes: latencia, ancho de banda, bisección BW
- Comparativa de rendimiento según topología y número de procesadores
- Aplicaciones en sistemas HPC y arquitecturas NUMA/NORMA

## Contexto académico

**Asignatura:** Redes de Computadores · **Institución:** Ingeniería Informática
**Autor:** Alejandro De Mendoza — Ingeniero Informático · Máster Arquitectura de Software

---

## Arquitectura

```mermaid
flowchart TD
    A[Sistema con Multiples Procesadores] --> B[Redes Estaticas]
    A --> C[Redes Dinamicas]
    B --> D[Malla 2D/3D]
    B --> E[Hipercubo]
    B --> F[Arbol Fat]
    C --> G[Crossbar Switch]
    C --> H[Red Omega]
    D & E & F & G & H --> I[Metricas de Rendimiento - Latencia / Ancho de banda / Biseccion BW]
    I --> J[Comparativa por Topologia y numero de procesadores]
    J --> K[Aplicaciones HPC - NUMA / NORMA]
```

## Autor

**Alejandro De Mendoza**  
Ingeniero Informático · Especialista en IA · Especialista en Ingeniería de Software · Máster en Arquitectura de Software

[![GitHub](https://img.shields.io/badge/GitHub-AlejoTechEngineer-181717?style=for-the-badge&logo=github)](https://github.com/AlejoTechEngineer)
