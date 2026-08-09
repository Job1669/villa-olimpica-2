# Villa Olímpica — Evidencia de aprendizaje U1

Sitio web responsivo de la tienda deportiva **Villa Olímpica**, desarrollado con HTML5 y CSS3, sin frameworks ni gestores de contenido. Incluye las páginas **Inicio** y **Más vendidos**, y adapta sus cuadrículas mediante media queries.

## Estructura

- `index.html`: página de Inicio.
- `mas-vendidos.html`: seis productos destacados.
- `css/estilos.css`: apariencia y media queries.
- `img/`: logotipo, fachada y productos.
- `.github/workflows/pages.yml`: publicación automática en GitHub Pages.

## Publicación corregida en GitHub Pages

1. Extrae este proyecto y sube **su contenido directamente a la raíz** del repositorio. `index.html` debe quedar visible en la portada del repositorio; no debe estar dentro de otra carpeta llamada `sitio`.
2. Usa la rama `main`.
3. En `Settings > Pages`, selecciona **GitHub Actions** como origen de publicación.
4. Abre `Actions` y ejecuta el flujo **Publicar Villa Olímpica en GitHub Pages**, o realiza un cambio en la rama `main` para iniciarlo automáticamente.
5. Al terminar, la URL aparecerá en el trabajo de despliegue y en `Settings > Pages`.

## Corrección aplicada al error de espera

El archivo `dynamic/pages/pages-build-deployment` que aparece en los registros es un flujo interno generado por GitHub y no se puede editar desde el repositorio. Este proyecto incluye un flujo propio con:

- Preparación explícita del sitio como artefacto estático.
- Acciones oficiales de GitHub Pages.
- Tiempo máximo de despliegue ampliado a 30 minutos.
- Trabajo completo con límite de 40 minutos.
- Concurrencia sin cancelar el despliegue que ya está en cola.

## Datos académicos

- Nombre: Hernán Job Ramirez López
- Docente: Josafat Poctzin Dircio
- Materia: Programación web II
