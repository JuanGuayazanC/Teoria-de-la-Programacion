# Teoría de la Programación (TPRO)

Repositorio general del curso Teoría de la Programación, que agrupa —mediante submódulos de git— los proyectos y recursos del curso.

Cada submódulo es un repositorio independiente con su propio historial de commits y README. Para saber cómo aprovechar este repositorio, ver [Cómo usar este repositorio](#cómo-usar-este-repositorio).

## Estructura del proyecto

```
Teoria-de-la-Programacion/
├── Proyectos/
│   └── Minimizacion-costos-replicacion-TPRO/
└── Recursos/
    └── Dividir-y-Conquistar--Programacion-dinamica-TPRO/
```

## Temas del curso

El curso recorre el diseño y análisis formal de algoritmos, desde la especificación hasta técnicas avanzadas de resolución de problemas:

- **Especificación de programas**: lenguaje de comandos guardados (Guarded Command Language), precondiciones y postcondiciones.
- **Corrección de ciclos**: invariantes y funciones de cota (variantes) para demostrar la corrección de programas iterativos.
- **Inducción y recurrencia**: análisis de complejidad mediante relaciones de recurrencia e inducción matemática.
- **Dividir y conquistar**: diseño de algoritmos que dividen un problema en subproblemas independientes.
- **Programación dinámica**: memoización y tabulación para resolver problemas con subestructura óptima (cambio de monedas, subsecuencia común máxima, distribución óptima de recursos, replicación óptima de archivos en servidores).
- **Alineación de secuencias**: aplicación de programación dinámica a la comparación de secuencias.

## Cosas a tener en cuenta

- `Dividir-y-Conquistar--Programacion-dinamica-TPRO` es material compartido entre el profesor (Raúl Alfredo Chaparro Aguilar) y los estudiantes del curso, no una entrega individual.
- `Minimizacion-costos-replicacion-TPRO` es la solución a un problema de programación dinámica: minimizar el costo total de colocación y acceso al replicar un archivo en una red de servidores.

## Herramientas

- Python
- Haskell (GHCi)

## Profesor

Raúl Alfredo Chaparro Aguilar.

## Cómo usar este repositorio

Este repositorio no contiene código directamente: es una colección de repositorios independientes (proyectos y recursos), organizados por carpetas. Cada carpeta es un submódulo de git que apunta al repositorio real de esa actividad.

- **Para consultar una actividad puntual**: entra directamente a su carpeta en GitHub (o navega el submódulo) y revisa su propio README.
- **Para tener todo el contenido en tu máquina**:

```bash
git clone --recurse-submodules https://github.com/JuanGuayazanC/Teoria-de-la-Programacion.git
```

Si ya clonaste el repositorio sin submódulos:

```bash
git submodule update --init --recursive
```
