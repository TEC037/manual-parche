# M@nü4I D3l P4rch3 - Sitio GitHub Pages

Este repositorio contiene la interfaz web estática lista para desplegar en **GitHub Pages**. Permite visualizar el documento directamente en el navegador, descargarlo con toda la metadata ofuscada y acceder al enlace de registro de membresías.

---

## 📁 Contenido del Repositorio

- `index.html`: Interfaz web completa con visor PDF integrado, botones de descarga, diseño responsivo y modal de redirección a las membresías.
- `M@nü4I D3l P4rch3.pdf`: Archivo PDF con metadata corrompida y contenido intacto.
- `manual.pdf`: Copia para visualización web compatible.
- `.nojekyll`: Desactiva el preprocesamiento de Jekyll en GitHub Pages para garantizar la entrega directa de todos los archivos.

---

## 🚀 Pasos para Publicar en GitHub Pages

### 1. Crear un repositorio en GitHub
1. Entra a tu cuenta en [GitHub.com](https://github.com/new).
2. Crea un nuevo repositorio (por ejemplo: `manual-parche` o `manual-tactico`).
3. Puedes dejarlo **Público** para que GitHub Pages sea accesible de forma gratuita.

### 2. Subir los archivos desde tu terminal
Abre una terminal en esta carpeta y ejecuta:

```bash
git init -b main
git add .
git commit -m "feat: publicar manual con visor y redireccion a membresias"
git remote add origin https://github.com/TU-USUARIO/manual-parche.git
git push -u origin main
```
*(Reemplaza `TU-USUARIO` y `manual-parche` con los datos de tu repositorio).*

### 3. Activar GitHub Pages en el repositorio
1. En GitHub, ve a la pestaña **Settings** (Configuración) de tu repositorio.
2. En el menú lateral izquierdo, haz clic en **Pages**.
3. En **Build and deployment** > **Source**, selecciona `Deploy from a branch`.
4. En **Branch**, selecciona `main` y la carpeta `/(root)`.
5. Haz clic en **Save**.

En 1 a 2 minutos tu sitio estará en vivo en:
`https://TU-USUARIO.github.io/manual-parche/`
