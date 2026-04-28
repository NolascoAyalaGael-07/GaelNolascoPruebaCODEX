# Actividad de GitHub Classroom: Propuesta de Práctica Temática (Enfoque en Documentación)

## 1) Título de la práctica

**Diseña tu título temático** para una práctica pequeña. Debe ser claro, breve y relacionado con una necesidad real.

Ejemplos de títulos válidos:
- **Mini Toolkit en ARM64**
- **Asistente de Estudio en Terminal**
- **Reporteador de Información del Sistema**
- **Organizador de Archivos**
- **Juego de Aprendizaje en Línea de Comandos**

---

## 2) Descripción general

En esta actividad **no se evalúa primero “cuánto código escribes”**, sino **qué tan bien justificas, documentas y planeas** una práctica temática pequeña.

Como estudiante, vas a diseñar una propuesta de proyecto que pueda desarrollarse en poco tiempo y con recursos limitados (por ejemplo, usando Codex gratuito u otra IA con límites de uso).

Debes elegir **un solo lenguaje principal**:
- **ARM64 Assembly**
- **C**
- **Python**
- **Bash**

> **Importante sobre ARM64 Assembly:** se recomienda únicamente para programas **muy pequeños** (ej. operaciones sencillas, mini utilidades de consola, validaciones básicas), por su nivel de detalle y tiempo de desarrollo.

La prioridad de esta práctica es:
1. Definir el problema o necesidad.
2. Justificar la solución propuesta.
3. Planear estructura, alcance y pruebas.
4. Documentar claramente antes de implementar.

---

## 3) Entregables del estudiante

Tu repositorio debe incluir, como mínimo, los siguientes archivos:

- `README.md`
- `docs/propuesta.md`
- `docs/caso_de_uso.md`
- `docs/estructura_repositorio.md`
- `docs/plan_de_pruebas.md`
- opcional: `src/`
- opcional: `scripts/`
- opcional: `tests/`

### Contenido esperado por archivo

#### `README.md`
Incluye:
- Nombre del proyecto.
- Lenguaje principal elegido.
- Resumen de 5 a 8 líneas del objetivo.
- Estado del proyecto (propuesta / prototipo).
- Instrucciones rápidas para revisar la documentación.

#### `docs/propuesta.md`
Incluye:
- Problema a resolver (contexto real o académico).
- Objetivo general.
- 3 objetivos específicos.
- Alcance (qué sí incluye).
- No alcance (qué no incluye).
- Justificación del lenguaje elegido.
- Estimación de tamaño: por qué es una práctica pequeña.

#### `docs/caso_de_uso.md`
Incluye:
- Actor principal (quién usa el programa).
- Escenario de uso paso a paso.
- Entrada esperada.
- Salida esperada.
- Criterios de éxito del caso de uso.

#### `docs/estructura_repositorio.md`
Incluye:
- Árbol del repositorio.
- Descripción breve de cada carpeta/archivo.
- Convención de nombres (archivos, scripts y pruebas).
- Flujo de trabajo sugerido (documentar → implementar mínimo → probar).

#### `docs/plan_de_pruebas.md`
Incluye:
- Estrategia de pruebas manuales (mínimo 5 casos).
- Casos normales.
- Casos límite (entradas vacías, rutas inválidas, datos inesperados, etc.).
- Resultado esperado por caso.
- Criterio de aprobación final.

---

## 4) Estructura recomendada del repositorio

Usa como base la siguiente estructura mínima:

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

> `<ext>` depende del lenguaje elegido (`s`, `c`, `py`, `sh`, etc.).

---

## 5) Restricciones de alcance (obligatorias)

Para mantener la práctica realista y breve:

- Proyecto **pequeño** (debe poder explicarse claramente en pocas páginas y prototiparse rápido).
- **No** usar frameworks grandes.
- **No** usar APIs pagadas.
- **No** usar bases de datos.
- **No** usar nube.
- **No** usar contenedores (Docker, etc.).
- **No** agregar dependencias complejas.

Se valoran más la claridad y la viabilidad que la complejidad técnica.

---

## 6) Guía para elegir tema (sugerencias)

Puedes proponer temas como:
- Herramienta de organización de archivos por extensión.
- Script para generar reportes simples del sistema.
- Mini asistente de estudio en terminal (preguntas/respuestas locales).
- Juego educativo corto de comandos básicos.
- Utilidad para validar formato de archivos de texto.

Todos deben ser de **ejecución local**, con insumos simples y salidas entendibles.

---

## 7) Rúbrica de evaluación sugerida (100 puntos)

- **Calidad de la propuesta (`docs/propuesta.md`)** – 30 pts  
  Claridad del problema, objetivos, alcance y justificación.

- **Caso de uso (`docs/caso_de_uso.md`)** – 20 pts  
  Coherencia entre actor, pasos, entradas/salidas y éxito.

- **Diseño del repositorio (`docs/estructura_repositorio.md`)** – 20 pts  
  Orden, consistencia y buena organización documental.

- **Plan de pruebas (`docs/plan_de_pruebas.md`)** – 20 pts  
  Casos suficientes, relevantes y verificables.

- **Presentación general (`README.md`)** – 10 pts  
  Redacción, estructura y facilidad para revisar.

---

## 8) Checklist de entrega (para estudiante)

Antes de enviar, verifica:

- [ ] Elegí un solo lenguaje principal (ARM64 Assembly, C, Python o Bash).
- [ ] Mi idea es pequeña y viable.
- [ ] Documenté objetivos, alcance y no alcance.
- [ ] Definí al menos un caso de uso completo.
- [ ] Incluí un plan de pruebas con mínimo 5 casos.
- [ ] Organicé el repositorio con la estructura solicitada.
- [ ] El `README.md` permite entender rápido el proyecto.

---

## 9) Formato de entrega en GitHub Classroom

1. Crea/usa el repositorio asignado por GitHub Classroom.
2. Sube los archivos solicitados.
3. Confirma que los nombres de archivos coincidan exactamente.
4. Realiza un commit final con mensaje sugerido:  
   `docs: propuesta inicial de práctica temática`
5. Entrega el enlace del repositorio según indique el docente.

---

## 10) Nota del instructor

La intención de esta actividad es que aprendas a **pensar como arquitecto(a) de software desde el inicio**: definir bien el problema, justificar decisiones técnicas y planear antes de codificar. En proyectos reales, una buena documentación inicial ahorra retrabajo y mejora mucho la calidad del resultado.
