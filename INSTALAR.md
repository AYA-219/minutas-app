# INSTALAR APP MINUTAS — Guía paso a paso

## PASO 1 — Subir a GitHub (1 vez, gratis)

1. Ir a [github.com](https://github.com) → Crear cuenta gratuita (si no tenés)
2. Clic en **"New repository"**
3. Nombre: `minutas-app`
4. Dejar en **Public** → clic **"Create repository"**
5. En la pantalla siguiente, elegir **"uploading an existing file"**
6. Arrastrar los 5 archivos de esta carpeta (`webapp/`):
   - `index.html`
   - `manifest.json`
   - `sw.js`
   - `icon.svg`
   - `vercel.json`
7. Clic **"Commit changes"**

---

## PASO 2 — Publicar en Vercel (1 vez, gratis)

1. Ir a [vercel.com](https://vercel.com) → **"Sign up with GitHub"**
2. Clic **"Add New Project"**
3. Seleccionar el repositorio `minutas-app`
4. Clic **"Deploy"** (sin cambiar ninguna configuración)
5. En 30 segundos aparece la URL:

```
https://minutas-app.vercel.app
```

---

## PASO 3 — Instalar en cada celular

Compartir la URL con el equipo (por WhatsApp o email).

### En Android (Chrome):
1. Abrir Chrome → ir a la URL
2. Menú (⋮) → **"Agregar a pantalla de inicio"**
3. Tocar **"Agregar"**
4. El ícono aparece como cualquier app

### En iPhone (Safari):
1. Abrir **Safari** (no Chrome) → ir a la URL
2. Tocar el botón de compartir (□↑)
3. Deslizar y tocar **"Agregar a pantalla de inicio"**
4. Tocar **"Agregar"**
5. El ícono aparece en la pantalla de inicio

> ⚠️ En iPhone usar Safari. Chrome en iOS no permite instalación de PWA.

---

## PASO 4 — Configurar la lista de distribución

Al abrir la app por primera vez:
1. Tocar **"👥 Equipo"** (arriba a la derecha)
2. Tocar **+** para agregar cada integrante
3. Ingresar: nombre, email y número de WhatsApp (con +54...)
4. Activar (✓) los que reciben cada minuta

---

## Actualizaciones futuras

Si se realizan cambios en la app, basta con subir los archivos actualizados a GitHub. Vercel los publica automáticamente y todos los celulares ven la versión nueva la próxima vez que abren la app.

---

## Requisitos

- Celular con Chrome (Android) o Safari (iOS)
- Internet para la primera instalación y para el OCR (descarga del modelo de idioma español)
- Sin internet: la app funciona pero el OCR no está disponible (se puede ingresar manualmente)

---

## Soporte
g.albera@alberayasociados.com
