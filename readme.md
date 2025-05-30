# 🎥 XION Bodycam Overlay para GTA V Roleplay

¡Bienvenido/a al **XION Bodycam Overlay**!  
Este es un **overlay estilo bodycam AXON™** para usar en **FiveM / GTA V Roleplay**. Ideal para agencias policiales como FIB, LSPD, BCSO, SAMS, SAFD etc.  
Dale más realismo a tus streams o grabaciones con un toque profesional. 🚔⚙️

---

## 🖼️ ¿Qué hace?

Este overlay muestra:

- 🎬 Estado de grabación con efecto *REC parpadeante*
- 🧑‍✈️ Nombre del agente (`player`)
- 🔢 Callsign personalizado (`[0000]`)
- 🏢 Agencia o departamento (`agency`)
- 📅 Fecha y 🕒 Hora en formato CET/CEST
- 🔊 Sonido de "beep" mientras graba
- 🖼️ Logo institucional (editable)

## 🧪 Vista previa
![Vista previa](https://i.imgur.com/Aesf7Y8.gif)


---

## 📁 Archivos importantes

- `index.html` – El archivo principal que genera el overlay.
- `logodepartamento.png` – Logo del FIB (puedes reemplazarlo por el de tu departamento).
- `Lekton-Italic.ttf` – Fuente usada en el diseño.

---

## ⚙️ Personalización

Edita fácilmente los siguientes valores dentro del `<script>` en `index.html` para personalizar tu bodycam:

```js
const player = "LOGAN HOLLIDAY";
const agency = "FEDERAL INVESTIGATION BUREAU";
const callsign = "[0789]";

📌 Tip: Reemplaza el logo logodepartamento.png por el de tu agencia y asegúrate de que tenga las mismas dimensiones (64x64px) o ajusta el tamaño en el HTML.

🚀 Cómo usarlo
Clona o descarga este repositorio.

Abre el archivo index.html en OBS como una fuente Browser (Navegador).

Marca "Fondo transparente" y ajusta tamaño (ej: 1920x1080).

¡Listo! Ya tienes una bodycam profesional para tus escenas RP.

🎯 Requisitos
- OBS Studio o software de stream que soporte fuentes HTML.
- Conexión a internet.


🛠️ Créditos
Diseñado por [ByRex03]

Inspirado en sistemas AXON™ Bodycam

💬 Licencia
Este proyecto está bajo la licencia MIT.
Úsalo, edítalo y compártelo libremente. Solo no elimines los créditos si vas a republicarlo. 🙏

¿Tienes dudas o ideas? ¡Abre un issue o haz un fork! 🛠️👨‍💻
