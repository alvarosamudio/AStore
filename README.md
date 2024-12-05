## Plantilla para una Tienda de Aplicaciones Comunitarias en Umbrel

Este repositorio es una plantilla para crear una Tienda de Aplicaciones Comunitarias en Umbrel. Estas tiendas adicionales permiten a los desarrolladores distribuir aplicaciones sin necesidad de enviarlas a la [Tienda Oficial de Aplicaciones de Umbrel](https://github.com/getumbrel/umbrel-apps).

---

## Cómo utilizar:

1. Comienza haciendo clic en el botón "Use this template" ubicado en la parte superior.
2. Asigna un ID y un nombre a tu tienda de aplicaciones en el archivo `umbrel-app-store.yml`. Este archivo especifica dos atributos importantes:
   - **`id`**: Actúa como un prefijo único para cada aplicación dentro de tu Tienda de Aplicaciones Comunitarias. Debes iniciar el ID de tu aplicación con el ID de tu tienda de aplicaciones. Por ejemplo, en esta plantilla, el ID de la tienda es `sparkles` y hay una aplicación llamada `hello world`. Por lo tanto, el ID de la aplicación debe ser: `sparkles-hello-world`.
   - **`name`**: Es el nombre de la Tienda de Aplicaciones Comunitarias que se muestra en la interfaz de Umbrel OS.
3. Cambia el nombre de la carpeta `sparkles-hello-world` para que coincida con el ID de tu aplicación. El ID de la aplicación lo decides tú. Por ejemplo, si el ID de tu tienda es `whistles` y tu aplicación se llama My Video Downloader, podrías asignarle el ID `whistles-my-video-downloader` y renombrar la carpeta en consecuencia.
4. Luego, introduce los detalles de tu aplicación en el archivo `whistles-my-video-downloader/umbrel-app.yml`. Estos detalles se mostrarán en la interfaz de Umbrel OS.
5. Incluye los servicios Docker necesarios en `whistles-my-video-downloader/docker-compose.yml`.
6. ¡Eso es todo! Tu Tienda de Aplicaciones Comunitarias, con tu aplicación única, está configurada y lista para usarse. Para utilizar tu Tienda de Aplicaciones Comunitarias, puedes añadir su URL de GitHub en la interfaz de usuario de Umbrel OS como se muestra en la siguiente demostración:

--- 

https://user-images.githubusercontent.com/10330103/197889452-e5cd7e96-3233-4a09-b475-94b754adc7a3.mp4
