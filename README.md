# Análisis de Embudo de Conversión y Retención de Usuarios

## Descripción

En este proyecto trabajé con información de comportamiento de usuarios en una plataforma de comercio electrónico para analizar dos aspectos clave:

- El recorrido de los usuarios dentro del proceso de compra.
- La retención de usuarios después de su registro.

El análisis fue realizado utilizando SQL y tuvo como objetivo identificar oportunidades de mejora tanto en la conversión como en la fidelización de clientes.

---

## Herramientas utilizadas

- SQL
- PostgreSQL
- Excel
- Análisis de Cohortes
- Análisis de Funnel

---

## Objetivos del análisis

### Embudo de conversión

Analizar cómo avanzan los usuarios a través de las diferentes etapas del proceso de compra:

```text
First Visit
↓
Select Item
↓
Add to Cart
↓
Begin Checkout
↓
Add Shipping Info
↓
Add Payment Info
↓
Purchase
```

### Retención

Evaluar qué porcentaje de usuarios continúa activo después de su registro en distintos momentos del tiempo (D7, D14, D21 y D28).

---

## Proceso realizado

### Análisis del Funnel

Se construyeron consultas SQL utilizando CTEs para calcular la cantidad de usuarios que alcanzaban cada etapa del embudo y posteriormente se calcularon las tasas de conversión por país.

### Análisis de Retención

Se realizó un análisis por cohortes agrupando a los usuarios según su mes de registro para medir la permanencia y actividad a lo largo del tiempo.

---

## Principales hallazgos

### Funnel de conversión

- La mayor parte de los usuarios que visitan la plataforma llegan a visualizar productos.
- El mayor abandono ocurre entre la visualización de productos y la adición al carrito.
- La conversión disminuye considerablemente a medida que los usuarios avanzan hacia el checkout y el pago.
- Existen diferencias importantes en el desempeño del funnel entre países.

### Retención

- La actividad de los usuarios se mantiene relativamente estable durante los primeros días después del registro.
- A partir de la segunda semana se observa una disminución progresiva de la retención.
- Algunas cohortes presentan un mejor comportamiento que otras, lo que podría estar relacionado con campañas o cambios en la experiencia de usuario.

---

## Conclusiones

A partir del análisis se identificó que las principales oportunidades de mejora se encuentran en dos frentes:

1. Incrementar la cantidad de usuarios que agregan productos al carrito mediante mejoras en la experiencia de compra.
2. Implementar estrategias de retención durante las primeras semanas de uso para reducir la pérdida de usuarios recurrentes.

Este ejercicio me permitió aplicar conceptos de análisis de embudos, cohortes, métricas de conversión y retención utilizando SQL para responder preguntas de negocio a partir de datos.

---

## Archivos del proyecto

```text
sql/
├── funnel_analysis.sql
└── retention_analysis.sql

reports/
└── resumen_ejecutivo.xlsx
```

---

## Autor

**Jose Fernando Garcés Saavedra**


## Lo que aprendí

Durante este proyecto reforcé el uso de CTEs para estructurar consultas complejas y comprendí cómo los análisis de funnel y cohortes pueden ayudar a identificar oportunidades de mejora en la experiencia de usuario y en la conversión de una plataforma digital.

Analista de Datos | Business Intelligence

GitHub: https://github.com/josefgarces465-data
