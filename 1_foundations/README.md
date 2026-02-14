---
title: career_conversation
app_file: app.py
sdk: gradio
sdk_version: 5.49.1
---

## Desplegar en Hugging Face Spaces (Gradio)

Para desplegar esta app con Gradio sin errores de ruta, ejecuta el deploy **desde esta carpeta** (`1_foundations`):

```bash
cd 1_foundations
uv run dotenv -f ../.env run -- uv run gradio deploy
```

Cuando pregunte por el archivo de la app, escribe `app.py`.
