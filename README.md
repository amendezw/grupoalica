# Grupo Álica · Plataformas, IA y seguridad

Propuesta interactiva de Wigilabs para Grupo Álica. Sitio estático de un solo archivo (`index.html`) con los prototipos incluidos; no requiere backend ni compilación.

## Contenido

- `index.html` — sitio completo, con imágenes, fuentes y prototipos embebidos.
- `vercel.json` — configuración de Vercel (sin indexación en buscadores).
- `robots.txt` — bloquea buscadores.

## Subir a GitHub

```bash
git init
git add .
git commit -m "Propuesta Grupo Álica"
git branch -M main
git remote add origin https://github.com/<organizacion>/grupo-alica-propuesta.git
git push -u origin main
```

Se recomienda un repositorio **privado**.

## Deploy en Vercel

1. En vercel.com, **Add New → Project** e importa el repositorio.
2. Framework Preset: **Other**. Build Command: vacío. Output Directory: `./` (raíz).
3. **Deploy**.

Para compartir por enlace privado, activa **Settings → Deployment Protection** (Vercel Authentication o contraseña).

## Notas

- Las fotos de Las Palomas, Jardines de San Juan, la planta de Frutálica y Nukari provienen de sitios oficiales del grupo; confirmar derechos de uso antes de compartir fuera de Álica.
- Personajes, precios y cifras de los prototipos son ficticios.
