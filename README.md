<div align="center">

# ▣ OptiFleet

**Controla varios teléfonos Android desde tu PC con Windows.**

Mira todos tus equipos en un mosaico, ábrelos con vídeo en vivo y control táctil,
revisa el estado de cada uno y aplica acciones a varios a la vez. Para talleres y granjas de teléfonos.

[🌐 Web](https://optisuite.app/optifleet/) · ✉️ support@optisuite.app · **v1.1.0** · Windows 10/11

**[⬇️ Descargar OptiFleet v1.1.0 (ZIP portable)](https://github.com/EnMaNueL-G/optifleet/releases/latest/download/OptiFleet-Portable-v1.1.0.zip)**

</div>

---

## ✨ Qué hace

- **Panel por equipo** — versión de Android y parche de seguridad, identidad e IMEI, batería (salud, temperatura y ciclos si el teléfono los informa), almacenamiento, uso de recursos e **informe de verificación**.
- **Mosaico** — miniaturas de todos tus equipos; con **«Ver todos en vivo»** pasan a vídeo en tiempo real (H.264).
- **Vídeo en vivo y control táctil** — abre cada equipo en su propia ventana y contrólalo desde el PC; también puedes espejarlo con scrcpy. Varias ventanas del mismo teléfono comparten una sola captura, el vídeo se reanuda solo si se corta y, al terminar, el teléfono recupera sus ajustes de pantalla.
- **Acciones en lote** — con confirmación y resultado por equipo: reiniciar, mantener despierto, instalar o desinstalar apps (también XAPK), respaldo de fotos, vídeos y archivos a una carpeta del PC (sin cifrar), optimización reversible (desactiva apps que no usas) y blindaje.
- **Blindaje** — oculta las Opciones de desarrollador y, con root, bloquea el restablecimiento de fábrica **desde Ajustes** (no desde el modo recovery). En algunas marcas, ocultar esas opciones apaga la depuración USB.
- **Bot de rutinas** — tocar, deslizar, escribir, pulsar teclas, abrir apps, hacer capturas…; cada N minutos o al conectar un equipo, con una espera mínima de 10 minutos por equipo.
- **Control desde el navegador** — en tu red local, o desde Internet con un túnel https (por ejemplo ngrok) o una VPN privada (por ejemplo Tailscale). Con https hay vídeo en vivo; por http funciona en modo capturas. Enlaces por usuario con los equipos asignados, rol **técnico** u **observador** (solo lectura) y caducidad.
- **Modo bajo consumo** — las miniaturas se actualizan cada 15 s y se pausan con la ventana minimizada (no afecta al vídeo en vivo).
- **Reconexión Wi-Fi** — los equipos conocidos se reconectan solos. Tras reiniciar el teléfono, Android olvida el modo Wi-Fi: enchúfalo una vez por USB y OptiFleet lo reactiva. Lista de equipos recordados con opción «Olvidar».
- **Estabilidad** — una sola copia abierta, recuperación si la ventana se cuelga y registro de errores en tu PC.

## 🔒 Seguridad y privacidad

- Sin anuncios ni telemetría.
- Tus datos **solo salen del PC si tú activas** el control web o la API.
- El control web/API viene **apagado** hasta que lo activas, está protegido por un token que puedes cambiar y limita los intentos fallidos.

## 🆕 Novedades de la 1.1.0

- **Seguridad:** se cierra la inyección de órdenes desde el control web, ventana blindada, token cambiable y API apagada por defecto.
- **Vídeo en vivo estable:** sin tormenta de reconexiones ni cortes entre ventanas; se reanuda solo y devuelve los ajustes de pantalla del teléfono.
- **Acciones en lote** con confirmación y resultado real por equipo.
- **Bot sin bucles** y **reconexión Wi-Fi mejorada**.
- **Licencias propias** de OptiFleet, sin Gumroad.
- **Electron 44**; el modo bajo consumo y el botón Captura ya funcionan.

## 💵 Precio

**10 días de prueba completa** (todo desbloqueado).

| Plan | Precio | Incluye |
|---|---|---|
| **PRO** | **$12.99** | Panel, mosaico, vídeo en vivo, control y acciones en lote |
| **PRO+** | **$19.99** | Todo lo de PRO + control web, compartir por usuario, bot de rutinas, respaldo y monitoreo |

**Comprar:** [💬 por WhatsApp](https://wa.me/56978327863?text=Hola%2C%20quiero%20una%20licencia%20de%20OptiFleet%20(PRO%20o%20PRO%2B).%20Mi%20ID%20de%20equipo%20(lo%20ves%20en%20la%20pesta%C3%B1a%20Apoyo)%3A%20) o en **support@optisuite.app**.
Envía tu **ID de equipo** (pestaña **Apoyo**) y recibirás tu clave. Las claves son propias de OptiFleet (las de OptiSuite Toolkit no sirven) y se activan sin conexión a internet.

## 📦 Requisitos e instalación

- Windows 10/11.
- Depuración USB activada en los teléfonos.
- ADB y scrcpy **incluidos**; no hay que instalar nada más.

1. Descarga el ZIP.
2. Clic derecho → **«Extraer todo…»**.
3. Abre **OptiFleet.exe**.

---

<div align="center">

Enmanuel Gil · OptiSuite · © 2026 · Código privado y protegido.

</div>
