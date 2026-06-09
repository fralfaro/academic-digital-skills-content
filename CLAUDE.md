# CLAUDE.md — Instrucciones para Claude Code

## Contexto del proyecto

Este repositorio (`academic-digital-skills`) es un recurso educativo del propedéutico de la
Universidad Técnica Federico Santa María (USM). Está dirigido a estudiantes de 3°–4° medio que
se están preparando para ingresar a una carrera de Ingeniería. El objetivo es presentarles
herramientas digitales clave para su vida académica universitaria.

El repositorio tiene la siguiente estructura bajo `trabajos/`:

```
trabajos/
  01-github/
  02-colab/
  03-overleaf/
  04-quarto/
```

---

## Tarea principal

Crea un archivo `motivacion.md` dentro de **cada una** de las cuatro carpetas anteriores.

Cada archivo debe cumplir con las siguientes condiciones:

---

## Estructura de cada `motivacion.md`

```markdown
# 🎬 Motivación — [Nombre de la herramienta]

## ¿Por qué aprender [herramienta]?

[Párrafo motivador, tono cercano, directo y entusiasta. Hablar de "tú" al estudiante.
Conectar con el dolor o problema concreto que resuelve la herramienta.
El estudiante está entrando a Ingeniería en la USM: eso es exigente y emocionante.]

## El problema que resuelve

[Párrafo breve describiendo la situación sin la herramienta: qué pasa si sigues
usando lo que usabas antes. Ser concreto y realista.]

## Lo que vas a poder hacer

- [Beneficio 1]
- [Beneficio 2]
- [Beneficio 3]
- [Beneficio 4]

## 🚀 ¿Listo para empezar?

> [Frase de cierre motivadora, breve, que invite a ver el material de la clase.]

📚 **Clase completa:** [link correspondiente]
```

---

## Contenido específico por herramienta

### 01-github → `motivacion.md`

- **Problema a resolver:** guardar proyectos en Google Drive o OneDrive está bien para archivos de texto, pero para código es un desastre: no hay versiones, no puedes colaborar en tiempo real, y nadie puede ver tu trabajo.
- **Propuesta:** GitHub es donde los ingenieros muestran sus proyectos al mundo. Tu portafolio de código en GitHub es como tu CV técnico.
- **Beneficios:** control de versiones, trabajo en equipo, portafolio público, industria estándar.
- **Tono:** "Si alguna vez trabajaste en grupo y terminaste con archivos llamados `informe_final_v3_ESTE.docx`, GitHub es para ti."
- **Link de la clase:** `https://fralfaro.github.io/talks/tools/github/presentacion.html#/title-slide`

---

### 02-colab → `motivacion.md`

- **Problema a resolver:** instalar Python, Anaconda, librerías, configurar el entorno… puede tomar horas y aun así fallar. Además, no todos tienen el mismo computador.
- **Propuesta:** Google Colab te da Python directamente en el navegador, sin instalar nada. Y tiene acceso a librerías de Data Science e Inteligencia Artificial con un solo `import`.
- **Beneficios:** sin instalación, gratis, GPU disponible, librerías como pandas/sklearn/TensorFlow listas para usar, ideal para explorar IA y ciencia de datos.
- **Tono:** "¿Quieres entrenar una red neuronal desde el computador del colegio? Con Colab, puedes."
- **Link de la clase:** `https://fralfaro.github.io/talks/tools/colab/presentacion.html#/title-slide`

---

### 03-overleaf → `motivacion.md`

- **Problema a resolver:** Microsoft Word es un dolor de cabeza para informes técnicos: las ecuaciones se ven mal, el formato se rompe, las referencias son un caos, y dos personas editando el mismo archivo es una pesadilla.
- **Propuesta:** LaTeX (vía Overleaf) es el estándar en ingeniería y ciencias para escribir documentos técnicos. Tú te concentras en el contenido; LaTeX hace que se vea profesional.
- **Beneficios:** ecuaciones hermosas, formato automático, bibliografía integrada, colaboración en la nube, mismo estándar que papers y tesis en la USM.
- **Tono:** "Cuando escribas tu primera tesis o informe de laboratorio, vas a agradecer no tener que pelear con Word."
- **Link de la clase:** `https://fralfaro.github.io/talks/tools/overleaf/presentacion.html#/title-slide`

---

### 04-quarto → `motivacion.md`

- **Problema a resolver:** hacer presentaciones bonitas toma tiempo, y si además tienen código o resultados, mantenerlos actualizados es imposible con PowerPoint.
- **Propuesta:** Quarto permite crear presentaciones, reportes y sitios web que combinan texto, código y visualizaciones en un solo archivo. Puedes reproducirlas, publicarlas y hasta correrlas con herramientas como Claude.
- **Beneficios:** presentaciones reproducibles, integración con Python/R, publicación web automática, reutilizable para informes y portafolios.
- **Tono:** "Imagina hacer una presentación donde los gráficos se actualizan solos cuando cambian los datos. Eso es Quarto."
- **Link de la clase:** `https://fralfaro.github.io/talks/tools/quarto/presentacion.html#/title-slide`

---

## Reglas de estilo y tono

- Hablar de **"tú"** al estudiante, no de "usted".
- Tono: **cercano, motivador, realista**. No sonar corporativo ni aburrido.
- Longitud: cada `motivacion.md` debe tener entre **250 y 400 palabras**.
- Usar **emojis con moderación** (máximo 3–4 por archivo, solo en títulos o llamadas de atención).
- Los ejemplos deben resonar con la experiencia de un estudiante de 3°–4° medio chileno.
- Evitar jerga muy técnica sin explicarla brevemente.
- Siempre cerrar con el link de la clase correspondiente en negrita.

---

## Verificación al finalizar

Después de crear los cuatro archivos, muestra un resumen con:

```
✅ trabajos/01-github/motivacion.md     — creado
✅ trabajos/02-colab/motivacion.md      — creado
✅ trabajos/03-overleaf/motivacion.md   — creado
✅ trabajos/04-quarto/motivacion.md     — creado
```

Si alguna carpeta no existe, créala antes de escribir el archivo.
