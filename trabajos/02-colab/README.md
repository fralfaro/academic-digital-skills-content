# Módulo 2 · Google Colab

## 🎯 Objetivo

Ejecutar un notebook de análisis exploratorio en Google Colab, cambiando **una sola línea de código** para usar el dataset de tu elección, y subir el resultado a tu repositorio de GitHub.

---

## 📌 Pasos a seguir

### 1. Abre el notebook plantilla

Haz clic en el siguiente enlace para abrir el notebook en Google Colab:

👉 [**Abrir notebook plantilla**](https://colab.research.google.com/drive/1rpWV2AlnvUPS5NJWl2cTLq8NVlVfCdMk?usp=sharing)

Una vez abierto, ve a **Archivo → Guardar una copia en Drive** para tener tu propia versión editable.

---

### 2. Cambia el dataset (solo una línea)

En la celda marcada con `# 🔧 CAMBIA AQUÍ TU DATASET`, elige uno de los siguientes conjuntos de datos según tu tema:

| Dataset | Tema sugerido | Cómo cargarlo |
|---------|--------------|---------------|
| `tips` | Propinas / economía | `sns.load_dataset("tips")` |
| `titanic` | Historia / sociedad | `sns.load_dataset("titanic")` |
| `penguins` | Naturaleza / biología | `sns.load_dataset("penguins")` |
| `iris` | Ciencias / botánica | `sns.load_dataset("iris")` |
| `planets` | Astronomía / ciencia | `sns.load_dataset("planets")` |
| `healthexp` | Salud / economía | `sns.load_dataset("healthexp")` |
| `mpg` | Transporte / energía | `sns.load_dataset("mpg")` |
| Tu propio CSV | Cualquier tema | `pd.read_csv("tu_archivo.csv")` |

> 💡 También puedes pedirle a la IA que genere un dataset en CSV sobre tu tema:
> *"Crea un CSV con 10 filas y 4 columnas sobre [tu tema]. Devuélvelo como código Python."*

---

### 3. Ejecuta todo el notebook

Ve a **Entorno de ejecución → Reiniciar sesión y ejecutar todo**.

El notebook genera automáticamente:
- Tabla con las primeras filas del dataset
- Resumen estadístico (media, mínimo, máximo, etc.)
- Gráficos básicos según el tipo de variables

---

### 4. Descarga y sube a tu repositorio

1. En Colab: **Archivo → Descargar → Descargar .ipynb**
2. Renombra el archivo como `analisis.ipynb`
3. Súbelo a tu repositorio de GitHub (en la carpeta raíz o donde prefieras)

---

## ✅ Checklist antes de publicar en el foro

- [ ] Abriste el notebook plantilla y guardaste una copia en tu Drive
- [ ] Cambiaste el dataset por uno relacionado a tu tema
- [ ] El notebook corre sin errores (todas las celdas ejecutadas)
- [ ] El archivo `analisis.ipynb` está subido a tu repositorio de GitHub

---

## 🔗 Entrega en el foro

Publica en el foro del módulo el link directo al notebook en tu repositorio. Ejemplo:

```
https://github.com/tu-usuario/academic-digital-skills-entregables/tree/main/trabajos/02-colab/analisis.ipynb
```

Luego revisa el notebook de un compañero y comenta: ¿qué dataset usó? ¿qué descubriste mirando sus gráficos?

---

> ⬅️ [Módulo 1 — GitHub](../01-github/README.md) · ➡️ [Módulo 3 — Overleaf](../03-overleaf/README.md)