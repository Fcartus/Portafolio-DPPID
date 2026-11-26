# Portafolio · Facundo Cabrera Artus

> Doy forma a lo tangible y estructura a lo invisible.

Portafolio interactivo de diseño industrial e interacción. Todo el sitio está hecho de caracteres ASCII que responden a quien lo visita:

- **Gotas:** un plano de agua en ASCII. Cada toque deja caer una gota afinada según una grilla musical de 8 × 7 (las 12 tonalidades, en modos de grave a agudo).
- **Proyectos:** una rueda de precisión. Arrastrar hacia abajo revela los proyectos del curso; hacia arriba, los de la carrera.
- **Sobre mí:** retrato en ASCII y biografía.

Se navega con los tres faders del panel inferior.

## Ver el sitio

Una vez publicado con GitHub Pages: `https://fcartus.github.io/<nombre-del-repositorio>/`

## Publicar en GitHub Pages

1. Crea un repositorio público en GitHub.
2. Sube los tres archivos de esta carpeta (`index.html`, `README.md` y `.nojekyll`) en «Add file → Upload files». Las fotos y el sonido van dentro de `index.html`, así que no hay carpetas que subir.
3. En el repositorio: **Settings → Pages → Build and deployment → Source: Deploy from a branch**, rama `main`, carpeta `/ (root)`.
4. Espera uno o dos minutos y abre la dirección que muestra Pages.

## Archivos

```
index.html   el sitio completo en un solo archivo: HTML, CSS, JavaScript, el sonido y las 38 fotos
             (Archivo Vivo, Soplador, MoRe y perfil) incrustadas
.nojekyll    indica a GitHub Pages que publique los archivos tal cual
```

## Créditos

- Sonido: water drop one shot dry (extraído de Freesound).
- Tipografías: VT323 y Doto (Google Fonts).
- Estela del puntero adaptada del componente WakeGlyph de nikolas-sapa (21st.dev).
