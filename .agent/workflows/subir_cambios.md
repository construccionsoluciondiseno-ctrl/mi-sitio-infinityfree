---
description: Guía paso a paso para guardar y subir cambios a GitHub
---

# Cómo subir cambios a GitHub

Cada vez que realices modificaciones en tu código (editar HTML, CSS, agregar imágenes, etc.) y quieras guardarlas en la nube (GitHub), sigue estos pasos desde la terminal:

## 1. Preparar los archivos (Stage)
Este comando prepara todos los archivos modificados para ser guardados.
```powershell
git add .
```

## 2. Guardar los cambios (Commit)
Este comando guarda una "foto" de tus cambios con un mensaje descriptivo.
Cambia el mensaje entre comillas por algo que describa lo que hiciste (ej. "Agregué nuevo logo", "Corregí colores", etc.).
```powershell
git commit -m "Describe aquí tus cambios"
```

## 3. Subir a GitHub (Push)
Este comando envía tus cambios guardados a tu repositorio en GitHub.
```powershell
git push origin main
```

---
**Tip:** Si en algún momento `git push` falla porque hay cambios en internet que no tienes, usa `git pull origin main` primero.
