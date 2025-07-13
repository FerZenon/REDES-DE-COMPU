# Investigación: Cableado Estructurado

---

## Tabla de Contenido

- [1. ¿Qué es el Cableado Estructurado?](#1-qué-es-el-cableado-estructurado)
- [2. Normativas Internacionales](#2-normativas-internacionales)
- [3. Subsistemas del Cableado Estructurado](#3-subsistemas-del-cableado-estructurado)
- [4. Tipos de Cables y Categorías](#4-tipos-de-cables-y-categorías)
- [5. Tabla de Subsistemas (Mermaid)](#5-tabla-de-subsistemas-mermaid)
- [6. Conclusión](#6-conclusión)

---

## 1. ¿Qué es el Cableado Estructurado?

El **cableado estructurado** es un sistema de cableado estandarizado diseñado para transportar datos, voz y video dentro de un entorno físico como edificios u oficinas. Su objetivo es ofrecer una infraestructura organizada, escalable y flexible, que permita realizar cambios y mantenimientos fácilmente.

Este sistema se instala siguiendo una arquitectura modular basada en normas internacionales, lo que permite la interoperabilidad entre distintos equipos y tecnologías.

---

## 2. Normativas Internacionales

Existen varias normas técnicas que rigen el diseño, instalación y mantenimiento del cableado estructurado:

| Norma            | Descripción                                     |
|------------------|-------------------------------------------------|
| **TIA/EIA-568**  | Define estándares para diseño e instalación     |
| **ISO/IEC 11801**| Norma internacional de cableado genérico        |
| **ANSI/TIA-606** | Identificación y documentación del sistema      |

Estas normas aseguran calidad, compatibilidad y rendimiento en el tiempo.

---

## 3. Subsistemas del Cableado Estructurado

El cableado estructurado se divide en seis subsistemas principales:

| Subsistema                | Función                                                  |
|---------------------------|-----------------------------------------------------------|
| **Área de trabajo**       | Conexión del usuario con la red                           |
| **Cableado horizontal**   | Enlace entre área de trabajo y el cuarto de telecomunicaciones |
| **Backbone o vertical**   | Interconexión entre pisos, cuartos o edificios            |
| **Cuarto de telecomunicaciones** | Punto de consolidación y distribución de redes         |
| **Cuarto de equipos**     | Donde se alojan servidores y switches centrales           |
| **Cuarto de entrada**     | Conexión de servicios externos al edificio                |

---

## 4. Tipos de Cables y Categorías

### 4.1 Par Trenzado (TP)

- **UTP**: Par trenzado sin blindaje  
- **STP**: Par trenzado con blindaje  
- **Categorías comunes**:
  - **Cat 5e**: Hasta 1 Gbps
  - **Cat 6**: Hasta 10 Gbps (corto alcance)
  - **Cat 6a / Cat 7**: Mejor rendimiento y protección contra interferencias

### 4.2 Fibra Óptica

- **Monomodo**: Larga distancia, un solo haz de luz  
- **Multimodo**: Cortas distancias, múltiples trayectorias de luz

### 4.3 Coaxial

- Usado anteriormente en redes locales, hoy más común en TV por cable

---

## 5. Tabla de Subsistemas (Mermaid)

```mermaid
graph TD
    A[Cableado Estructurado] --> B[Área de Trabajo]
    A --> C[Cableado Horizontal]
    A --> D[Backbone (Cableado Vertical)]
    A --> E[Cuarto de Telecomunicaciones]
    A --> F[Cuarto de Entrada]
    A --> G[Cuarto de Equipos]
