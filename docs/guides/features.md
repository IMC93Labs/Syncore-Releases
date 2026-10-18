# SYNCORE Games — SYNCORE 2.2.1

[Current stable / Versión estable actual](https://github.com/IMC93Labs/Syncore-Releases/releases/latest)

| Area / Área | Available / Disponible | Limits / Límites |
|---|---|---|
| PC library / Biblioteca | Grid/list, cover sizing, search/filters, actions, shared favorites / Cuadrícula/lista, carátulas completas, filtros y acciones | Games/artwork must exist; no invented statistics / Datos reales |
| Console / Consola | Controller navigation, Guide/Control Center, compact settings, confirm/cancel dropdowns / Navegación con mando y ajustes compactos | Add-game entry reserved; no controller file browser yet / Añadir juego reservado |
| Saves / Partidas | Local verified backups, protected history, version selection, transactional restore/recovery / Historial, elección y recuperación protegidos | Ambiguous branches require choice; advanced progress is not inferred from date / Divergencias requieren elección |
| Google Drive | Verified synchronization, retries, safe repair and offline pending work / Sincronización verificada y recuperación segura | User OAuth required; network/auth/conflicts may require intervention / Requiere OAuth propio |
| Own / PresentMon | Observed FPS/frametime and available CPU/GPU/RAM/VRAM; live hardware in Control Center without game / Sensores sin juego | Frames need active compatible renderer and ETW permission; Present events are not proof of final composition / FPS requieren renderer y ETW |
| CPU temperature / Temperatura CPU | CPU Package/equivalent through existing broker, supported sensors and optional signed PawnIO / Lectura real mediante broker existente | Explicit Setup consent, hardware/anti-cheat dependent; unavailable is — / Depende de hardware y políticas |
| Refresh rate / Hz | Supported monitor modes, confirmation, restoration and recovery / Frecuencias compatibles, confirmación y restauración | No unsupported modes or global permanent GPU profile changes / Sin modos incompatibles |
| Updates / Actualizaciones | Direct stable upgrade, download integrity, explicit install, deferred own notices / Actualización directa con verificación y confirmación | Installer unsigned; physical cross-PC scenarios still need validation / Sin firma; validación externa pendiente |
| DLSS5 | Existing prepared-game integrations; DX11 and Native DX12 internal evaluation evidence / Integración existente en juegos preparados | Experimental/limited compatibility; Native final visual composition unconfirmed; no anti-cheat claim / Composición final Native no demostrada |

## Not available / No disponible

- Dynamic FPS limiting / Limitador dinámico de FPS: disabled, no safe universal backend shipped.
- Universal DX12/Vulkan/OpenGL compatibility or universal anti-cheat compatibility / Compatibilidad universal no demostrada.
- Some Windows Show desktop routes / Algunos accesos de Mostrar escritorio.
- Controller-adapted Add game wizard / Asistente Añadir juego adaptado al mando.

## Installation permissions / Permisos

SYNCORE runs as the normal user. Setup has explicit optional tasks for controller support, CPU hardware access and ETW. ETW uses Performance Log Users (S-1-5-32-559), a persistent reversible diagnostic permission for the local user and their apps; it is not an administrator grant. Sign-out/sign-in may be needed. Existing memberships are preserved. CPU driver/provider support is not guaranteed on every PC.

SYNCORE se ejecuta como usuario normal. Las tareas opcionales del instalador explican los permisos y dependen de consentimiento; no se desactivan protecciones ni se elevan juegos de forma indiscriminada. La retirada ETW se hace mediante el script Undo con su journal; no se retiran permisos previos.

Normal uninstall keeps user data. Historical documentation/screenshots remain archived and are not evidence that an unavailable feature is implemented. / La desinstalación normal conserva datos; la documentación histórica no anuncia funciones pendientes como operativas.
