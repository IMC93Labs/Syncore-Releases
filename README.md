# SYNCORE Games

**SYNCORE 2.2.1 — Windows game library, Console Mode and verified save protection.**

SYNCORE Games is the public project description. The Windows application remains named **SYNCORE**.

[Download SYNCORE 2.2.1](https://github.com/IMC93Labs/Syncore-Releases/releases/download/v2.2.1/SynCore-Setup-v2.2.1.exe) · [Latest release and checksums](https://github.com/IMC93Labs/Syncore-Releases/releases/latest) · [All previous versions](https://github.com/IMC93Labs/Syncore-Releases/releases) · [Features and limitations](docs/guides/features.md)

## Available

- PC library with grid/list views, complete cover images, search, filters, artwork selection and shared favorites.
- Controller-oriented Console Mode, Guide/Control Center, compact settings, confirmed dropdown choices and circular navigation.
- Local save protection, verified Cloud synchronization through your Google Drive configuration, protected history, version selection and safe recovery. Ambiguous versions require a decision; the app does not infer progress from file dates.
- Own OSD: PresentMon FPS/frametime and available CPU/GPU usage, temperatures, RAM and VRAM. Control Center readings work without a game; FPS/frametime need an active compatible renderer. Metric switches change OSD visibility only.
- Supported display refresh rates with confirmation, rollback and restoration after the game.
- Integrated stable-release updater, with explicit installation confirmation and preservation of compatible user data.

## Installation and updates

Windows 10/11 x64. NTFS is required where junction-based protection is used. Runtime components and the existing helper/broker are bundled; SYNCORE runs without administrator rights.

Optional Setup choices are explicit: controller dependencies, CPU temperature through the signed PawnIO driver, and ETW permission for Own. ETW adds the selected local user to Performance Log Users, is reversible and may need sign-out/sign-in. CPU/ETW configuration is not silently applied and is not repeated through UAC per game. Sensor support and anti-cheat policies vary. A game may still require its own UAC independently of SYNCORE.

Supported stable versions can update directly to 2.2.1 without intermediate releases. Normal update/uninstall preserves library, preferences, credentials, saves and protected backups; deleting local data remains a separate explicit destructive choice. Keep independent backups before any installation change.

**The SYNCORE installer is not digitally signed.** Keep Windows protections enabled, use this official repository and compare SHA-256 with the release asset. Signed vendor dependencies do not make the SYNCORE installer signed.

```powershell
Get-FileHash -Algorithm SHA256 'SynCore-Setup-v2.2.1.exe'
```

Google Drive requires your own OAuth setup; no account, credentials or personal saves are distributed.

## Limits and validation

Dynamic FPS limiting is **not available**. Own measures Present events; it does not certify final displayed/generated frames. DLSS5 routes are limited to prepared compatible games; Native DX12 has verified internal evaluations, while final visual composition remains unconfirmed. Do not use experimental integrations with anti-cheat-protected games.

Some Show desktop entry points remain unresolved; Win+D and direct game return retain their validated behavior. CPU temperature is shown only with a real supported sensor. The Console Mode Add game entry is reserved for a future controller-adapted flow. Historical CrashReportClient diagnostics are documented with verified backups; they are not save files.

Automated checks and isolated real-game telemetry evidence are recorded in each release. Clean installation, upgrade, reinstall and rollback on additional PCs remain external validation; no universal compatibility is claimed.

The media in `docs/media/` is historical, not a screenshot of the current UI. Previous releases and migration documentation remain available as history.

---

## Español

**SYNCORE Games** es el nombre descriptivo público; la aplicación sigue llamándose **SYNCORE**.

[Descargar SYNCORE 2.2.1](https://github.com/IMC93Labs/Syncore-Releases/releases/download/v2.2.1/SynCore-Setup-v2.2.1.exe) · [Notas, SHA256 y procedencia](https://github.com/IMC93Labs/Syncore-Releases/releases/latest)

Biblioteca PC renovada, Modo Consola con mando, Guide y Control Center; protección de partidas, historial y selección de versiones; sincronización verificada con Google Drive y recuperación segura. Las versiones ambiguas se conservan y requieren elegir: una fecha más reciente no demuestra mayor progreso.

Own mide FPS/frametime mediante PresentMon y muestra los sensores disponibles. Control Center mantiene lecturas de hardware sin juego, aunque los interruptores estén apagados; estos solo controlan su aparición en el OSD. FPS/frametime requieren un juego compatible. Hz permite aplicar, confirmar y restaurar frecuencias compatibles.

El instalador incorpora runtimes y componentes. Las opciones PawnIO/temperatura CPU y ETW requieren consentimiento explícito durante Setup; ETW es un permiso reversible para el usuario local y puede requerir cerrar sesión. No se eleva toda la aplicación ni se pide UAC por cada medición. Los juegos pueden solicitar sus propios permisos.

Actualización directa a 2.2.1, conservando datos compatibles. La desinstalación normal conserva los datos; su eliminación es una elección destructiva separada. Google Drive necesita configuración OAuth propia. **Instalador sin firma digital:** no desactives las protecciones de Windows y comprueba su SHA256.

Limitaciones: limitador FPS no disponible, composición visual final de DLSS5 Native DX12 no demostrada, algunos accesos de Mostrar escritorio pendientes, sensores dependientes del hardware y asistente de añadir juegos con mando pendiente. Instalación/actualización físicas en otros equipos pendientes de validación externa. No se anuncian estas funciones como terminadas.

[Funciones y límites](docs/guides/features.md) · [Soporte](SUPPORT.md) · [Seguridad](SECURITY.md) · [Historial](https://github.com/IMC93Labs/Syncore-Releases/releases)
