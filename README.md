# 📊 Bioestadística Skill (`SKILL.md`)

Skill especializada en **Bioestadística y Estadística aplicada a las Ciencias de la Salud** para asistentes de Inteligencia Artificial (compatible con plataformas que soportan especificaciones de agentes y skills con `SKILL.md`).

Diseñada para resolver problemas, contrastar hipótesis e interpretar resultados clínicos siguiendo el **formalismo académico universitario**, evitando atajos o resoluciones superficiales.

---

## 📌 Origen y Metodología (Aviso de Transparencia)

> **Nota sobre el desarrollo:**  
> Este proyecto ha sido redactado y estructurado con **fuerte asistencia de Inteligencia Artificial**, pero **su lógica, metodología y criterios se basan íntegramente en los apuntes oficiales y temarios de 2.º curso universitario de Bioestadística** (Grados en Ciencias de la Salud: Medicina, Biología, Farmacia, Enfermería, Biotecnología).

El objetivo principal fue transformar el rigor de los apuntes tradicionales (notaciones, pasos obligatorios en exámenes, justificación de hipótesis y criterios clínicos) en un conjunto de instrucciones de sistema estrictas para que la IA no invente procedimientos ni proporcione respuestas simplistas.

---

## ¿Qué hace esta Skill?

Cuando se activa, la IA adopta el rol de docente/especialista y aplica un protocolo de resolución estricto:

1. **Prioridad absoluta a los apuntes del alumno:** Si se adjunta material o apuntes de clase, prioriza la nomenclatura y fórmulas del profesor.
2. **Estructura académica de 7 pasos:**
   - Datos y objetivo
   - Elección y justificación del método
   - Fórmula analítica
   - Sustitución y cálculo detallado (sin saltos bruscos)
   - Resultado con unidades y redondeo adecuado
   - Interpretación contextualizada en salud
   - Verificación de supuestos y limitaciones
3. **Enfoque biomédico:**
   - Distingue claramente entre significación estadística ($p < \alpha$) e importancia clínica.
   - Trato riguroso de pruebas diagnósticas (Sensibilidad, Especificidad, Prevalencia, VPP y VPN vía Teorema de Bayes).
   - Manejo adecuado de contrastes paramétricos vs. no paramétricos y verificación de normalidad/homocedasticidad.

---

## 🌐 Idioma y Soporte Multilingüe

- **Idioma por defecto:** Español (con terminología adaptada al ámbito universitario hispanohablante).
- **Adaptación a otros idiomas:** Aunque su configuración base responde en español, la skill contempla explícitamente en sus instrucciones (*Sección 3: "Responde en español, salvo que el usuario solicite otro idioma"*) la capacidad de operar en **cualquier otro idioma** (inglés, francés, etc.). Basta con pedírselo en el prompt o formular la consulta en ese idioma para que adapte tanto el razonamiento como la notación estadística correspondiente.

---

## Activadores (Triggers)

La skill se activa automáticamente cuando en la conversación o prompt se detectan términos clave como:

- `bioestad`
- `bioestadistica`
- `bioestadística`
- O peticiones explícitas para resolver o contrastar ejercicios de estadística médica, epidemiología analítica o inferencia.

---

## 📂 Contenido del repositorio

```text
├── assets/
│   └── bibliograf.tex  # Apuntes y fuentes de referencia de bioestadística (LaTeX)
├── SKILL.md            # Definición de la habilidad (instrucciones + frontmatter YAML)
├── LICENSE             # Términos de la licencia de uso
└── README.md           # Documentación del proyecto

---

## ⚙️ Instalación / Uso

### Opción 1: En plataformas compatibles con Agent Skills / `.skill`
1. Descarga el archivo `SKILL.md` (o comprímelo en un archivo `.zip` si tu plataforma lo requiere).
2. Súbelo en el panel de configuración de skills/herramientas de tu agente.

### Opción 2: Como Custom Instruction / System Prompt
Si utilizas ChatGPT, Claude u otra interfaz web sin soporte nativo de archivos `.skill`:
1. Abre `SKILL.md`.
2. Omite el bloque YAML inicial (`--- ... ---`).
3. Copia el resto del texto y pégalo en la sección de **Instrucciones personalizadas (System Prompt)** de tu asistente o proyecto.

---

## 📖 Temas cubiertos

- **Estadística descriptiva:** Medidas de centralización, dispersión, asimetría y robustez frente a *outliers*.
- **Probabilidad y diagnóstico:** Teorema de Bayes, tasas de falsos positivos/negativos, probabilidades condicionadas.
- **Distribuciones teóricas:** Binomial, Poisson, Normal, $t$ de Student, Chi-cuadrado, etc.
- **Muestreo y estimación:** Estimación puntual, errores estándar y cálculo de tamaño muestral.
- **Intervalos de confianza y contrastes de hipótesis:** Formulaciones bilaterales/unilaterales, estadísticos de prueba, región crítica y valores $p$.
- **Asociación y modelos:** Tablas de contingencia, correlación (Pearson/Spearman) y regresión lineal.

---

## ⚠️ Descargo de responsabilidad (Disclaimer)

Esta skill está concebida como una **herramienta de apoyo al estudio universitario**. Aunque ha sido diseñada para minimizar alucinaciones y forzar la comprobación matemática:
- Debe contrastarse siempre con los criterios específicos del profesorado de cada facultad o departamento.
- **No debe utilizarse como herramienta de diagnóstico clínico o toma de decisiones médicas reales.**

---

## Contribuciones

Si cursas Bioestadística y crees que falta alguna convención, prueba estadística habitual o caso especial, ¡las *pull requests* y *issues* son bienvenidas!
