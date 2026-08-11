# SØD V3.1.1 — Hub-native Conversation Oracle

- Replaced the SaaS-style `/experiencia` layout with the approved luminous SØD conversation interface.
- Conversation opens directly over the Hub from the central core or SØD portal.
- Uses remote background plate `https://i.imgur.com/6Mn5t2W.png`; no heavy local image added.
- Coded title, presence state, messages, timestamps, composer, send control and floating history tools.
- Hub panorama pauses behind the overlay and resumes without losing viewpoint.
- Preserved structured dialogue API and all Library/Videoteca functionality.

# SØD V3.1.0 — Hablar con SØD Continuous Conversation

- Replaced the rigid `/experiencia` transformation wizard with continuous conversation.
- Added premium SØD chat stream, responsive composer, visual presence states and retry UX.
- Added `clientMessageId` and future `conversationId`/Bearer compatibility.
- Added guest session controller using session-scoped storage only.
- Added future session-provider boundary for Supabase Auth.
- Removed automatic Semilla/Código mutation from the conversation path.
- Preserved Hub, Biblioteca, Videoteca, Semillas, Elementos 33, Observatorio and existing routes.
- Added targeted conversation integration tests.

# SØD V3.0.5 — Biblioteca/Videoteca cierre de etapa

- Videoteca reconstruida según referencia canónica.
- 2 carruseles compactos con 5 videos visibles en desktop.
- Miniaturas públicas de YouTube con fallback automático.
- Reproducción YouTube inline en la propia tarjeta, con fullscreen nativo.
- Categorías de video y búsqueda integrada.
- Carrusel compacto de canales esenciales.
- Libros y Videos son vistas mutuamente excluyentes.
- Biblioteca Libros V3.0.4.7 permanece intacta.
- Carruseles de libros conservan navegación anterior/siguiente.

# SØD V3.0.4.9 — Videoteca Exclusive Fix

## Correcciones
- Libros y Videos ahora son vistas mutuamente excluyentes.
- El modo Videos oculta completamente carruseles, autores y temas de Libros.
- Se eliminó la arquitectura de cinco filas de videos.
- Videoteca usa solo dos carruseles: Selección SØD y Profundizar.
- Categorías de video en una sola fila escaneable.
- Exponentes esenciales en un carrusel compacto con hipervínculos a sus canales.
- Reproducción inline: al pulsar una tarjeta, la miniatura se reemplaza por el reproductor oficial de YouTube.
- Fullscreen y controles nativos de YouTube disponibles dentro de la tarjeta.
- Fallback visual si una miniatura remota no puede cargar.
- Carruseles con botones anterior y siguiente.

## Curaduría actualizada
Se actualizaron enlaces concretos de Daily Stoic, Mel Robbins y Bernardo Kastrup, manteniendo la curaduría ya existente de Sadhguru, Huberman Lab, Tony Robbins, GaryVee, Chris Voss, Alex Hormozi, TED-Ed, Eternalised y HealthyGamerGG.

## Preservado
- Biblioteca de libros V3.0.4.7.
- Hub panorámico.
- Safe Browsing hotfix.
- Semillas, Códigos, Observatorio, Elementos 33 y resto del MVP.
