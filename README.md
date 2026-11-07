# Landing Page — Dr. Carlos Palma Marín

Página web del Dr. Carlos Palma Marín para Tehuacán: "Tehuacán merece vivir en paz".

## Qué contiene

- **Hero** con el video oficial (33 segundos) y el botón "Súmate al cambio".
- **Sección "Hablemos de paz"** con los valores (tranquilidad, comunidad, acuerdos reales, liderazgo) y los tres pilares: familia, calles seguras y comunidad que se escucha.
- **Formulario de registro** con nombre completo, WhatsApp y correo opcional.
- **Pie** con enlaces a las páginas oficiales de Facebook del doctor y del Partido PAZ, el lema de PAZ y el aviso de privacidad.

## Cómo funciona el formulario

Esta es una página estática: **no hay servidor ni base de datos**.

Al enviar el formulario, la página arma un mensaje con los datos de la persona y muestra un botón verde **"Enviar mis datos por WhatsApp"**. Ese botón abre WhatsApp con el mensaje ya redactado, dirigido al número **221 198 3184**, por ejemplo:

> Hola, [nombre] está interesado en sumarse al movimiento por la paz de Tehuacán. WhatsApp: [número]

La persona tiene que tocar el botón y luego tocar enviar dentro de WhatsApp. Si no lo hace, el mensaje no llega: una página web no puede mandar un WhatsApp por sí sola.

## Cómo publicarla con GitHub Pages

1. Crea un repositorio nuevo en GitHub (por ejemplo `sumate-carlos-palma`) y sube todos los archivos de esta carpeta (`index.html`, `README.md` y la carpeta `assets/` con el video y los logos).
2. En GitHub, entra a **Settings > Pages**.
3. En **Build and deployment**, elige **Deploy from a branch**, rama **main** (o `master`, según se llame) y carpeta **/ (root)**. Guarda.
4. GitHub te dará la dirección, algo como `https://tu-usuario.github.io/sumate-carlos-palma/`. Tarda unos minutos en activarse.
5. Si compras un dominio propio (por ejemplo `sumatecarlospalma.mx`), apúntalo a GitHub Pages desde **Settings > Pages > Custom domain** y sigue las instrucciones de DNS que muestra GitHub.

## Archivos

- `index.html` — la página completa (estilos y lógica del formulario incluidos).
- `assets/video-oficial-dr-carlos-palma-v3.mp4` — video oficial (33 s).
- `assets/poster-video.jpg` — miniatura del video (plaza de Tehuacán).
- `assets/logo-paz-oficial.jpg` — logotipo oficial de Partido PAZ (usar entero, sin recortar, deformar ni cambiar de color).
- `assets/logo-carlos-palma-hablemos-de-paz.jpg` — logotipo "Carlos Palma — Hablemos de Paz".

## Notas

- Los logos se usan enteros, solo con cambio de tamaño proporcional.
- La página es difusión de paz y comunidad.
- El aviso de privacidad está en el pie de la página: los datos solo se usan para contactar a la persona sobre sumarse al movimiento.
