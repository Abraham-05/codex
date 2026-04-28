# Plantilla de Propuesta: Práctica Temática de Proyecto Pequeño

## 1) Título de la actividad

**Diseña tu práctica temática pequeña (documentación primero)**

> Ejemplos de título que puedes usar o adaptar:
>
> - **Mini Toolkit en ARM64**
> - **Asistente de Estudio en Terminal**
> - **Reporteador de Información del Sistema**
> - **Organizador de Archivos**
> - **Juego de Aprendizaje en Línea de Comandos**

---

## 2) Descripción general

En esta actividad vas a **diseñar una propuesta de proyecto pequeño** para terminal, con enfoque en **planeación, documentación y estructura de repositorio**.

Tú debes elegir **un lenguaje principal**:

- ARM64 Assembly
- C
- Python
- Bash

> ⚠️ **Nota importante sobre ARM64 Assembly:** úsalo solo si tu idea es **muy pequeña y acotada** (por ejemplo: operaciones básicas, lectura simple de argumentos o manejo mínimo de entrada/salida).

La prioridad de esta práctica es que **justifiques bien la idea antes de programar mucho**. Si incluyes código, debe ser mínimo y congruente con lo documentado.

---

## 3) Entregables del estudiante

Tu repositorio debe incluir, como mínimo, los siguientes archivos:

- `README.md`
- `docs/propuesta.md`
- `docs/caso_de_uso.md`
- `docs/estructura_repositorio.md`
- `docs/plan_de_pruebas.md`

Carpetas opcionales (recomendadas si agregas prototipo):

- `src/`
- `scripts/`
- `tests/`

---

## 4) Estructura recomendada del repositorio

Usa esta estructura base:

```text
nombre-del-proyecto/
├── README.md
├── docs/
│   ├── propuesta.md
│   ├── caso_de_uso.md
│   ├── estructura_repositorio.md
│   └── plan_de_pruebas.md
├── src/
│   └── main.<ext>
├── scripts/
│   └── run.sh
└── tests/
    └── test_plan.md
```

---

## 5) Instrucciones para completar la propuesta

1. Define un problema pequeño y realista que pueda resolverse en terminal.
2. Limita el alcance para terminar una versión funcional mínima.
3. Documenta primero (objetivo, caso de uso, estructura y pruebas).
4. Si decides programar, haz solo un prototipo pequeño alineado al plan.
5. Evita dependencias complejas y herramientas fuera del alcance del curso.

---

## 6) Criterios de evaluación sugeridos

- **Claridad del problema y objetivo** (20%)
- **Justificación del lenguaje elegido** (15%)
- **Calidad de la documentación** (35%)
- **Coherencia de la estructura del repositorio** (15%)
- **Viabilidad del plan de pruebas** (15%)

---

## 7) Restricciones académicas y técnicas

- Proyecto **pequeño**, viable con tiempo y recursos limitados.
- Sin frameworks pesados.
- Sin APIs pagadas.
- Sin bases de datos o servicios en la nube.
- Sin contenedores.
- Sin dependencias complejas.

---

## 8) Sugerencias de temas pequeños

- Conversor de unidades en terminal.
- Organizador básico de archivos por extensión.
- Generador de checklist para estudio.
- Script de respaldo local simple.
- Utilidad para mostrar información del sistema.

---

## 9) Resultado esperado

Al finalizar, debes tener una **propuesta completa y bien documentada**, lista para convertirse en práctica programable en una segunda etapa.
