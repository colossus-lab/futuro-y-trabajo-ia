# 🇦🇷 Argentina & IA Generativa — Estado de Situación: Futuro del Trabajo

> **Análisis de preparación y exposición del mercado laboral argentino frente a la IA Generativa, basado en el framework de Anthropic (2026).**

---

## 📖 ¿Qué es este proyecto?

Este sitio web interactivo presenta un cruce analítico entre dos fuentes:

1. **El informe de Anthropic (2026)**: *"Labor market impacts of AI: A new measure and early evidence"* — marco metodológico que introduce el concepto de **Exposición Observada** (lo que realmente se automatiza vs. lo que teóricamente podría automatizarse).
2. **Datos estructurales argentinos** provenientes de INDEC, ILIA (CEPAL/CENIA), CIPPEC, OCDE, y el Ministerio de Trabajo — estadísticas sobre empleo formal e informal, demografía laboral, juventud, y políticas de reconversión.

El resultado es un **diagnóstico interactivo** que permite visualizar cómo impactaría la IA generativa específicamente en el mercado de trabajo argentino.

---

## 🧭 Guía de Navegación

El sitio se organiza en **8 pestañas** accesibles desde la barra de navegación superior:

### 1. 🏠 Inicio
Panorama general con las 4 cifras clave del informe:
- **54%** del empleo formal expuesto a la IA
- **676K** puestos en riesgo de sustitución directa
- **42%** de informalidad laboral total
- **2.1M** puestos en zona de complementariedad ("copiloto")

Incluye una **Síntesis Evaluativa** con los 4 hallazgos principales.

### 2. 📊 Exposición
Explica el concepto de **Exposición Observada** de Anthropic y su aplicación a la realidad argentina. Incluye:
- Gráfico de **brecha de adopción** (benchmarks vs. uso global vs. realidad local)
- Panel interactivo de **vulnerabilidad demográfica** (filtrable por perfil general, nivel educativo y género)
- Métricas de **sustitución vs. complementariedad** (directa: 676K / parcial: 129K / copiloto: 2.1M)

### 3. 🏭 Sectores
Análisis de vulnerabilidad por sector económico. Toggle interactivo entre:
- **Peso en el empleo** — participación de cada sector
- **Riesgo IA** — nivel de exposición a la automatización

Destaca el caso de Servicios Profesionales (contadores, abogados, programadores junior) y la calificación ocupacional según INDEC.

### 4. ⚠️ Informalidad
Sección dedicada al **42% del empleo informal** como falso amortiguador. Datos clave:
- 36.1% de asalariados sin descuentos jubilatorios
- 62.4% de cuentapropistas no registrados
- ~80% de informalidad en construcción y trabajo doméstico

### 5. 👩‍🎓 Juventud
La **"Escalera Rota" del Primer Empleo**: la IA automatiza exactamente las tareas de los roles entry-level. Métricas:
- -14% en contratación de 22-25 años
- 16.9% de desempleo en mujeres jóvenes (14-29)
- 50% de jóvenes perciben su formación como inadecuada

### 6. 🌍 Rankings
Posición de Argentina en el contexto internacional:
- **ILIA 2024-2025**: Argentina cayó al 6° lugar en LATAM (52.98/100 pts)
- Caída en Talento Humano y en I+D+A (-10 pts)
- 76% de CEOs ya implementa o planea usar IA

### 7. 🔮 Escenarios
**10 consecuencias proyectadas de la inacción** y **10 medidas preventivas** organizadas por urgencia:
- 🟢 Urgentes (0-12 meses)
- 🟡 Estratégicas (12-36 meses)
- 🔵 Estructurales (36-60 meses)

### 8. 🏛️ Políticas
Programas de reconversión laboral existentes (Argentina Programa 4.0, Talento Tech, Santa Fe 4.0, Mendoza Forma Tec) y la **Paradoja Pedagógica**: muchos programas enseñan habilidades que la IA ya automatiza.

---

## 📄 Informe PDF

El sitio incluye un botón de descarga directa del informe completo en PDF:
**"Argentina: IA, Empleo y Transición Tecnológica"** (~1.7 MB, circulación libre).

---

## 🛠️ Stack Técnico

| Componente | Tecnología |
|---|---|
| Estructura | HTML5 semántico (single-page) |
| Estilos | TailwindCSS (CDN) + CSS custom |
| Visualizaciones | Chart.js (bar, radar, doughnut) |
| Tipografía | Google Fonts (Inter) |
| Interactividad | Vanilla JavaScript |
| Deploy | Archivo estático (sin build) |

---

## 🚀 Cómo usar

```bash
# Clonar el repositorio
git clone https://github.com/dantedeagostino-dot/futuro-y-trabajo-ia.git

# Abrir directamente en el navegador
start index.html    # Windows
open index.html     # macOS
xdg-open index.html # Linux
```

No requiere instalación, servidor ni dependencias. Es un archivo HTML autocontenido.

---

## 📁 Estructura del Proyecto

```
futuro-y-trabajo-ia/
├── index.html                                    # Aplicación web completa
├── Argentina_ IA, Empleo y Transición Tecnológica.pdf  # Informe descargable
├── informe_escenarios_y_medidas.md               # Documento fuente: escenarios y medidas
├── web.txt                                       # Versión draft inicial del sitio
├── .gitignore
└── README.md
```

---

## 📚 Fuentes Principales

- **Anthropic (2026)** — *"Labor market impacts of AI: A new measure and early evidence"*
- **INDEC** — Encuesta Permanente de Hogares, 2T/4T-2024/2025
- **ILIA (CEPAL/CENIA)** — Índice Latinoamericano de Inteligencia Artificial 2024-2025
- **CIPPEC** — Análisis de distribución del excedente de IA
- **OCDE** — Presión deflacionaria en mercados laborales (2025)
- **Oxford AI Readiness Index** — Ranking global de preparación en IA
- **Ministerio de Trabajo (Argentina)** — Clasificación de exposición laboral (2023)

---

## ✍️ Autoría

Desarrollado por **Laboratorio Colossus** · Investigación de Impacto Laboral 2026

Documento técnico de **circulación libre**.

---

## 📝 Licencia

Este proyecto es de circulación libre con fines educativos e informativos. Se permite su distribución citando las fuentes originales.
