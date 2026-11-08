# Grupo_Osterc_Echecoena_Sansolini_ISyD2026

TP Integrador de Ingeniería del Software y Datos 2026 (MIA 203, UdeSA).
Somos Faustino Osterc, Rodrigo Echeconea y Nicolás Sansolini.

## Qué estamos construyendo

Cuando alguien entra a una agencia de viajes online ve un catálogo enorme y, muchas veces, termina mirando solo los destinos que ya conoce. Queremos ayudarlo a descubrir lugares que quizás no habría buscado.

Para eso armamos un sistema que toma datos reales de Despegar.com (una muestra de aproximadamente el 1% de sus clientes, con sus destinos e interacciones), los limpia y los enriquece con un pipeline que se puede volver a ejecutar cuando se quiera, y entrena un modelo de recomendación (ALS). Una API usa ese modelo: le pasás un usuario y te devuelve los destinos que más le pueden interesar. Si el usuario es nuevo o casi no tiene historial, le devuelve los destinos más populares.

## En qué punto estamos

Estamos en la **entrega 2 (7/11/2026)**: el PRD con su Roadmap. Todavía no hay código, así que por ahora este repositorio tiene solo documentación. El sistema se construye entre el 8/11 y el 5/12, que es la fecha de la entrega final.

## Qué hay en el repo

- `docs/`: el PRD con el Roadmap (entrega 2).
- La propuesta aprobada (entrega 1) está en la raíz del repositorio.
- Las decisiones de diseño se van a documentar como ADRs a medida que las tomemos. Cada ADR compara alternativas y explica por qué elegimos una.
- Más adelante se suman el SRD (diseño del sistema), el código del pipeline, del modelo y de la API, y la configuración de CI.

## Cómo ejecutarlo

Todavía no hay nada para ejecutar. Uno de nuestros objetivos es que todo se levante con un solo comando en una máquina limpia, y cuando eso esté listo lo vamos a explicar acá, paso a paso.

## Cómo nos organizamos

| Quién | Se encarga principalmente de |
|---|---|
| Rodrigo | Repo, entorno y CI; API y persistencia |
| Faustino | Pipeline de datos; modelo ALS y evaluación |
| Nicolás | PRD, ADRs, SRD, README y video |

Cada frente tiene además a otra persona de apoyo. Las fechas de cada tramo están en el roadmap del PRD.

## Sobre los datos

Los datos están anonimizados y **no se suben a este repositorio**. Cuando tengamos lista la ingesta, vamos a documentar acá cómo conseguirlos y cargarlos.
