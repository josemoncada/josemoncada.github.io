# Portfolio de José Moncada Muñoz

Portfolio profesional bilingüe (Inglés/Español) construido con HTML, CSS y JavaScript vanilla. Optimizado para GitHub Pages.

## 🚀 Características

- ✨ Diseño moderno y profesional
- 🌐 Bilingüe: Español e Inglés con cambio dinámico
- 📱 Completamente responsive (mobile-first)
- 🎨 Animaciones suaves y efectos visuales
- ⚡ Carga rápida (sin dependencias externas excepto fuentes)
- 📄 Descarga de CV en ambos idiomas
- 🎯 Secciones: About, Experience, Projects, Skills, Education, Contact

## 📦 Estructura del Proyecto

```
portfolio/
├── index.html                      # Página principal (todo incluido)
├── José_Moncada_Muñoz_CV.pdf     # CV en español
├── Jose_Moncada_Munoz_CV_EN.pdf  # CV en inglés
└── README.md                      # Este archivo
```

## 🛠️ Deployment en GitHub Pages

### Método 1: Crear un nuevo repositorio (Recomendado)

1. **Crea un nuevo repositorio en GitHub:**
   - Nombre sugerido: `portfolio` o `{tu-usuario}.github.io` (para URL personalizada)
   - Marca como público
   - NO inicialices con README

2. **Sube los archivos:**
   ```bash
   # En tu terminal, navega a la carpeta donde tienes los archivos
   cd /ruta/a/tu/portfolio
   
   # Inicializa git
   git init
   
   # Añade los archivos
   git add .
   
   # Commit
   git commit -m "Initial commit: Professional portfolio"
   
   # Conecta con tu repositorio de GitHub
   git remote add origin https://github.com/TU-USUARIO/portfolio.git
   
   # Sube los archivos
   git branch -M main
   git push -u origin main
   ```

3. **Activa GitHub Pages:**
   - Ve a Settings → Pages
   - En "Source", selecciona "Deploy from a branch"
   - En "Branch", selecciona `main` y carpeta `/ (root)`
   - Click en "Save"

4. **¡Listo!** Tu sitio estará disponible en:
   - Si usaste `{tu-usuario}.github.io`: https://{tu-usuario}.github.io
   - Si usaste otro nombre: https://{tu-usuario}.github.io/portfolio

### Método 2: Usando el interfaz web de GitHub

1. Crea un nuevo repositorio en GitHub
2. Click en "Add file" → "Upload files"
3. Arrastra los 3 archivos (index.html y ambos PDFs)
4. Commit los cambios
5. Sigue el paso 3 del Método 1 para activar GitHub Pages

## 📝 Personalización

### Cambiar colores
Edita las variables CSS en la sección `:root` del archivo `index.html`:
```css
:root {
    --bg-primary: #0a0e27;      /* Color de fondo principal */
    --accent-primary: #00d9ff;   /* Color de acento (cyan) */
    --accent-secondary: #7c3aed; /* Color secundario (purple) */
    /* ... más variables ... */
}
```

### Actualizar contenido
Todo el contenido está en el archivo `index.html`. Busca las secciones:
- `<section class="hero">` - Hero/Inicio
- `<section id="about">` - Acerca de
- `<section id="experience">` - Experiencia
- `<section id="projects">` - Proyectos
- `<section id="skills">` - Habilidades
- `<section id="education">` - Educación
- `<section id="contact">` - Contacto

### Actualizar CVs
Simplemente reemplaza los archivos PDF con las nuevas versiones manteniendo los nombres:
- `José_Moncada_Muñoz_CV.pdf` (español)
- `Jose_Moncada_Munoz_CV_EN.pdf` (inglés)

## 🌐 URLs Personalizadas

### Opción 1: Dominio de GitHub
Si nombraste tu repositorio como `{tu-usuario}.github.io`, ese será tu dominio principal.

### Opción 2: Dominio personalizado
1. Compra un dominio (ej: josemoncada.dev)
2. En GitHub Pages settings, añade tu dominio custom
3. Configura los DNS de tu proveedor:
   ```
   Type: A Record
   Name: @
   Value: 185.199.108.153
   Value: 185.199.109.153
   Value: 185.199.110.153
   Value: 185.199.111.153
   
   Type: CNAME
   Name: www
   Value: {tu-usuario}.github.io
   ```

## 🔧 Tecnologías Utilizadas

- HTML5
- CSS3 (Custom Properties, Grid, Flexbox, Animations)
- JavaScript Vanilla (ES6+)
- Google Fonts (JetBrains Mono, Manrope)

## 📱 Responsive Design

El sitio está optimizado para:
- 📱 Mobile: 320px - 768px
- 💻 Tablet: 768px - 1024px
- 🖥️ Desktop: 1024px+

## ⚡ Rendimiento

- Sin dependencias npm
- Sin frameworks pesados
- Fuentes optimizadas con `display=swap`
- Animaciones CSS optimizadas
- Imágenes no incluidas (solo texto y fuentes)

## 🎨 Paleta de Colores

- **Background:** Dark Navy (#0a0e27)
- **Accent:** Cyan (#00d9ff)
- **Secondary:** Purple (#7c3aed)
- **Text:** Light Gray (#e8edf4)

## 📄 Licencia

Este portfolio es de uso personal para José Moncada Muñoz. Puedes usarlo como inspiración, pero por favor crea tu propio diseño único.

## 🤝 Contacto

- **Email:** jose.moncada.munoz@gmail.com
- **Phone:** +52 644 161 7743
- **Location:** México | Remoto

---

**Nota:** Asegúrate de tener los archivos PDF de tu CV en la misma carpeta que el `index.html` antes de hacer el deployment a GitHub Pages.

## 🚀 Quick Start para GitHub Pages

```bash
# 1. Clone este repositorio o descarga los archivos
# 2. Navega a la carpeta
cd portfolio

# 3. Verifica que tengas los 3 archivos:
ls
# Deberías ver: index.html, José_Moncada_Muñoz_CV.pdf, Jose_Moncada_Munoz_CV_EN.pdf

# 4. Inicializa git y sube a GitHub
git init
git add .
git commit -m "Initial commit"
git remote add origin https://github.com/TU-USUARIO/TU-REPO.git
git push -u origin main

# 5. Activa GitHub Pages en Settings → Pages
```

¡Y listo! 🎉
