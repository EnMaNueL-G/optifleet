<div align="center">

# ▣ OptiFleet

**Centro de mando de flotas de dispositivos Android — desde tu PC.**

Visualiza, controla y diagnostica **decenas de dispositivos Android a la vez** desde una sola
aplicación de escritorio. Panel profesional por equipo, mosaico en vivo de toda la flota,
control y espejado, e informe de salud. Pensado para talleres y granjas de dispositivos.

[🌐 Web](https://optisuite.app/#optifleet) · ✉️ support@optisuite.app · **v1.0.0 (Beta)** · Windows 10/11

</div>

---

## ✨ Qué hace

- **Mosaico en vivo** — todos tus equipos en una rejilla que se actualiza en tiempo real; elige cuál controlar.
- **Panel por dispositivo** — Android, parche de seguridad, identidad e IMEI, batería (salud, ciclos, temperatura), almacenamiento e **informe de verificación** (Normal / Aviso / Anormal).
- **Control y espejado** — visualiza y maneja cualquier equipo desde el PC; abre varios a la vez.
- **Acciones en lote** — reinicia, espeja o gestiona varios equipos seleccionados de una sola vez.
- **Modo bajo consumo** — optimizado para mantener muchos equipos conectados en sesiones largas.
- **Privado y seguro** — licencia vinculada a tu equipo, sin anuncios ni telemetría; tus datos no salen del PC.

## 🧰 Herramientas y tecnologías

| Área | Tecnología |
|------|-----------|
| Aplicación de escritorio | **Electron 33** (Chromium + Node), `contextIsolation`, IPC por `contextBridge` |
| Conexión con dispositivos | **ADB** (Android Platform-Tools), `execFile` sin shell |
| Espejado / control | Motor de espejado integrado (basado en scrcpy) |
| Información en vivo | Captura de pantalla periódica para el mosaico |
| Interfaz | HTML/CSS/JS *vanilla*, gauges con `conic-gradient`, tema oscuro OptiSuite |
| Licencias | Claves firmadas **Ed25519** (offline) + verificación Gumroad + huella de equipo + HMAC + anti-rollback |

> **En desarrollo (próximas versiones):** multi-stream de vídeo en vivo con **WebCodecs** (H.264) y *Web Workers*,
> calidad adaptativa por dispositivo, API REST interna, sincronización de acciones, visión por computador
> (auto-diagnóstico) y companion para tiempos de actividad prolongados.

## 💵 Precio

**$12.99** · licencia por equipo · **10 días de prueba gratis** (todo desbloqueado).
Beta privada: escríbenos a **support@optisuite.app**.

## 📦 Requisitos

- Windows 10/11
- ADB (Android Platform-Tools) — incluido en la versión empaquetada
- Depuración USB activada en los dispositivos

---

<div align="center">

Parte de la suite **OptiSuite** · © EnMaNueL-G · Código privado y protegido.

</div>
