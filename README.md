# 📱 Calculadora Fondos — Guía de instalación en iPhone

## Archivos incluidos
- `index.html` → La calculadora
- `manifest.json` → Info de la app (nombre, colores, icono)
- `sw.js` → Service Worker (funciona offline)

---

## Paso a paso: Subir a GitHub Pages

### 1. Crear cuenta en GitHub
Ve a https://github.com y crea una cuenta gratuita.

### 2. Crear repositorio
- Pulsa el botón **"+"** arriba a la derecha → **"New repository"**
- Nombre: `fondos` (o el que quieras)
- Marca **"Public"**
- Pulsa **"Create repository"**

### 3. Subir los archivos
- En la página del repositorio, pulsa **"uploading an existing file"**
- Arrastra los 3 archivos: `index.html`, `manifest.json`, `sw.js`
- Pulsa **"Commit changes"**

### 4. Activar GitHub Pages
- Ve a **Settings** (pestaña arriba)
- En el menú izquierdo: **Pages**
- En "Source" selecciona **"Deploy from a branch"**
- Branch: **main** / carpeta: **/ (root)**
- Pulsa **Save**

### 5. Tu URL (lista en ~2 minutos)
```
https://TU_USUARIO.github.io/fondos/
```

---

## Instalar en iPhone como app

1. Abre Safari en tu iPhone
2. Ve a tu URL de GitHub Pages
3. Pulsa el botón de compartir (cuadrado con flecha ↑)
4. Toca **"Añadir a pantalla de inicio"**
5. Ponle nombre: **Fondos**
6. Pulsa **Añadir**

✅ Ya tienes el icono en tu pantalla de inicio. Funciona offline una vez cargada.
