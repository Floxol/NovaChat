# 🌌 Nova Chat - Widget para KDE Plasma

**Nova Chat** es un plasmoid (widget) para KDE Plasma que permite interactuar con modelos de lenguaje locales (como LLaMA 3, Mistral, Phi, entre otros) usando [Ollama](https://ollama.com/). Está diseñado con un estilo espacial oscuro e inspirado en el cosmos.

---

## 🔧 Requisitos

- KDE Plasma con soporte para widgets personalizados.
- Ollama instalado y funcional.
- Modelos locales (ej: llama3, gemma, mistral, phi).
- `kpackagetool5` para instalación del widget.

---

## 🚀 Instalación

1. Clona el repositorio:
   ```bash
   git clone https://github.com/Floxol/NovaChat.git
   cd NovaChat/scripts
   ```

2. Ejecuta el instalador:
   ```bash
   chmod +x instalar_novachat.sh
   ./instalar_novachat.sh
   ```

3. Agrega el widget desde el menú de widgets de Plasma: **"Nova Chat"**.

---

## 🗑️ Desinstalación

```bash
cd NovaChat/scripts
chmod +x desinstalar_novachat.sh
./desinstalar_novachat.sh
```

---

## 🧠 Funcionalidades

- Estética espacial oscura.
- Historial persistente de conversaciones.
- Soporte para múltiples modelos Ollama.
- Sesiones independientes de chat.
- Selector de modelo desde la interfaz.

---

## 🌐 Vista previa web

Puedes ver más detalles en la página `web/index.html` incluida o subirla como GitHub Page.

---

## 📄 Licencia

MIT — Libre de usar, modificar y compartir. 🌟