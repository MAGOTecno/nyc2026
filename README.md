# NYC 2026 – Nuestro viaje · versión 3.0

Web-app instalable para GitHub Pages: <https://magotecno.github.io/nyc2026/> · código fuente en <https://github.com/MAGOTecno/nyc2026>.

## Novedades de la versión 3

- **8 nuevas actividades icónicas** agrupadas por sectores para evitar desvíos largos: Central Perk (domingo), árbol de Rockefeller/FAO Schwarz/Radio City (lunes), puente Gapstow/The Plaza (miércoles), Joe's Pizza/Friends (viernes) y cena Katz's (sábado; se actualiza la cena existente). Son 70 actividades en total, incluidas opciones.
- En cada tarjeta encontrarás **etiquetas culturales** («🎬 Mi pobre angelito 2», «📺 Friends», «🕷️ Spider-Man 2»), una frase corta que explica por qué es famosa, botón **Más detalles**, precios o advertencias y rutas con metro o caminata.
- En **Plan → 🎬 Ver solo lugares famosos** puedes filtrar las paradas temáticas de cada día.
- El **diccionario** agrega frases para fotos, restaurantes y lugares de cine y ofrece frases específicas en el detalle de los nuevos lugares.
- Se conservan el clima en línea, el itinerario editable, el checklist, el presupuesto, modo sin conexión, mapas y exportación de alertas del calendario.

### Importante: lugares ficticios vs. reales

- **Central Perk**: el café que aparece en *Friends* era un set de televisión en Los Ángeles. **Sí existe ahora un Central Perk Coffeehouse oficial en Times Square**, 20 Times Square (7th Ave / W 47th), abierto todos los días 08:00–23:00 según el sitio oficial. https://centralperk.com/pages/new-york-city-store-location
- **Edificio Friends**: la fachada exterior está en 90 Bedford St / Grove St; es un edificio privado y no se puede visitar por dentro.
- **Joe's Pizza**: la película *Spider-Man 2* utilizó el antiguo local en 233 Bleecker St / Carmine; el restaurante ahora está a unos metros, en 7 Carmine St. https://fd28ddd581db4c328a3c8a521586cb4b.web.ordersave.com/greenwich-village
- **Duncan's Toy Chest**: es una juguetería **ficticia**, inspirada en FAO Schwarz. Las escenas de la tienda se grabaron en Chicago. La actual **FAO Schwarz** real está en 30 Rockefeller Plaza y se visita gratuitamente. https://www.rockefellercenter.com/shops/fao-schwarz/
- **Árbol de Rockefeller**: estará instalado pero **no encendido** durante las fechas del viaje. La iluminación oficial será el **2 de diciembre de 2026**. https://www.rockefellercenter.com/holidays/
- **The Plaza y puente Gapstow**: son locaciones reales de *Mi pobre angelito 2*, a las que pueden ir el miércoles durante el paseo de Central Park.
- **Katz's**: 205 East Houston St, célebre por el pastrami y por la película *Cuando Harry conoció a Sally*. Un sándwich de pastrami ronda USD 30 (confirmar carta). Visita opcional como cena del sábado; si están cansados pueden cenar en el hotel.
- **Radio City Music Hall**: célebre por su marquesina Art Decó, Rockettes y espectáculos navideños. La foto exterior es gratuita; los espectáculos requieren entrada.

## Actualizar GitHub Pages desde iPhone o computador

**Antes de comenzar: en la aplicación vieja, entra a Más → Guardar copia JSON** para respaldar checklist, gastos y horarios personalizados.

1. Descarga `NYC2026_v3_GitHub_Pages.zip` y descomprímelo en la aplicación **Archivos** del iPhone, o en el computador.
2. Abre <https://github.com/MAGOTecno/nyc2026> en Safari o navegador de escritorio, iniciando sesión en GitHub.
3. Selecciona **Add file → Upload files**. En Safari del iPhone, si no aparece la opción, elige **Solicitar sitio web de escritorio**.
4. Selecciona **los 11 archivos del interior de la carpeta descomprimida** (no subas el ZIP ni la carpeta como subcarpeta). Deben reemplazar los actuales en la **raíz** del repositorio, particularmente `index.html`, `app.js`, `data.js`, `style.css`, `sw.js` y los archivos de calendario. Haz **Commit changes**.
5. Si Pages ya está habilitado, **no cambies** la configuración. Espera unos minutos a que GitHub termine el despliegue. Si hace falta, comprueba **Actions**.
6. Abre <https://magotecno.github.io/nyc2026/> en Safari. Desde la aplicación pulsa **Más → Buscar actualización**, luego ciérrala completamente y vuelve a abrir. Si la pantalla sigue en caché, espera un poco y prueba abrir la URL desde Safari.
7. Busca **Plan → Lun 23 → FAO Schwarz** y comprueba que aparece la etiqueta **Mi pobre angelito 2**. La etiqueta confirma la versión 3.

No necesitas computadora. Para subir 11 archivos, sin embargo, el computador suele ser más cómodo. GitHub Pages gratis requiere un repositorio público: no subas pasaportes, números bancarios ni los QR de tus entradas.

## Checklist, gastos y calendarios

Los datos se guardan con la misma clave local que usaba v2. La versión 3 **preserva los checklist y gastos locales** y agrega las nuevas actividades. Cuando una actividad existente cambió de hora o nombre, v3 solo actualiza los campos que siguen exactamente iguales a los originales de v2; si modificaste un campo personalmente, trata de respetarlo. **Exportar copia JSON antes de actualizar es muy recomendable.**

Si importaste el calendario de v2, elimínalo antes de importar el nuevo para evitar duplicados. Incluimos dos archivos `.ics`: uno con 70 actividades y otro con 13 recordatorios esenciales. Todos utilizan hora de Nueva York y aviso 30 minutos antes. En la pestaña **Más** puedes volver a exportarlos según tus modificaciones.

**Las alertas de una web app estática no se pueden garantizar cuando está cerrada:** para ello utiliza Calendario de Apple con los `.ics`. Los datos no se sincronizan automáticamente entre teléfonos; el clima y los mapas requieren internet, pero el itinerario puede abrir sin conexión tras instalar la app y abrirla en línea al menos una vez.

## Fuentes de ubicaciones consultadas el 21/11/2026

- Central Perk oficial: https://centralperk.com/pages/new-york-city-store-location
- Friends, fachada: https://www.lonelyplanet.com/articles/friends-nyc-itinerary
- Joe's Pizza oficial: https://fd28ddd581db4c328a3c8a521586cb4b.web.ordersave.com/greenwich-village
- Katz's oficial: https://katzsdelicatessen.com/
- Plaza Hotel (filmografía): https://www.theplazany.com/history/faces-films-moments/
- Central Park Conservancy (puente Gapstow): https://www.centralparknyc.org/articles/movies-in-central-park-our-favorite-park-locations-made-famous-on-film
- Rockefeller Center, árbol y fecha de encendido: https://www.rockefellercenter.com/holidays/
- FAO Schwarz: https://www.rockefellercenter.com/shops/fao-schwarz/

**Archivos para subir**: `index.html`, `app.js`, `data.js`, `style.css`, `manifest.webmanifest`, `sw.js`, `icon-192.png`, `icon-512.png`, `NYC2026.ics`, `NYC2026-alertas-esenciales.ics`, `README.md`.
