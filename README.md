# ByteMind Solutions — ATLAS GENESIS · Swarm Live

Sitio oficial de ByteMind Solutions, basado en Next Generation V1.2. El diseño original, el fondo Network azul neón, las secciones y las interacciones se conservan.

## Experiencia ATLAS GENESIS

La primera visita abre un portal de neón azul con ATLAS y cursores orbitales. Después, 12 cursores coreografiados dibujan y van mostrando 36 bloques **de la propia web** mientras un editor enseña fragmentos de código ilustrativos. La web queda navegable al terminar.

- **Ver la web:** https://zeroartlord.github.io/bytemind-web/
- **Forzar la introducción:** https://zeroartlord.github.io/bytemind-web/?swarm=1
- **Entrar directamente sin introducción:** https://zeroartlord.github.io/bytemind-web/?noswarm=1
- **Repetir:** botón **ATLAS GENESIS ↻** abajo a la derecha

### Controles durante la presentación
- Espacio: pausar / continuar
- Tecla R: reiniciar
- Tecla S o Esc: saltar
- Tecla H: ocultar / mostrar controles para grabar
- Teclas 1, 2, 3: velocidad de la presentación
- Botones en pantalla para todas las funciones principales

En móviles se reduce el número de cursores simultáneos. La animación puede omitirse y respeta la preferencia de movimiento reducido. No se utilizan librerías de terceros.

**Transparencia:** son agentes y pasos *simulados* mediante coreografía de JavaScript en el navegador; no hay agentes de IA programando ni compilación en vivo. El editor muestra ejemplos visuales sincronizados con los componentes originales.

**Copia de seguridad de la versión anterior:** rama `backup/pre-atlas-genesis-v1.2`.

**Mantenimiento:** esta publicación incluye en `index.html` un cargador sin dependencias con los módulos de la experiencia incorporados. Los archivos originales editables `swarm-genesis.js` y `swarm-genesis.css` están en el paquete de código fuente de ATLAS GENESIS.


## ATLAS GENESIS SWARM V3 — noviembre de 2026

- 24 cursores en escritorio y 12 en móvil; coreografía acelerada de navegación, diseño, trazado de marcos y escritura letra por letra.
- Cada unidad visible de la página se construye por grupos de agentes; la cámara recorre las secciones para evitar que aparezcan completas sin intervención.
- Al terminar, todos los cursores forman una espiral neón y regresan al ATLAS CORE integrado en la portada.
- El HTML publicado es autónomo y no necesita Node.js, compilación ni rutas a módulos externos.
- Pruebas Chromium: 36 bloques completados; más de 770 palabras animadas; pausa, salto, repetición y visualización móvil funcionales.
- Respaldos: `backup/atlas-genesis-v2-before-v3` (versión inmediata anterior) y `backup/pre-atlas-genesis-v1.2`.

**Uso:** visita `?swarm=1` para forzar la animación o `?noswarm=1` para omitirla. R reinicia; H oculta controles; espacio pausa; 1, 2 y 3 ajustan la velocidad; S salta.

**Aviso:** el editor y los agentes muestran una simulación visual coreografiada, no compilación ni agentes de IA reales.


## ATLAS GENESIS V3.1 — ritmo equilibrado y agentes activos

- Ajustes para que el recorrido y la escritura se vean con claridad, sin perder el trabajo simultáneo.
- Los agentes solo son visibles mientras ejecutan una tarea: eliminados los movimientos aleatorios de relleno y los cursores residuales.
- Se mantiene el equipo de 24 cursores disponibles en escritorio y 12 en móvil, con asignación a marcos y escritura letra por letra.
- El HUD muestra cuántos agentes están trabajando realmente.
- Portal neón y regreso en espiral al ATLAS CORE preservados.
- Pruebas en Chromium: 36 bloques completados, más de 750 palabras animadas, sin errores JS y sin cursores inactivos visibles.

Acceso directo a esta edición: https://zeroartlord.github.io/bytemind-web/?swarm=1&v=31 . Velocidades: 1×, 1.5×, 2×; R reinicia; S salta; H oculta controles.


## V3.2 — Velocidad 1× real (2026-11-05)

Se corrigió el multiplicador oculto de la animación: el reloj ya no ejecuta 2.6× cuando el control indica 1×. Conservar la coreografía original, escritura letra a letra, cursores activos, portal de neón y espiral final. En modo predeterminado el reloj avanza en tiempo real según los fotogramas del navegador. Opcional: 1 / 2 / 3 para elegir 1×, 1.5× o 2×.

Inicio directo: https://zeroartlord.github.io/bytemind-web/?swarm=1&v=32
Respaldo anterior: `backup/atlas-genesis-v3-1-normal-speed`.
