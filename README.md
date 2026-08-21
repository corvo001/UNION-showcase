# UNION

**Experimental environment for creating, transporting, and exploring fractal
structures in real time.**

[Portfolio (ES)](https://corvo01.com/es/proyectos/union/) ·
[Portfolio (EN)](https://corvo01.com/en/work/union/)

![UNION real-time fractal interface](https://corvo01.com/assets/images/union/Imagen-del-proyecto.png)

## Español

UNION es un proyecto de I+D que conecta generación visual, transporte de
definiciones y análisis matemático dentro de un mismo flujo de trabajo. Permite
crear, transformar y estudiar geometrías fractales interactivas sin tratar la
imagen renderizada como la única fuente de verdad.

### Componentes

| Componente | Tecnología | Función |
| --- | --- | --- |
| **FractalCreator** | C++17 + GLSL | Creación y deformación interactiva en GPU. |
| **Nexo** | Rust | Validación y transporte de definiciones y resultados. |
| **FractalExplorer** | Julia | Reproducción, exploración y análisis matemático. |

El proyecto se encuentra en desarrollo activo. Este repositorio es un
**escaparate técnico**: contiene documentación pública y material visual, pero
no contiene el código fuente ni los detalles de implementación del motor. El
núcleo de UNION se mantiene en un repositorio privado.

Consulta [la arquitectura pública](docs/ARCHITECTURE.md) para conocer el flujo
general del sistema.

### Galería

| Exploración | Deformación | Morfología |
| --- | --- | --- |
| ![Exploración fractal](https://corvo01.com/assets/images/union/capture_144410.png) | ![Deformación fractal](https://corvo01.com/assets/images/union/capture_144459.png) | ![Morfología fractal](https://corvo01.com/assets/images/union/capture_144414.png) |

## English

UNION is an R&D project connecting visual generation, definition transport,
and mathematical analysis in a single workflow. It creates, transforms, and
studies interactive fractal geometries without treating the rendered image as
the system's only source of truth.

This is a **technical showcase repository**. It contains public documentation
and visual material, but no engine source code or private implementation
details. UNION's core is maintained in a private repository.

See the [public architecture overview](docs/ARCHITECTURE.md) for the general
system flow.

## Contact

For research, collaboration, or licensing enquiries:
[danielcuervor01@gmail.com](mailto:danielcuervor01@gmail.com).

## Rights

Copyright © 2025-2026 Daniel Cuervo. All rights reserved. See
[`LICENSE`](LICENSE).
