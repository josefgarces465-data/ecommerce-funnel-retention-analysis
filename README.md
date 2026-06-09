# MercadoLibre Funnel & Retention Analysis

## 📌 Overview

Este proyecto analiza el comportamiento de los usuarios dentro del embudo de conversión de MercadoLibre y evalúa los niveles de retención mediante análisis de cohortes.

El objetivo fue identificar los principales puntos de abandono durante el proceso de compra y comprender cómo evoluciona la retención de usuarios a lo largo del tiempo para detectar oportunidades de mejora en la experiencia del cliente.

---

## 🎯 Objetivos del Negocio

- Medir la conversión en cada etapa del funnel de compra.
- Identificar los puntos de mayor abandono.
- Comparar el desempeño entre países.
- Analizar la retención de usuarios por cohortes.
- Generar recomendaciones basadas en datos para incrementar la conversión y la fidelización.

---

## 🛠️ Herramientas Utilizadas

- SQL
- PostgreSQL
- Excel
- Funnel Analysis
- Cohort Analysis
- KPI Reporting
- Data Analytics

---

## 📂 Estructura del Proyecto

```text
sql/
├── funnel_analysis.sql
└── retention_analysis.sql

reports/
└── resumen_ejecutivo.xlsx
```

---

## 📊 Metodología

### Funnel Analysis

Se construyó un embudo utilizando las siguientes etapas:

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

Posteriormente se calcularon las tasas de conversión de cada etapa respecto al total de usuarios que realizaron una primera visita.

### Cohort Retention Analysis

Se agruparon los usuarios según su mes de registro para analizar la retención en:

- Día 7 (D7)
- Día 14 (D14)
- Día 21 (D21)
- Día 28 (D28)

---

# 📈 Resultados del Funnel

| Etapa | Conversión |
|---------|---------:|
| Select Item | 76.90% |
| Add to Cart | 11.01% |
| Begin Checkout | 4.00% |
| Add Shipping Info | 2.42% |
| Add Payment Info | 2.09% |
| Purchase | 1.25% |

### Hallazgo Principal

Aunque el 76.9% de los usuarios visualiza productos, únicamente el 11.0% agrega artículos al carrito.

Esto indica que el mayor punto de abandono ocurre entre:

**Select Item → Add to Cart**

La evidencia sugiere una posible fricción relacionada con:

- Precio del producto.
- Costos de envío.
- Comparación con otras opciones.
- Falta de intención inmediata de compra.

---

# 🌎 Análisis por País

Se observaron diferencias significativas en las tasas de conversión entre mercados.

### Países con mejor conversión a compra

- Uruguay
- Bolivia
- México

Estos países mostraron una mayor capacidad para convertir usuarios hasta la etapa final del funnel.

### Oportunidades de mejora

- Colombia
- Ecuador
- Paraguay

Los usuarios muestran interés inicial pero presentan mayores tasas de abandono durante el proceso de checkout.

---

# 🔄 Resultados de Retención

### Retención promedio observada

| Periodo | Retención |
|----------|---------:|
| D7 | 85% - 88% |
| D14 | 53% - 57% |
| D21 | 19% - 27% |
| D28 | 1% - 3% |

### Hallazgo Principal

La retención permanece sólida durante la primera semana, pero disminuye progresivamente después del día 14.

La caída más pronunciada ocurre entre:

**D14 → D28**

Esto sugiere que muchos usuarios realizan interacciones iniciales, pero no desarrollan hábitos de uso recurrente en el largo plazo.

---

# 👥 Análisis de Cohortes

Las cohortes con mejor desempeño fueron:

- Marzo 2025
- Mayo 2025

Estas cohortes alcanzaron los niveles más altos de retención en D21, superando el promedio general.

Esto podría indicar la efectividad de campañas comerciales, promociones o mejoras en la experiencia del usuario implementadas durante esos períodos.

---

# 💡 Recomendaciones

### Funnel de Conversión

- Optimizar las páginas de producto.
- Mejorar la transparencia de costos de envío.
- Incorporar incentivos para completar la compra.
- Reducir fricciones durante el checkout.

### Retención

- Implementar campañas de reactivación.
- Diseñar estrategias de fidelización.
- Personalizar comunicaciones según comportamiento.
- Incentivar compras recurrentes durante los primeros 14 días.

---

# 📚 Habilidades Demostradas

- SQL avanzado
- Common Table Expressions (CTEs)
- Funnel Analysis
- Cohort Analysis
- Retention Metrics
- KPI Development
- Business Analytics
- Data Storytelling
- Insight Generation

---

## 👨‍💻 Autor

**Jose Fernando Garcés Saavedra**

Data Analyst | Business Intelligence Analyst
