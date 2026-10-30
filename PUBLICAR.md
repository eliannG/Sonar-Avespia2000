# Publicar la página del celular (GitHub Pages, ~3 minutos)

El QR del sonar apunta a: https://elianng.github.io/Sonar-Avespia2000/ (repo eliannG/Sonar-Avespia2000)

1. En GitHub, creá un repo **público** (ya lo creaste: Sonar-Avespia2000).
2. Subí a la raíz del repo los dos archivos de esta carpeta: `index.html` y `mqtt.min.js` (Add file → Upload files).
3. Settings → Pages → Source: Deploy from a branch → Branch: `main` / `(root)` → Save.
4. En 1–2 minutos abrí la URL de arriba en tu celular, poné tu nombre y tocá Conectar.
5. Con el sonar abierto en la compu, sacudí el celular: tenés que aparecer como un punto celeste.

Si usás otro nombre de repo, cambiá `PHONE_URL` en `SonarNocturno/index.html`.

## Cómo funciona
Los celulares y el sonar se hablan por MQTT sobre WebSocket seguro, usando dos brokers públicos y gratuitos a la vez (HiveMQ y EMQX). Si uno falla, sigue el otro. Funciona con datos móviles y con wifi.

## Probalo antes del evento
- En la sala: abrí el sonar, abajo a la derecha tiene que decir "RED EN LÍNEA 2/2" (o 1/2).
- Conectá tu celular con datos móviles y sacudí.
- Si la red de la sala bloquea todo: tecla **D** en el sonar = celulares simulados.

## IMPORTANTE: cada vez que cambie celular/index.html
Volvé a subirlo al repo (Add file → Upload files → reemplazar index.html). GitHub Pages tarda 1–2 minutos en actualizar.
