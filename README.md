# HPR PRIME — Suite de 40 Programas de Ingeniería (HP Prime G2)

Landing page oficial, autónoma y optimizada para **GitHub Pages**.

## 🚀 Publicación Inmediata en GitHub Pages

Esta carpeta está organizada de forma **100% autónoma y autocontenida** (sin dependencias externas ni CDNs obligatorios). Para publicarla:

1. **Subir los archivos a tu repositorio de GitHub:**
   - Puedes subir el contenido de esta carpeta `landing/` directamente a la raíz (`/`) de tu repositorio en GitHub.
2. **Activar GitHub Pages:**
   - En tu repositorio de GitHub, ve a **Settings** > **Pages**.
   - En **Build and deployment** > **Source**, selecciona `Deploy from a branch`.
   - En **Branch**, selecciona `main` (o `master`) y la carpeta `/ (root)`.
   - Haz clic en **Save**.
3. **¡Listo!** Tu web estará visible en `https://<tu-usuario>.github.io/<tu-repositorio>/`.

---

## 📁 Estructura del Proyecto

```text
landing/
├── index.html                 # Página principal con catálogo de 40 programas
├── README.md                  # Guía de publicación
└── assets/
    ├── poppins.css            # Tipografía Poppins local (100% offline)
    ├── logo_inertix_transparent.png  # Logotipo oficial INERTIX
    ├── fonts/                 # 18 archivos WOFF2 de Poppins
    ├── js/
    │   └── liquid-text.js     # Motor WebGL de animación líquida nativa
    └── programas/             # 40 carpetas con iconos PNG/SVG y capturas reales
        ├── ACERIX/
        ├── APUX/
        ├── DINAMIX/
        └── ... (40 programas)
```

---

## ✨ Características Principales
- **Animación Líquida WebGL:** En el Hero H1, Catálogo H2 y en los títulos de cada una de las 40 tarjetas al pasar el cursor.
- **Efecto de Tarjeta Elevada:** Efecto hover dinámico (`translateY(-4px)` con resalte naranja y sombra).
- **Ficha Técnica (Modal 2-Columnas):** Información normativa, módulos, especificaciones y capturas nativas HP Prime (320x240).
- **Atención Directa por WhatsApp:** Enlace integrado en los 5 puntos clave con el número `+591 69666824`.
- **Filtros por Especialidad y Buscador en Tiempo Real.**
