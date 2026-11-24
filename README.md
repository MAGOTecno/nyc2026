# NYC 2026 – Versión 5.1 (23 de noviembre de 2026)

Aplicación PWA para el repositorio `https://github.com/MAGOTecno/nyc2026` y el sitio `https://magotecno.github.io/nyc2026/`. Esta carpeta contiene **11 archivos públicos** para GitHub Pages. No requiere servidor ni base de datos. Todo se puede actualizar desde Safari en un iPhone.

## Cambios

- Respeta el respaldo privado `NYC2026-copia-v3(1).json` (20 actividades marcadas, 4 gastos registrados), y añade el tour **TopView** realizado el lunes, sin marcar como comprobado que desembarcaron en la Estatua o subieron al observatorio. Para esos dos puntos hay casillas de confirmación en **Más**.
- No repetir Downtown/11-S/Wall Street ni contratar otro bus de paradas libres; ya han hecho TopView y **Liberty Cruise panorámico**.
- **24/11**: selector «Washington reservado» (desactivado hasta tener voucher real). Al activar, plan con bus y guía; al desactivar, Museo de Historia Natural + Central Park bici/scooter por caminos Park Drives habilitados + mall Columbus Circle. Opciones de tours guiados en español enlazadas.
- **25/11**: si Washington se confirmó, museo/Parque, con descanso largo; si no, Hudson Yards, mall y High Line; **Knicks fijo 19:30** en MSG y llegada sugerida 18:15.
- **26/11**: desfile Thanksgiving y plan por lluvia, sin contar con comercios abiertos.
- **27/11**: Macy's Black Friday + **Victoria's Secret/PINK en 435 7th Ave** + compras/regalos, SoHo, Joe's Pizza y edificio de Friends si aún hay energía.
- **28/11**: opción Brooklyn + Katz's; ferry oficial con desembarque SOLO si no lo hicieron antes, activable desde **Más**. No paga otro tour TopView. Chelsea Market es opcional, no obligatorio.
- **29/11**: equipaje, LIRR/AirTrain, vuelo JFK 18:25.
- **177 frases** en múltiples categorías con audio en inglés, y diálogos específicos en actividades de Washington, tiendas, scooter, restaurante, ferry y fotos.
- Pronóstico en línea por el botón **Actualizar clima** usando Open-Meteo; actualización no cambia reservas por sí sola. Información almacenada localmente en el iPhone. El clima de referencia se revisó el 23/11.

## URGENTE: Washington mañana

No hay disponibilidad confirmada para 24/11; reserva solo al ver **2 adultos + fecha 24/11 + salida y guía en español** en la confirmación:

- https://www.viator.com/es-ES/tours/New-York/Washington-D-C-Tour-from-New-York/d5560-5614063P8 – Real's Tours, excursión acompañada en español, anuncio de grupo reducido.
- https://www.expedia.com/things-to-do/washington-d-c-day-trip-from-new-york.a184049.activity-details – Empire Vacations, anuncio de salida 06:30 desde 330 W 42nd St, cerca del New Yorker.
- https://excursionawashingtonenespanol.com/en/ – tour anunciado desde 7th Ave con W 51st St, consultar precio/cupos y cancelación.

**No comprar solo billetes de bus interurbano a Washington** ni tour hop-on/hop-off de Washington si quieres transporte entre monumentos con guía acompañante.

## Actualización del repositorio desde iPhone

1. En tu aplicación instalada pulsa **Más → Guardar copia JSON**. Es **privada**: solo en Archivos o iCloud privado, **nunca en GitHub**.
2. Descarga `NYC2026_v5_GitHub_Pages.zip` desde ChatGPT. Abre Archivos y pulsa el ZIP para descomprimir.
3. Safari → https://github.com/MAGOTecno/nyc2026 → `Add file` → `Upload files`. Si no ves opciones, usa «Solicitar sitio web de escritorio». Selecciona los **11 archivos sueltos** dentro de la carpeta descomprimida.
4. Deben quedar en la raíz junto a `index.html`, no dentro de una subcarpeta. Confirma **Commit changes**.
5. Espera 1–3 minutos, abre https://magotecno.github.io/nyc2026/ , toca **Más → Buscar actualización** y fuerza cierre/reapertura de la aplicación si ves recursos antiguos. La versión visible es **5.0**.
6. Revisa **Más** y confirma si Washington está reservado y si ya desembarcaron en Liberty Island. El plan se adapta automáticamente.
7. Comprueba las marcas y 4 gastos. Si faltan, usa **Más → Restaurar copia anterior** y selecciona el JSON PRIVADO v5 o tu respaldo reciente v3; la aplicación lo adapta.

La migración usa la clave `nyc2026-v1` (mismo origen de las versiones anteriores) y mantiene marcas/gastos. Los horarios personalizados se conservan solo cuando difieren del diseño previo; la nueva versión reordena las actividades predeterminadas. Guarda respaldo antes.

## Calendario

Incluimos ICS de itinerario base **sin Washington confirmado**. Para generar alertas correctas del plan que elijas: marca si reservaste Washington y si necesitas ferry, luego entra a **Más → Alertas y calendario** y exporta **Alertas esenciales**. Importa el nuevo calendario en Apple y elimina el anterior si estaba importado (así evitas avisos duplicados). La PWA sola no envía alertas con la aplicación cerrada.

## Nota sobre el ferry y la bicicleta/scooter

Una foto o visita panorámica desde TopView **no equivale a desembarcar** en Liberty Island ni entrar al mirador One World. Si ya desembarcaron, activa esa casilla y el ferry se oculta; si desean la visita y no la hicieron, activa «Ruta ferry oficial». Scooter eléctrico: solamente en vías autorizadas (`Park Drives`) y sujeto a reglas de NYC Parks; **no** utilizar por senderos ni veredas. Recomendamos bici tradicional para viajar tranquilos.

## Privacidad

El repositorio GitHub es público. El ZIP solo contiene código, itinerario genérico e íconos. Tu progreso y los gastos NO van dentro del ZIP, ni se comparten con GitHub. Los archivos privados JSON deben quedarse en tu iPhone.

## Actualización Liberty Cruise (v5.1)

El viaje panorámico **Liberty Cruise** ya fue realizado: vieron la Estatua de la Libertad desde el barco, sin confirmación de desembarque en la isla. La ruta del sábado recomienda Brooklyn y Katz’s y mantiene el ferry oficial a Liberty Island como **alternativa opcional**, solo si quieren desembarcar. Los datos privados siguen exclusivamente en el teléfono.

**Nota para actualización desde la versión 3:** La primera apertura migrará las marcas de actividades y gastos del teléfono y registrará Liberty Cruise como completado. No hará falta importar un JSON de respaldo si el iPhone mantiene su almacenamiento. El archivo ZIP no incluye gastos personales.
