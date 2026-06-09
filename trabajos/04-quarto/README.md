# Módulo 4 · Posit Cloud + Quarto

## 🎯 Objetivo

Crear una presentación de 4–5 slides en Quarto (formato RevealJS), publicarla desde Posit Cloud y subir los archivos a tu repositorio de GitHub.

---

## 📌 Pasos a seguir

### 1. Crea tu cuenta en Posit Cloud

👉 [**Registrarse en Posit Cloud**](https://posit.cloud/)

Haz clic en **Sign Up** → usa tu cuenta de Google o correo. Es gratis.

---

### 2. Crea un nuevo proyecto

Una vez dentro:

1. Haz clic en **New Project → New RStudio Project**
2. Ponle un nombre (ej: `mi-presentacion`)
3. Espera que cargue el entorno — toma unos segundos

---

### 3. Crea tu presentación `.qmd`

En el panel de RStudio Cloud:

1. Ve a **File → New File → Quarto Presentation**
2. Elige el formato **Revealjs**
3. Se abrirá un archivo `.qmd` de ejemplo — reemplaza el contenido con el tuyo

---

### 4. Elige un tema y pídele ayuda a la IA

Elige cualquier tema que te interese — no tiene que ser matemático ni académico. Puede ser algo cotidiano, un hobby, un lugar, lo que quieras.

Luego copia este prompt en Claude, ChatGPT o el asistente que prefieras:

> *"Quiero hacer una presentación en Quarto RevealJS de 4-5 slides sobre **[TU TEMA]**. Dame el código `.qmd` completo con: título, 3-4 slides de contenido con texto breve y una slide final de conclusión. Usa el tema `moon` (o sugiere otro que quede bien para este tema)."*

Pega el código que te entregue en tu archivo `.qmd`.

---

### 5. Agrega una imagen (opcional)

Si quieres incluir una imagen en alguna slide:

1. Sube la imagen al proyecto en Posit Cloud (**Files → Upload**)
2. En el `.qmd` agrégala así:

```markdown
![](mi_imagen.jpg)
```

---

### 6. Renderiza la presentación

En RStudio Cloud haz clic en el botón **Render** (arriba del editor).  
Se abrirá una vista previa de tu presentación en el navegador.

---

### 7. Descarga y sube a GitHub

1. En el panel **Files** (abajo a la derecha), selecciona tu archivo `.qmd` y las imágenes que usaste
2. **More → Export** para descargarlos
3. Súbelos a la carpeta `trabajos/04-quarto/` de tu repositorio

---

## ✅ Checklist antes de publicar en el foro

- [ ] Cuenta creada en Posit Cloud
- [ ] Presentación con 4–5 slides sobre un tema de tu elección
- [ ] La presentación renderiza sin errores
- [ ] El archivo `.qmd` (y las imágenes si las hay) están en `trabajos/04-quarto/` de tu repositorio

---

## 🔗 Entrega en el foro

Publica el link a la carpeta o al archivo `.qmd` en tu repositorio. Ejemplo:

```
https://github.com/tu-usuario/academic-digital-skills-entregables/tree/main/trabajos/04-quarto/presntacion.qmd
```

Luego revisa la presentación de un compañero y comenta: ¿de qué habla? ¿cómo se ve el diseño?

---

> ⬅️ [Módulo 3 — Overleaf](../03-overleaf/README.md) · ⬆️ [Volver al inicio](../../README.md)