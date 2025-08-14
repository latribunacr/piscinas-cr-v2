
# Proyecto: Piscinas por cada 100 habitantes — Ciudad Real

Este proyecto publica una tabla interactiva (buscador + ordenación) que carga los datos desde `data.csv` y calcula en el navegador las **piscinas por cada 100 habitantes**.

## Estructura
- `index.html` → página lista para GitHub Pages.
- `data.csv` → datos limpios con columnas: `municipio,piscinas,habitantes`.
- `.nojekyll` → evita procesado de Jekyll.
- `README.md` → esta guía.

## Publicación en GitHub Pages (Project Pages)
1. Crea un repositorio público (p. ej., `piscinas-cr-v2`) en la cuenta **latribunacr**.
2. Sube **estos cuatro archivos a la raíz** del repo.
3. Ve a **Settings → Pages**.
   - **Source**: *Deploy from a branch*
   - **Branch**: `main`
   - **Folder**: `/ (root)`
   - **Save**
4. Abre la URL que te muestre GitHub Pages, p. ej.:
   `https://latribunacr.github.io/piscinas-cr-v2/`

## Actualizar datos
Edita `data.csv` con los municipios reales (mismas columnas). Al recargar la página, se recalcula el ratio automáticamente.

## Incrustar en tu web
```html
<iframe 
  src="https://latribunacr.github.io/piscinas-cr-v2/" 
  style="width:100%; height:720px; border:none" 
  loading="lazy">
</iframe>
```
