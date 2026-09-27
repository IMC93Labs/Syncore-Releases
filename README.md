<p align="center">
  <strong>SYNCORE</strong><br>
  <sub>ALL YOUR GAMES / SYNC</sub><br>
  <sub>Windows game library · Console Mode · Controllers · Save protection · Cloud recovery</sub>
</p>

<p align="center">
  <img alt="Windows 10/11 x64" src="https://img.shields.io/badge/platform-Windows%2010%20%2F%2011%20x64-0078D4">
  <a href="https://github.com/IMC93Labs/Syncore-Releases/releases/latest"><img alt="Latest stable release" src="https://img.shields.io/badge/stable-v2.0.0-2ea44f"></a>
  <img alt="Distribution repository" src="https://img.shields.io/badge/repository-releases%20%26%20docs-B7F52A">
</p>

<p align="center">
  <a href="https://github.com/IMC93Labs/Syncore-Releases/releases/download/v2.0.0/SynCore-Setup-v2.0.0.exe"><strong>⬇ Download SYNCORE v2.0.0 / Descargar SYNCORE v2.0.0</strong></a>
  · <a href="https://github.com/IMC93Labs/Syncore-Releases/releases/latest">Release notes / Notas</a>
  · <a href="docs/guides/features.md">Features / Funciones</a>
  · <a href="SUPPORT.md">Support / Soporte</a>
</p>

[English](#english) · [Español](#espanol)

---

<a id="english"></a>
## English

### Your games and saves, together

SYNCORE is a Windows game library with a controller-friendly Console Mode and local-first save protection. Configure and launch games, choose their artwork, manage selected save folders and restore your library on another PC with Google Drive.

**SYNCORE v2.0.0 is publicly released.** It succeeds Game Sync Hub 1.1.0; earlier releases remain available in the [release history](https://github.com/IMC93Labs/Syncore-Releases/releases).

### Download and install

**[Download SynCore-Setup-v2.0.0.exe](https://github.com/IMC93Labs/Syncore-Releases/releases/download/v2.0.0/SynCore-Setup-v2.0.0.exe)** · [View v2.0.0 release notes](https://github.com/IMC93Labs/Syncore-Releases/releases/tag/v2.0.0)

- **System:** Windows 10/11 x64. Save-folder junction protection requires a local NTFS volume.
- The installer includes the application runtime and broker. Optional controller virtualization includes the official HidHide installer and HIDMaestro preparation and may require restarting Windows.
- Google Drive functions require your own OAuth Desktop App configuration; no Google account or credentials are bundled.
- You can manually upgrade compatible Game Sync Hub 1.x installations while retaining compatible data. Keep an independent backup of important saves before making changes.
- **Publisher signature:** this v2.0.0 installer is not Authenticode-signed. Download only from this official release and check its hash before running it. The final installer passed automated checks and an isolated launch test; a physical installation on a clean Windows system has not yet been recorded.

**SHA-256 — installer**

```text
6EF4D68FB4B5D9C6F7CFD61A1E7C5FD61DBC25C47B3C6534B4166FF1984F97ED
```

Verify the downloaded file in PowerShell:

```powershell
Get-FileHash -Algorithm SHA256 "SynCore-Setup-v2.0.0.exe"
```

### What is included

- **Library and Console Mode:** configure and launch games using the desktop library or controller-first interface.
- **Artwork and metadata:** search for candidates and select covers and backgrounds.
- **Save protection:** link selected game save folders to verified managed storage through NTFS junctions.
- **Google Drive recovery:** Current, Previous, recoverable history and guided local/remote conflict choices.
- **Second-PC setup:** recover the library and configure a game on another Windows PC without replacing the first PC's device profile.
- **Resumable operations:** journals and conservative recovery steps protect local data during interrupted changes.
- **Stable updates:** distribution through the official release repository.

[Feature guide](docs/guides/features.md) · [Support](SUPPORT.md) · [Security](SECURITY.md) · [Disclaimer](DISCLAIMER.md)

### About this repository

This public repository distributes **installers, release notes, documentation and support**, not the private SYNCORE application source code. SYNCORE is a personal, AI-assisted hobby project offered on a best-effort basis. Keep independent backups of irreplaceable saves.

Historical images in `docs/media/` show **Game Sync Hub 1.x**, not SYNCORE 2.0. Updated, privacy-reviewed v2.0 screenshots will be added separately; do not interpret old artwork as the current UI.

---

<a id="espanol"></a>
## Español

### Tus juegos y partidas, juntos

SYNCORE reúne una biblioteca de juegos para Windows, un Modo consola adaptado al mando y protección local de partidas. Configura y ejecuta tus juegos, selecciona sus imágenes, gestiona sus carpetas de guardado y recupera tu biblioteca en otro PC mediante Google Drive.

**SYNCORE v2.0.0 ya está publicado.** Sucede a Game Sync Hub 1.1.0; las versiones anteriores siguen disponibles en el [historial de publicaciones](https://github.com/IMC93Labs/Syncore-Releases/releases).

### Descarga e instalación

**[Descargar SynCore-Setup-v2.0.0.exe](https://github.com/IMC93Labs/Syncore-Releases/releases/download/v2.0.0/SynCore-Setup-v2.0.0.exe)** · [Notas de v2.0.0](https://github.com/IMC93Labs/Syncore-Releases/releases/tag/v2.0.0)

- **Sistema:** Windows 10/11 x64. La protección mediante junctions requiere un volumen NTFS local.
- El instalador incluye el runtime y el broker. La virtualización opcional de mandos incorpora el instalador oficial de HidHide y la preparación de HIDMaestro; puede necesitar reiniciar Windows.
- Las funciones de Google Drive requieren tu propia configuración OAuth Desktop App; no se incluye ninguna cuenta ni credencial.
- Puedes actualizar manualmente instalaciones compatibles de Game Sync Hub 1.x conservando los datos compatibles. Mantén una copia independiente de las partidas importantes.
- **Firma:** el instalador v2.0.0 no tiene firma Authenticode. Descárgalo solo desde esta publicación oficial y comprueba su hash antes de ejecutarlo. El instalador final superó las pruebas automatizadas y un arranque aislado; todavía no consta una instalación física en un Windows limpio.

**SHA-256 — instalador**

```text
6EF4D68FB4B5D9C6F7CFD61A1E7C5FD61DBC25C47B3C6534B4166FF1984F97ED
```

Comprueba el archivo descargado desde PowerShell:

```powershell
Get-FileHash -Algorithm SHA256 "SynCore-Setup-v2.0.0.exe"
```

### Funciones principales

- **Biblioteca y Modo consola:** configura y abre juegos desde Windows o con una interfaz adaptada al mando.
- **Imágenes y metadatos:** busca candidatos y selecciona portadas y fondos.
- **Protección de partidas:** vincula carpetas de guardado al almacenamiento gestionado y verificado mediante junctions NTFS.
- **Recuperación en Google Drive:** Current, Previous, historial recuperable y elección guiada entre partidas locales y remotas.
- **Varios equipos:** recupera la biblioteca y configura juegos en otro PC sin sustituir el perfil del primero.
- **Operaciones reanudables:** journals y recuperación conservadora ante interrupciones.
- **Actualizaciones estables:** distribuidas desde el repositorio oficial de publicaciones.

[Guía de funciones](docs/guides/features.md) · [Soporte](SUPPORT.md) · [Seguridad](SECURITY.md) · [Aviso y responsabilidad](DISCLAIMER.md)

### Sobre este repositorio

Este repositorio público ofrece **instaladores, notas de versión, documentación y soporte**, no el código fuente privado de SYNCORE. SYNCORE es un proyecto personal desarrollado como hobby con asistencia de IA y mantenido en la medida de lo posible. Conserva siempre copias independientes de tus partidas irremplazables.

Las imágenes históricas de `docs/media/` corresponden a **Game Sync Hub 1.x**, no a SYNCORE 2.0. Las nuevas capturas se incorporarán después de revisarlas para no exponer información personal.

---

<p align="center"><strong>SYNCORE · IMC93Labs</strong></p>
