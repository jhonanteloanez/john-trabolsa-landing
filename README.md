# Despliegue de la landing page

Esta carpeta contiene una landing page estática para `John Trabolsa`.

## Archivos

- `index.html`
- `styles.css`

## Opción 1: Desplegar en Vercel

1. Crea una cuenta en https://vercel.com/ si no tienes.
2. Inicia sesión y selecciona "New Project".
3. Elige la opción de importar desde GitHub/GitLab/Bitbucket, o usa "Import Third-Party Repository" si tienes tu repositorio.
4. Si prefieres sin repositorio, arrastra la carpeta `Landing Page John Trabolsa` directamente a la sección de "Deploy" de Vercel.
5. Vercel detecta el sitio como estático y lo desplegará automáticamente.

### Con Vercel CLI (opcional)

Si quieres hacerlo desde tu máquina:

```bash
npm install -g vercel
cd "c:\Users\lenovo\Desktop\Landing Page John Trabolsa"
vercel --prod
```

## Opción 2: Desplegar en Netlify

1. Crea una cuenta en https://www.netlify.com/ si no tienes.
2. Inicia sesión y selecciona "Add new site" > "Deploy manually".
3. Arrastra la carpeta `Landing Page John Trabolsa` o solo los archivos `index.html` y `styles.css`.
4. Netlify te dará una URL pública al instante.

## Notas

- El botón de WhatsApp ya está configurado en `index.html` con tu número.
- Si quieres, puedo ayudarte a crear un repositorio Git y conectarlo directamente a Vercel o Netlify.