# Google Reviews

Herramientas para conseguir más reseñas en Google.

**Sitio:** https://isaackiux.github.io/GoogleReviews/

## Páginas

- **`index.html`: generador.** Pega el link de un negocio en Google Maps, elige si mandas a tus clientes a la página custom o directo a Google, y obtienes:
  - el link de la página para clientes, con el nombre del negocio y 5 estrellas marcadas
  - el link directo al formulario de reseña de Google
  - un código QR y un mensaje listo para WhatsApp
- **`califica.html`: página para clientes.** Muestra el negocio, las estrellas y comentarios rápidos, y lleva al cliente a Google para publicar.

## Notas

- Acepta links largos y cortos (`maps.app.goo.gl`). Los cortos se abren a través de servicios públicos de proxy (allorigins, corsproxy, codetabs); si ninguno responde, la página muestra cómo copiar el link largo a mano.
- El negocio viaja en el link (`califica.html#<PlaceID>~<nombre>`), así que no hace falta servidor ni base de datos.
- Google no acepta una calificación desde fuera de su formulario. El cliente confirma las estrellas en Google, y la página le indica cuáles tocar.
