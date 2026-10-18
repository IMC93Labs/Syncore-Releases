# 📘 Empezar con SYNCORE / SYNCORE quick start

> **SYNCORE Games** · [Inicio / Home](https://github.com/IMC93Labs/Syncore-Releases) · [Descarga / Download](https://github.com/IMC93Labs/Syncore-Releases/releases/latest) · [Funciones / Features](https://github.com/IMC93Labs/Syncore-Releases/blob/main/docs/guides/features.md) · [Guía visual / Visual guide](https://github.com/IMC93Labs/Syncore-Releases/blob/main/docs/guides/visual-documentation.md) · [Ayuda / Support](https://github.com/IMC93Labs/Syncore-Releases/blob/main/SUPPORT.md)

**Idioma / Language:** [Español](#español) · [English](#english)

---

## Español

### 1 · Descargar

Accede a [la última versión estable](https://github.com/IMC93Labs/Syncore-Releases/releases/latest), despliega **Assets** y descarga **`SynCore-Setup-vX.Y.Z.exe`**. La aplicación está dirigida a Windows 10/11 x64.

### 2 · Verificar el archivo

El instalador **no está firmado digitalmente**. Comprueba que la descarga procede del repositorio oficial y compara el SHA-256 del instalador con el archivo `.sha256` que acompaña a la publicación. En PowerShell:

```powershell
Get-FileHash -Algorithm SHA256 -Path ".\SynCore-Setup-vX.Y.Z.exe"
```

Sustituye `X.Y.Z` por la versión descargada. **No desactives SmartScreen ni otras defensas de Windows** para instalarlo.

### 3 · Instalar y configurar

El instalador presenta por separado los componentes opcionales relacionados con mandos, lecturas de temperatura CPU y permisos ETW. Activa solo lo necesario y entiende sus efectos antes de aceptar; algunas opciones requieren iniciar sesión de nuevo en Windows.

Abre SYNCORE y añade un juego desde el **Modo PC**. Selecciona sus rutas y arte gráfico con las herramientas disponibles. El asistente de añadir juegos **íntegramente con mando todavía no está terminado**.

### 4 · Proteger partidas y conectar Drive (opcional)

Configura la **carpeta real de partidas** de cada juego antes de activar su protección. El sistema de enlaces requiere **NTFS** donde se aplique. Conserva una copia adicional fuera de SYNCORE.

Puedes enlazar **tu propia cuenta y configuración OAuth de Google Drive** para sincronizar copias de partidas y recuperarlas. Confirma manualmente las versiones cuando exista un conflicto: la fecha de un archivo no demuestra qué partida tiene mayor progreso. Google Drive no sustituye a una copia de seguridad independiente.

### 5 · Jugar y pedir ayuda

Entra en **Modo Consola** desde SYNCORE para navegar con el mando. Las métricas de Control Center/OSD aparecen solo si el hardware y el juego permiten lecturas válidas.

[Funciones](features.md) · [Guía visual](visual-documentation.md) · [Ayuda](../../SUPPORT.md) · [Versiones](https://github.com/IMC93Labs/Syncore-Releases/releases)

---

## English

### 1 · Download

Open the [latest stable release](https://github.com/IMC93Labs/Syncore-Releases/releases/latest), expand **Assets** and download **`SynCore-Setup-vX.Y.Z.exe`** for Windows 10/11 x64.

### 2 · Verify the file

The installer **is not digitally signed**. Download only from the official repository and compare the installer's SHA-256 with the published `.sha256` asset:

```powershell
Get-FileHash -Algorithm SHA256 -Path ".\SynCore-Setup-vX.Y.Z.exe"
```

Replace `X.Y.Z` with the actual release version. **Do not disable Windows security protections**.

### 3 · Install and configure

Setup presents optional controller, CPU sensor and ETW components separately. Review permissions before consenting; some changes may need a Windows sign-out/sign-in.

Add games from **PC Mode** and configure their files and artwork. The fully controller-driven Add game wizard is **not available yet**.

### 4 · Protect saves and optionally connect Drive

Select each game's **actual save folder**. Junction-based protection needs **NTFS**, and independent backups remain important.

Optional Google Drive synchronisation needs **your own OAuth configuration and account**. Resolve ambiguous save versions manually: timestamps are not reliable proof of game progress. Cloud synchronisation is not a substitute for independent backups.

### 5 · Play and get help

Enter **Console Mode** to browse with a gamepad. Control Center/OSD readings are shown only where valid data is available.

[Features](features.md) · [Visual guide](visual-documentation.md) · [Support](../../SUPPORT.md) · [Releases](https://github.com/IMC93Labs/Syncore-Releases/releases)

---

<sub>SYNCORE Games · IMC93Labs · [Inicio / Home](../../README.md)</sub>
