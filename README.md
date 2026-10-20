# MSGF — Modelos del Proceso Unificado de Ingeniería de Software

Este repositorio reúne **modelos UML elaborados con [draw.io (diagrams.net)](https://app.diagrams.net/)** como resultado de aplicar, con fines académicos, el **Proceso Unificado de Ingeniería de Software** al caso de estudio hipotético de la **Fundación MSG (MSG Foundation)**, presentado por Stephen R. Schach en su texto guía.

El propósito es **documentar la evolución de los modelos entre iteraciones** y servir como material de estudio y práctica para comprender cómo los nuevos requerimientos obligan a revisar, ampliar y ajustar los artefactos de ingeniería de software.

## Contexto del caso de estudio

La Fundación MSG es una organización ficticia orientada a facilitar el acceso a vivienda mediante créditos hipotecarios. El caso permite estudiar la elicitación y el refinamiento de requerimientos, así como la construcción progresiva de modelos orientados a objetos.

Los diagramas de este repositorio son **artefactos académicos de modelado**; no constituyen una implementación de software ni deben interpretarse como los modelos originales publicados por la editorial.

## Organización del repositorio

```text
MSGF/
├── .gitignore
├── README.md
├── Iteration1/
│   ├── 1. MSG-F General Use Case.drawio
│   ├── 2. MSG-F Entity Classes.drawio
│   ├── 3. MSG-F MachineStateChart.drawio
│   └── 4. MSG-F Boundary and Control Classes.drawio
└── Iteration2-becaCrédito/
    ├── 1. MSG-F General Use Case.drawio
    ├── 2. MSG-F Entity Classes.drawio
    ├── 3. MSG-F MachineStateChart.drawio
    └── 4. MSG-F Boundary and Control Classes.drawio
```

### `Iteration1` — Requerimientos iniciales y primera aproximación al análisis

Contiene modelos obtenidos tras **varias iteraciones de elicitación de requerimientos** y **una iteración de análisis orientado a objetos**, que comprendió:

- **Modelado de requerimientos:** elaboración y refinamiento de casos de uso.
- **Modelado funcional:** descripción de escenarios asociados a los casos de uso.
- **Descubrimiento de clases:** identificación de clases entidad; también se conservan diagramas de clases límite y control.
- **Modelado dinámico:** representación del comportamiento mediante **diagramas de máquinas de estado**. En esta etapa no se incluyen otros tipos de diagramas dinámicos.

**Archivos:**

| Modelo | Archivo |
| --- | --- |
| Casos de uso generales | [1. MSG-F General Use Case.drawio](Iteration1/1.%20MSG-F%20General%20Use%20Case.drawio) |
| Clases entidad | [2. MSG-F Entity Classes.drawio](Iteration1/2.%20MSG-F%20Entity%20Classes.drawio) |
| Máquinas de estado | [3. MSG-F MachineStateChart.drawio](Iteration1/3.%20MSG-F%20MachineStateChart.drawio) |
| Clases límite y control | [4. MSG-F Boundary and Control Classes.drawio](Iteration1/4.%20MSG-F%20Boundary%20and%20Control%20Classes.drawio) |

### `Iteration2-becaCrédito` — Incorporación de becas-crédito

Presenta la **revisión y modificación de los modelos de la primera iteración** a partir de un **requerimiento adicional**: la Fundación comienza a otorgar **becas-crédito**.

Esta etapa busca evidenciar cómo un cambio en el alcance del sistema repercute en los casos de uso, las clases y el comportamiento modelado.

| Modelo actualizado | Archivo |
| --- | --- |
| Casos de uso generales | [1. MSG-F General Use Case.drawio](iteration2-becaCrédito/1.%20MSG-F%20General%20Use%20Case.drawio) |
| Clases entidad | [2. MSG-F Entity Classes.drawio](iteration2-becaCrédito/2.%20MSG-F%20Entity%20Classes.drawio) |
| Máquinas de estado | [3. MSG-F MachineStateChart.drawio](iteration2-becaCrédito/3.%20MSG-F%20MachineStateChart.drawio) |
| Clases límite y control | [4. MSG-F Boundary and Control Classes.drawio](iteration2-becaCrédito/4.%20MSG-F%20Boundary%20and%20Control%20Classes.drawio) |

### Próximas iteraciones y ejercicios

Se prevé incorporar **otras carpetas de práctica**, cada una dedicada a nuevos requerimientos o ejercicios que permitan desarrollar la habilidad de **iterar sobre modelos existentes**, reconocer el impacto de los cambios y mantener la consistencia entre artefactos.

## Cómo consultar los modelos

1. Abre [diagrams.net](https://app.diagrams.net/) o la aplicación de escritorio de draw.io.
2. Descarga o clona el repositorio.
3. Abre el archivo `.drawio` que quieras estudiar o modificar.
4. Compara los diagramas homólogos de `Iteration1` y `Iteration2-becaCrédito` para identificar las modificaciones introducidas por el requerimiento de becas-crédito.

Para clonar el repositorio:

```bash
git clone https://github.com/is-i/MSGF.git
```

Los archivos originales `.drawio` se mantienen editables. El archivo `.gitignore` excluye archivos temporales y de bloqueo generados durante su edición.

## Enfoque pedagógico

Este repositorio privilegia el **carácter iterativo e incremental del modelado**: los artefactos no se consideran definitivos, sino susceptibles de ampliación, corrección y reorganización cuando se comprende mejor el dominio o aparecen nuevos requerimientos.

El material documenta las actividades y los diagramas efectivamente trabajados; **no representa todas las disciplinas, actividades ni artefactos posibles del Proceso Unificado**.

## Referencia bibliográfica

Schach, S. R. (2012). *Classical and Object Oriented Software Engineering* (8.ª ed.). McGraw-Hill.

> **Nota:** La Fundación MSG es un caso de estudio ficticio tomado como referencia didáctica. Los modelos alojados aquí son desarrollos académicos basados en ese caso.
