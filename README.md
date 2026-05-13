# ScaleUp Landing Page

Pagina web estatica para ScaleUp Marketing Agency, enfocada en vender soluciones de CRM, automatizaciones, chatbots y marketing orientado a conversion.

## Archivos del proyecto

- `index.html`: estructura principal de la pagina.
- `styles.css`: estilos visuales, responsive design y apariencia general.
- `script.js`: menu movil y funcionamiento del formulario.
- `assets/scaleup-logo.jpg`: logo usado en la pagina.

## Como abrir la pagina

1. Abre la carpeta del proyecto en Visual Studio Code.
2. Abre el archivo `index.html`.
3. Haz clic derecho y selecciona `Open with Live Server` si tienes esa extension instalada.

Tambien puedes abrir `index.html` directamente con doble clic desde el explorador de archivos.

## Funcionalidad del formulario

El formulario no usa backend ni base de datos. Cuando el usuario completa los campos:

- El boton `Enviar por WhatsApp` abre WhatsApp con el mensaje ya preparado.
- El boton `Enviar por correo` abre el cliente de correo con el asunto y mensaje preparados.

Datos configurados actualmente:

- Telefono: `3001790488`
- WhatsApp internacional: `573001790488`
- Correo: `scaleup235@gmail.com`

## Como cambiar los datos de contacto

En `index.html`, busca:

```html
300 179 0488
scaleup235@gmail.com
https://wa.me/573001790488
```

En `script.js`, cambia estas constantes:

```js
const phoneNumber = "573001790488";
const emailAddress = "scaleup235@gmail.com";
```

## Como cambiar el logo

Reemplaza el archivo:

```text
assets/scaleup-logo.jpg
```

por otra imagen con el mismo nombre. Si usas otro nombre, actualiza las rutas en `index.html`.

## Secciones incluidas

- Inicio con propuesta de valor.
- Servicios principales.
- Explicacion de CRM.
- Diferenciadores de ScaleUp.
- Proceso de trabajo.
- Casos de uso.
- Formulario para agendar asesoria.
- Footer con contacto.

## Recomendacion importante

Esta pagina ya funciona como landing estatica. Si quieres recibir los formularios en una base de datos, CRM o correo automatico sin que el usuario abra WhatsApp, necesitas conectar un backend o un servicio externo como Formspree, Make, Zapier, Google Sheets o una API propia.
