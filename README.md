
# 🛠️ DawnCraft-Server-Ready

Servidor oficial **DawnCraft** completamente preconfigurado, listo para clonar, ejecutar y jugar con amigos. Incluye traducción al español, shaders configurados, sistema de backups y compatibilidad con conexión por **Tailscale**.

---

## 📥 Descargar servidor

🔗 [Descargar desde Google Drive](https://drive.google.com/file/d/1E9L6WWAajE_se9T_9WraRAFSxi-1dQab/view?usp=drive_link)

Descomprime el archivo `.zip` en cualquier carpeta local y sigue los pasos para ejecutarlo.

---

## 🚀 Cómo iniciar el servidor

1. Asegúrate de tener **Java 17** instalado.
2. 🔗 Puedes descargarlo desde el siguiente enlace oficial de Adoptium:  
👉 [Descargar Java 17 (Temurin)](https://adoptium.net/es/temurin/releases/?os=any&arch=any&package=jdk&version=17)
### 🔍 Verifica la instalación

Para confirmar que Java se ha instalado correctamente, abre una terminal o consola de comandos (cmd) y escribe:
```
java --version
```

4. Abre PowerShell dentro de la carpeta del servidor.dame
5. Ejecuta:
```
Set-ExecutionPolicy -ExecutionPolicy Bypass -Scope Process
.\start.ps1
```

5. ### ✅ Aceptar la EULA

Acepta la **EULA** cuando se te pida al iniciar por primera vez el servidor.

---

### 🧠 Recomendaciones

- Se recomienda disponer de al menos **8 GB de RAM** dedicados al servidor para un rendimiento óptimo.
- ⚙️ Por defecto, el servidor ya está preconfigurado con 8 GB de RAM.  
  Puedes ajustar esta cantidad editando el archivo `variables.txt`, modificando la línea:
  ```bash
  JAVA_ARGS="-Xmx8G -Xms8G"
- 🧾 En el archivo `server.properties`, también se han preestablecido los valores recomendados para el rendimiento:
  - `view-distance=6`
  - `simulation-distance=4`
-Si cuentas con más recursos disponibles, puedes incrementarlos para mejorar la experiencia del juego.
---

### 🌐 Jugar con amigos (sin abrir puertos)

Este servidor usa **Tailscale** para jugar sin complicaciones:

1. Descarga Tailscale: [https://tailscale.com](https://tailscale.com)
2. Inicia sesión con tu cuenta de Google.
3. Pide al dueño del servidor que te invite a su red.
4. Conéctate usando la IP que te dé Tailscale (ejemplo: `100.x.x.x`).

---

### 🔁 Backups automáticos

- El servidor incluye el mod **SimpleBackups**.
- Guarda copias de seguridad automáticamente cada **15 minutos** en la carpeta `simplebackups/`.
- Tamaño máximo total: **25 GB**.
- Se almacenan los últimos **10 backups**.

---

### 🧙 Shaders y Mods

Este servidor está listo para usar shaders como:

- **Complementary**
- **Sildur’s**
- **SEUS**

Solo debes activarlos desde el menú de vídeo si usas **Iris** u **OptiFine**, los cuales ya vienen preconfigurados desde CurseForge.




