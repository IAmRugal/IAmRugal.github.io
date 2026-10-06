# Contexto del proyecto

Archivo para retomar el trabajo en cualquier momento (también sirve para dárselo a Claude en una conversación nueva).

## Origen

- Creada en octubre de 2026 con Claude, a partir de la hoja de vida `HV_William_Ruiz_Morales_GCIR.docx`.
- Intereses personales indicados por William: running, montaña, videojuegos y fotografía.
- Cuenta de GitHub: `IAmRugal` · URL: https://iamrugal.github.io

## Decisiones de diseño

- **Concepto:** mapa topográfico. El encabezado tiene curvas de nivel dibujadas en un `<canvas>` (cada quinta curva más gruesa, como en los mapas reales) y la trayectoria se presenta como una ruta con puntos de control. Une la montaña con el "camino" profesional. Al pasar el cursor (o tocar en el celular) las curvas se ondulan como agua: oleaje suave más ondas que se expanden desde el cursor. Se desactiva si el sistema pide reducir movimiento.
- **Colores:** fondo gris verdoso claro, tinta verde pino, acento azul (`#1f5fa8`, mismo tono del aro de la foto de la HV) y verde musgo para la sección de intereses. Modo oscuro automático según el sistema, más un botón (luna/sol) en la barra superior para cambiarlo; la elección se recuerda en el navegador (`localStorage`, clave `tema`).
- **Tipografías (Google Fonts):** Bricolage Grotesque (títulos), Public Sans (texto), JetBrains Mono (etiquetas, fechas, coordenadas).
- **Detalles propios:** unidades de cada interés (min/km, m s.n.m., f/8 · 1/250 s · ISO 100).
- **Encabezado:** los roles (Ingeniero de requerimientos · Gestor del cambio · Ingeniero de datos) pasan como un aviso en movimiento (marquesina en CSS; se detiene al pasar el cursor). Debajo del párrafo: solo "Bogotá D.C., Colombia" e idiomas (sin altitud ni coordenadas, por decisión de William).
- **Redacción:** usar "elaborar requerimientos", no "levantar".
- **Trayectoria:** no incluye la experiencia HSE/SISOMA (decisión de William); se mantiene la certificación de Auditor HSEQ en Formación.
- **Todo en un archivo:** `index.html` contiene HTML, CSS y JS; la foto está en `assets/foto.jpg`.

## Privacidad

- **No se publica el teléfono.** Solo correo (con botón "Copiar") y ciudad.
- El correo publicado es `williamruizm10@hotmail.com`. Considerar cambiarlo por un formulario si llega spam.

## Contenido a validar por William

- Los textos de la sección de intereses son genéricos (redactados por Claude). Reemplazar con experiencias reales.
- El portafolio solo usa logros que aparecen en la HV; agregar cifras o resultados concretos si los hay.

## Pendientes / ideas

- [ ] Galería de fotografía (las tarjetas de intereses ya rotan fotos propias; falta una galería ampliable)
- [ ] Reescribir textos de Running, Montaña y Videojuegos con experiencias reales (maratón 42K, nevados, etc.)
- [ ] Confirmar permiso de la persona que aparece en la selfie de Running (`assets/running-4.jpg`)
- [ ] Enlace a LinkedIn
- [ ] Versión en inglés
- [ ] Dominio propio (opcional, ~USD 10–15/año)
- [ ] Subir proyectos de bases de datos (Esp. Jorge Tadeo Lozano) como portafolio técnico

## Historial

- **2026-10-05** · Versión 1 publicada: perfil, trayectoria, portafolio (5 proyectos), formación, intereses y contacto.
- **2026-10-06** · Botón de modo claro/oscuro y efecto de agua en las curvas de nivel del encabezado.
- **2026-10-06** · Roles en marquesina (se agrega Ingeniero de datos), ubicación simplificada, "levantar" → "elaborar", se quita HSE/SISOMA y se reescribe el caso SGDEA SuperArgo (Supersalud).
- **2026-10-06** · Competencias depuradas (+ Administración de bases de datos, Análisis de datos). Fotos propias en las cuatro tarjetas de intereses, con rotación suave (Running 4, Montaña 3, Videojuegos 1, Fotografía 4).
