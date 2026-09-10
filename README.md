# Mapa de Conexión CIEACE 2026

Visualización interactiva en HTML/SVG puro que representa la red de países participantes del **IX Congreso Internacional CIEACE 2026**, con Colombia como país anfitrión.

## Descripción

Un mapa estilizado de Latinoamérica donde cada país participante es un nodo clickeable. Al interactuar con cada uno, se traza una línea de conexión hacia Colombia y aparece su nombre con una tipografía acorde a la identidad visual del evento. Al conectar todos los países, se revela el logo del congreso.

## Países participantes

México · República Dominicana · Ecuador · Perú · Bolivia · Chile · Brasil · Argentina

## Características

- **100% autocontenido**: un único archivo `.html` sin dependencias externas (incluye el logo embebido en base64).
- **Interacción por clic/touch**: cada país se conecta individualmente al ser seleccionado.
- **Progreso visible**: contador dinámico de países conectados (`x / 8`).
- **Revelado final**: al completar todas las conexiones, se atenúa el mapa y aparece el logo del evento.
- **Accesible**: nodos navegables por teclado (`Tab` + `Enter`/`Espacio`).
- **Reinicio rápido**: tecla `R` para reiniciar la demo.
- **Responsive**: escala mediante `viewBox` de SVG, ideal para pantallas/proyección.

## Tecnologías

- HTML5 + CSS3 (variables CSS, animaciones, transiciones)
- SVG para el mapa, nodos y líneas de conexión
- JavaScript vanilla (sin frameworks ni librerías)

## Uso

Solo abre `mapa_conexion_cieace.html` en cualquier navegador moderno. No requiere build ni servidor.

## Controles

| Acción | Resultado |
|---|---|
| Clic/touch en un país | Conecta ese país con Colombia y muestra su nombre |
| Todos los países conectados | Revela el logo del congreso |
| Tecla `R` | Reinicia la animación |
