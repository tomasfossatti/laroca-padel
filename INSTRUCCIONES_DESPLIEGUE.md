# 🚀 Guía de Despliegue Permanente: La Roca Padel Club

Para que tu sitio web esté disponible en Internet de forma **permanente y gratuita**, te recomiendo usar **Netlify**, que es la opción más rápida y sencilla.

### Opción 1: Despliegue Rápido (Netlify Drop)
1. Extrae el archivo `.zip` que te envié.
2. Abre tu navegador y ve a [Netlify Drop](https://app.netlify.com/drop).
3. Arrastra la carpeta `laroca-final` completa directamente al cuadro que aparece en la página.
4. **¡Listo!** En unos segundos, Netlify te dará una URL (ej: `nombre-aleatorio.netlify.app`) donde tu sitio estará activo.

### Opción 2: Usar GitHub (Recomendado para cambios futuros)
Si quieres un control total y actualizaciones automáticas:
1. Sube los archivos de la carpeta `laroca-final` a un nuevo repositorio en tu cuenta de GitHub.
2. Ve a [Vercel](https://vercel.com) o [Netlify](https://netlify.com).
3. Conecta tu repositorio y selecciona "Deploy".
4. Cada vez que cambies algo en GitHub, tu sitio se actualizará solo.

---
### Notas Técnicas
- El sitio es **mobile-first** y está optimizado para cargar rápido.
- No requiere base de datos ni servidor (es un sitio estático de alto rendimiento).
- El formulario de reserva muestra un mensaje de éxito visual; si necesitas recibir los correos, puedes conectar el formulario a servicios gratuitos como [Formspree](https://formspree.io).
