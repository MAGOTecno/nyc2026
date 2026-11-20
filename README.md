# NYC 2026 — Nuestro viaje · Versión 2.0

Aplicación web instalable (PWA) y totalmente estática para [GitHub Pages](https://github.com/MAGOTecno/nyc2026).

## Publicar o actualizar en GitHub

Repositorio: https://github.com/MAGOTecno/nyc2026
URL publicada esperada: https://magotecno.github.io/nyc2026/

**Desde iPhone, sin computador:**

1. Descarga `NYC2026_v2_GitHub_Pages.zip` al iPhone (app **Archivos** → **Descargas**).
2. En **Archivos**, toca el ZIP una vez para descomprimirlo. Abre la carpeta resultante (verás `index.html`, `app.js`, etc.).
3. Abre **Safari** y entra a https://github.com/MAGOTecno/nyc2026 (inicia sesión). Si hace falta, elige «Solicitar sitio web de escritorio» en las opciones de Safari.
4. En el repositorio pulsa **Add file → Upload files**. Pulsa **choose your files** y en **Archivos** selecciona **los archivos interiores** de la carpeta descomprimida (no subas solamente el ZIP). Selecciona varios si aparece la opción; de lo contrario súbelos por tandas. Confirma **Commit changes**. Si ya existen archivos con el mismo nombre, súbelos al mismo directorio raíz y confirma la sustitución.
5. En **Settings → Pages**, verificar que Source sea `Deploy from a branch`, Branch `main`, Carpeta `/(root)`. Si GitHub Pages ya estaba habilitado **no hace falta activarlo de nuevo**.
6. Espera a que termine el despliegue (en **Actions** aparece el estado). Abre https://magotecno.github.io/nyc2026/ . Si sigue apareciendo v1, cierra la app, vuelve a entrar con conexión, en la pestaña **Más** pulsa «Buscar actualización», y vuelve a abrir.

**Desde computador:** Descomprime el ZIP, entra al repositorio en la web, **Add file → Upload files**, arrastra los archivos nuevos al directorio raíz, confirma el commit. Es más cómodo que hacerlo con el teléfono, pero **no es obligatorio**.

Nota: si la cuenta no permite subir varios archivos desde Safari, la alternativa sencilla es actualizar desde computador. Evita subir una carpeta `nyc2026_v2` dentro del repositorio: `index.html` debe estar en la **raíz**.

## Novedades v2

- **Actualizar clima:** consulta en tiempo real el servicio gratuito Open-Meteo, sin clave de API, por HTTPS. Requiere internet. Presenta máxima probabilidad de precipitación y riesgo aproximado por mañana/tarde/noche; el cálculo varía según el proveedor y **no equivale a una alerta oficial**. Si no hay red, muestra último pronóstico almacenado o referencia del 20/11/2026.
- **Itinerario corregido:** el domingo 22 (lluvia intensa a partir de la tarde) Times Square es breve y temprano; se agrega visita nocturna el lunes 23. Museo Americano de Historia Natural, que inspiró «Night at the Museum», lunes 23. Central Park + Knicks miércoles 25. Estatua/One World sábado 28 si permiten el clima, y domingo 29 sin paseos obligatorios por previsión de lluvia. Otras reservas y fechas fijas no se mueven automáticamente.
- **Más detalles en cada actividad:** qué es, trayecto explicado, recomendación de ruta y 3 frases de inglés de esa situación. Los mapas externos se abren en Google Maps; las líneas y la frecuencia deben verificarse en MTA.
- **Inglés:** 53 frases, buscador y reproducción de voz local del navegador (puede variar según voces instaladas).
- **Mirador:** One World Observatory, opcional, desde USD 39 por adulto más cargos/impuestos. Presupuesto USD 95 para dos, puedes incluir/excluir el mirador en **Gastos**. Alternativa gratis: DUMBO/puente Brooklyn; alternativa clásica: Top of the Rock (otro precio).
- **Alertas:** calendario completo (`NYC2026.ics`) o calendario solo de eventos esenciales (`NYC2026-alertas-esenciales.ics`), avisos con anticipación de 30 min, horario `America/New_York`.

## Atención: calendario y alertas

- Una PWA publicada en GitHub Pages **no puede emitir alertas fiables cuando está completamente cerrada** sin backend/push. Los `.ics` agregan alarmas al calendario del teléfono. Importa el que prefieras en un calendario separado para identificarlo y eliminarlo fácilmente.
- Si ya importaste `NYC2026.ics` de la versión anterior, **borra el calendario anterior antes de importar v2**, porque los recordatorios podrían duplicarse. En la pestaña **Más** puedes exportar las citas según los horarios que edites.
- Importa `.ics` desde una app compatible de calendario; en iPhone, dependiendo del sistema, puede resultar más fácil agregarlo en un calendario de iCloud desde Mac, Calendario web compatible o enviar por correo y abrir archivo. Verifica una alarma.

## Privacidad y conservación de datos

- Los archivos que subes al repositorio público muestran itinerario y hotel. **NO** subas números de pasaporte, credenciales ni códigos QR.
- Los gastos, checklist, cambios y previsión se guardan **localmente en el navegador del iPhone**. No se sincronizan con otros teléfonos y pueden perderse si se borran datos de Safari, se usa otro navegador o cambia la URL.
- Actualizar el código en la **misma URL** no debería borrar los gastos. La aplicación migra los marcados/compras de v1 a v2 y guarda una copia local `nyc2026-v1-before-upgrade`. **El itinerario base de v1 se reemplaza por el nuevo plan y los horarios personalizados anteriores no se trasladan automáticamente**. Si habías editado muchos horarios, exporta copia JSON desde **Más** antes de actualizar.
- En v2, nuevos cambios se conservan tras reemplazar los archivos en el servidor.

## Fuentes de precios y observaciones (consulta 20/11/2026)

- Museo Americano de Historia Natural: https://www.amnh.org/plan-your-visit — entrada general **USD 37 adulto no residente NY**, USD 74 para dos; cerrado el jueves de Thanksgiving. Recorrido de la película: https://www.amnh.org/plan-your-visit/tours/night-museum-exhibits
- One World Observatory: https://www.oneworldobservatory.com/es/buy-tickets/ — **desde USD 39 por adulto + USD 3.50 de gestión + impuestos**; precio final y disponibilidad sujetos a fecha/hora.
- Ferry oficial: https://www.cityexperiences.com/new-york/city-cruises/statue/ — revisar tarifa y horario antes de pagar.
- Alerta meteorológica ciudad: https://www.nyc.gov/site/em/about/pr_20261120_NYCEM-Issues-Weather-Alert-Windy-Soaking-Rain-Sunday-To-Monday.page
- Clima dinámico: https://open-meteo.com/ — información orientativa, no sustituye fuentes oficiales de alertas.

## Qué contiene el paquete

`index.html`, `style.css`, `data.js`, `app.js`, `manifest.webmanifest`, `sw.js`, iconos PNG, ambos calendarios `.ics` y este `README.md`.

Para instalar en iPhone: en Safari abre la URL y elige **Compartir → Agregar a pantalla de inicio**. Deja cargar la aplicación online al menos una vez, luego el itinerario puede abrir sin conexión; pronóstico nuevo, mapas y enlaces externos necesitan Internet.
