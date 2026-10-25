# 🧩 Funciones y compatibilidad / Features & compatibility

> **SYNCORE Games** · [Inicio / Home](../../README.md) · [Descarga / Download](https://github.com/IMC93Labs/Syncore-Releases/releases/latest) · [Primeros pasos / Quick start](quick-start.md) · [Funciones / Features](features.md) · [Ayuda / Support](../../SUPPORT.md)

**Idioma / Language:** [Español](#español) · [English](#english)

---

## Español

SYNCORE reúne varias herramientas en una única aplicación Windows. **Disponible**, **opcional**, **experimental** y **pendiente** no significan lo mismo: aquí se indican claramente.

| Área | Estado en la versión 2.2.2 | Qué debes saber |
|---|---|---|
| 🎮 Biblioteca / Modo PC | **Disponible** | Cuadrícula y lista, búsqueda, filtros, favoritos, carátulas, fondos y opciones de juegos. |
| 🕹️ Modo Consola | **Disponible** | Navegación con mando; al volver del juego, se puede navegar mientras se verifican las partidas en segundo plano. |
| 🎛️ Control Center sobre el juego | **Disponible según equipo/permisos** | Guide abre el panel; energía y prioridad reflejan estados reales solo cuando Windows permite consultarlos o modificarlos. |
| 💾 Protección de partidas | **Disponible con configuración** | Copias verificadas, historial y recuperación controlada. Necesita identificar bien las carpetas y NTFS cuando se utilizan junctions. |
| ☁️ Google Drive | **Opcional** | Sincronización y recuperación verificadas, reintentos y conflictos que requieren decisión. Requiere tu propia configuración OAuth, conectividad y autorización. |
| 📊 PresentMon / OSD | **Condicionado** | FPS y frametime en juegos/renderizadores compatibles y con permisos necesarios. Mide eventos Present, no certifica fotogramas finales generados. |
| 🌡️ Telemetría | **Condicionado** | Carga de CPU/GPU, temperaturas y RAM/VRAM si hay sensores/lecturas válidas. Control Center puede mostrar lecturas sin juego. |
| 🔊 Audio y ajustes de rendimiento | **Disponible según función/equipo** | Control Center muestra ajustes compatibles y evita afirmar capacidades no disponibles. |
| 🖥️ Frecuencia de pantalla | **Disponible según monitor** | Selección de Hz admitidos, confirmación con mando y reversión automática a los 15 s; Cancelar tiene el foco inicial por seguridad. |
| 🔄 Actualizador | **Disponible** | Descargas verificadas y consentimiento explícito antes de instalar versiones compatibles. |
| 🧪 DLSS5 / ReShade | **Experimental** | Integraciones existentes para juegos preparados; composición visual final Native DX12 y compatibilidad general no demostradas. Evita antitrampas. |
| ⏳ Añadir juegos con mando | **Pendiente** | La entrada de Modo Consola está reservada; el asistente completo se realiza en Modo PC. |
| 🕹️ Mini Arcade | **Disponible** | Snake, Dino Run, Flappy y Breakout durante la carga; récords independientes y sonidos opcionales. Se retira al entregar el control al juego. |
| ⏳ Limitador de FPS | **No disponible** | No hay backend operativo para aplicar un límite de FPS; no se ofrece un selector funcional. |

### Consideraciones técnicas

- Windows 10/11 x64. Volumen NTFS cuando se emplean junctions para proteger partidas.
- El instalador incluye componentes y dependencias; las opciones de sensores CPU y permisos ETW se presentan **por separado y requieren consentimiento**. ETW puede necesitar cerrar sesión. No se eleva SYNCORE durante su uso habitual.
- El instalador **no está firmado digitalmente**. Verifica origen y SHA-256; no desactives las defensas de Windows.
- La disponibilidad de sensores, drivers, videojuegos y antitrampas no se puede garantizar para todos los equipos.
- Conserva siempre **respaldos independientes** de las partidas. Una fecha posterior de un archivo no demuestra mayor progreso.
- Persisten algunas rutas pendientes de **Mostrar escritorio**; no se anuncian como totalmente resueltas.
- En la validación de 2.2.2 quedó una **prueba de cadencia de sensores por debajo del objetivo**: 194 muestras/30 s frente a 200 mínimas; las lecturas siguen disponibles y el umbral no se ha rebajado.
- Las pruebas automatizadas no sustituyen una validación física completa de instalación, actualización y rollback en otros equipos.

[Cómo empezar](quick-start.md) · [Guía visual](visual-documentation.md) · [Notas oficiales](https://github.com/IMC93Labs/Syncore-Releases/releases/latest)

---

## English

SYNCORE brings several tools into one Windows application. **Available**, **optional**, **experimental**, and **not yet available** are different statuses and should never be conflated.

| Feature | Status in 2.2.2 | What to expect |
|---|---|---|
| 🎮 Game library / PC Mode | **Available** | Grid/list, search, filters, favourites, artwork and game options. |
| 🕹️ Console Mode | **Available** | Controller navigation; on game exit the library responds while save checks run in the background. |
| 🎛️ In-game Control Center | **System/permission-dependent** | Guide opens the panel; power and priority show actual states only where Windows permits reading or changing them. |
| 💾 Save protection | **Available with setup** | Verified backups, history and controlled recovery. Correct save paths and NTFS for junctions are essential. |
| ☁️ Google Drive | **Optional** | Verified save synchronisation and recovery, retries and conflict decisions. Requires your own OAuth setup, network and authorisation. |
| 📊 PresentMon / OSD | **Compatibility-dependent** | FPS/frametime for supported games/renderers with required permissions. Present events are not proof of final displayed/generated frames. |
| 🌡️ Hardware telemetry | **Compatibility-dependent** | CPU/GPU load, temperatures and RAM/VRAM when reliable sensors are available. Control Center can read hardware without a game. |
| 🔊 Audio & performance controls | **Feature/system-dependent** | Control Center exposes supported settings without claiming unavailable capabilities. |
| 🖥️ Refresh-rate control | **Display-dependent** | Supported Hz modes, gamepad confirmation and rollback after 15 s; Cancel has initial focus for safety. |
| 🔄 Built-in updater | **Available** | Integrity-checked updates with explicit installation approval. |
| 🧪 DLSS5 / ReShade | **Experimental** | Existing prepared-game integrations; Native DX12 final composition and broad compatibility unproven. Avoid anti-cheat-protected games. |
| ⏳ Controller-native Add game | **Pending** | Console entry reserved; complete game setup is handled from PC Mode. |
| 🕹️ Mini Arcade | **Available** | Snake, Dino Run, Flappy and Breakout while loading; separate records and optional sounds. Stops when control passes to the game. |
| ⏳ FPS limiter | **Unavailable** | No working backend for FPS limiting; no functional selector is offered. |

### Technical notes

- Windows 10/11 x64; NTFS is required wherever junction-based save protection is used.
- Setup bundles components and presents **separate consent** for CPU sensor and ETW options. ETW may require sign-out/sign-in. SYNCORE does not run elevated during normal use.
- The installer **is not digitally signed**. Verify the official source and SHA-256; do not disable Windows security.
- Sensor, driver, game and anti-cheat compatibility varies by system.
- Keep **independent backups** of important saves. A newer timestamp does not imply greater progress.
- Some **Show desktop** paths remain unresolved; no blanket compatibility claim is made.
- Release 2.2.2 reports **one below-target sensor cadence check**: 194 samples/30 s versus 200 minimum. Sensor readings remain available and the threshold was not lowered.
- Automated tests do not replace cross-device physical install, upgrade and rollback testing.

[Quick start](quick-start.md) · [Visual guide](visual-documentation.md) · [Release notes](https://github.com/IMC93Labs/Syncore-Releases/releases/latest)

---

<sub>SYNCORE Games · IMC93Labs · [Inicio / Home](../../README.md)</sub>
