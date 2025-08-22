# 🌐 Deploy en GitHub Pages

Este proyecto es un **Profile Card / Linktree** hecho en HTML y CSS.  
Aquí tienes la guía rápida para desplegarlo en **GitHub Pages**.

---

## ✅ Pasos para desplegar

### 1. **Crear un repositorio en GitHub**

- Ve a [GitHub](https://github.com) y crea un repo nuevo (ejemplo: `profile-card`).

### 2. **Subir tu proyecto al repo**

```bash
git init
git add .
git commit -m "Versión inicial"
git branch -M main
git remote add origin https://github.com/TU-USUARIO/profile-card.git
git push -u origin main
```

### 3. **Activar GitHub Pages**

- En tu repositorio, ve a **Settings > Pages**.
- En la sección **Branch**, selecciona:
  - **Source** → `main`
  - **Folder** → `/root` (si `index.html` está en la raíz).
- Haz clic en **Save**.

### 4. **Esperar a que se genere la página**

- GitHub creará automáticamente el sitio.
- En unos segundos verás la URL en el mismo apartado de Pages, algo así:

```
https://tu-usuario.github.io/profile-card/
```

### 5. **Verificar tu despliegue**

- Entra al link para ver tu tarjeta.
- ⚠️ **Si las imágenes no cargan**, revisa que las rutas coincidan exactamente (recuerda: `assets` ≠ `Assets`).

---

## 🔧 Tips

- **Actualizaciones automáticas**: Cada vez que hagas `git push` a `main`, GitHub Pages actualizará tu sitio automáticamente.
- **Carpeta alternativa**: Si prefieres usar la carpeta `/docs`, mueve ahí tu `index.html` y selecciona esa opción en Settings.
- **Dominio personalizado**: Puedes configurar un dominio personalizado en la misma sección de Pages.

---

## 🎉 Resultado

Una vez desplegado, comparte tu link, por ejemplo:

👉 **Mi Profile Card en vivo**

---

**Hecho con 💙 por Dina Rocío**
