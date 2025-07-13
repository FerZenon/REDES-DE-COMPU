
# Investigación: IEEE 802

---

## Tabla de Contenido

- [1. ¿Qué es IEEE 802?](#1-qué-es-ieee-802)
- [2. Familia de Estándares IEEE 802](#2-familia-de-estándares-ieee-802)
- [3. Tabla de Estándares (Mermaid)](#3-tabla-de-estándares-mermaid)
- [4. Conclusión](#4-conclusión)

---

## 1. ¿Qué es IEEE 802?

IEEE 802 es una colección de estándares creados por el IEEE (Institute of Electrical and Electronics Engineers) para definir las tecnologías utilizadas en redes de área local (LAN) y redes metropolitanas (MAN).

Estos estándares operan principalmente en las dos capas más bajas del modelo OSI: la capa física y la de enlace de datos, facilitando la interoperabilidad entre distintos fabricantes de equipos de red.

---

## 2. Familia de Estándares IEEE 802

Cada número dentro de la serie IEEE 802 representa un subgrupo especializado. Algunos de los estándares más relevantes son:

| Estándar | Nombre             | Función Principal                  |
|----------|--------------------|-----------------------------------|
| 802.1    | Bridging / Gestión | Control de tráfico y VLAN         |
| 802.2    | LLC                | Subcapa de enlace lógico          |
| 802.3    | Ethernet           | Red cableada CSMA/CD              |
| 802.5    | Token Ring         | Red basada en anillo y token      |
| 802.11   | Wi-Fi              | Redes inalámbricas LAN            |
| 802.15   | WPAN / Bluetooth   | Redes personales inalámbricas     |
| 802.16   | WiMAX              | Acceso inalámbrico de banda ancha |

---

## 3. Tabla de Estándares (Mermaid)

```mermaid
graph TD
    A[IEEE 802] --> B[802.1 - Gestión y VLAN]
    A --> C[802.2 - LLC]
    A --> D[802.3 - Ethernet]
    A --> E[802.5 - Token Ring]
    A --> F[802.11 - Wi-Fi]
    A --> G[802.15 - Bluetooth / WPAN]
    A --> H[802.16 - WiMAX]
