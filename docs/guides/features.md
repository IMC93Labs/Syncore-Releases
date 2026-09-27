# SYNCORE v2.0.0 — Features / Funciones

**Public stable release / Versión estable pública:** [SYNCORE v2.0.0](https://github.com/IMC93Labs/Syncore-Releases/releases/tag/v2.0.0) · [Download installer / Descargar instalador](https://github.com/IMC93Labs/Syncore-Releases/releases/download/v2.0.0/SynCore-Setup-v2.0.0.exe)

[English](#english) · [Español](#espanol)

---

<a id="english"></a>
## English

### Library, artwork and launch
- Desktop library for installed and remote-library games; configure games on each PC independently.
- Game launch, metadata, cover and background selection, and controller-friendly Console Mode.
- Optional controller virtualization; the installer includes HidHide setup and HIDMaestro preparation.

### Save protection and recovery
- Choose a game's save folder and protect it via a verified local managed copy and NTFS junction.
- Compare local and Google Drive save versions before selecting which one to activate or preserve.
- Google Drive `Current`, `Previous`, recoverable history, imports and manual recovery.
- Recover on another PC using a device-specific profile. Journaled operations can resume following interruptions.
- Conservative handling of existing saves and backups; technical backups are removed only after they are verified redundant.
- Stable releases distributed through this repository.

### Requirements and boundaries
Windows 10/11 x64; a **local NTFS volume** for save junctions. Cloud functionality requires user-provided Google Drive OAuth Desktop App configuration. Keep independent backups of important saves. The installer is not Authenticode-signed; verify its [published SHA-256](../../README.md#download-and-install).

The final installer passed automated checks and an isolated launch test; a physical installation on clean Windows has not yet been recorded. Hardware-specific or game-specific behaviour may vary. For details, see the [v2.0.0 release notes](https://github.com/IMC93Labs/Syncore-Releases/releases/tag/v2.0.0).

Previous [Game Sync Hub v1.1.0 notes](../releases/v1.1.0.md) are historical documentation, not the current stable release.

---

<a id="espanol"></a>
## Español

### Biblioteca, imágenes y ejecución
- Biblioteca de juegos instalados y recuperados de Drive; configuración independiente por equipo.
- Lanzamiento de juegos, metadatos, elección de portadas y fondos y Modo consola con mando.
- Virtualización opcional de mandos; el instalador incluye la preparación de HidHide y HIDMaestro.

### Protección y recuperación de partidas
- Selecciona la carpeta de partidas y protégela mediante una copia local gestionada y verificada con junction NTFS.
- Compara partidas locales y de Google Drive antes de decidir cuál activar o conservar.
- `Current`, `Previous`, historial recuperable, importaciones y recuperación manual en Google Drive.
- Recuperación en otro PC con perfil propio. Operaciones registradas en journals y reanudables tras interrupciones.
- Tratamiento conservador de partidas y copias: los respaldos técnicos se retiran solo tras comprobar que son redundantes.
- Versiones estables distribuidas desde este repositorio.

### Requisitos y límites
Windows 10/11 x64; **volumen NTFS local** para los junctions. Google Drive requiere la configuración OAuth Desktop App aportada por el usuario. Conserva copias independientes de las partidas importantes. El instalador no está firmado con Authenticode; verifica su [SHA-256 publicado](../../README.md#descarga-e-instalación).

El instalador final superó pruebas automatizadas y un arranque aislado; todavía no consta una instalación física en Windows limpio. El funcionamiento puede variar según el equipo y el juego. Consulta las [notas de v2.0.0](https://github.com/IMC93Labs/Syncore-Releases/releases/tag/v2.0.0).

Las [notas de Game Sync Hub v1.1.0](../releases/v1.1.0.md) se conservan como documentación histórica y no representan la versión estable actual.
