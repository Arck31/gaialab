# GaiaLab - Dashboard del girasol

Panel para ninos que muestra la humedad y la temperatura de un terrario en tiempo real.
El girasol cambia de animo: feliz, con sed, con calor, con frio...

- Datos: ESP32 -> EMQX Cloud (MQTT sobre TLS) -> esta pagina (WebSocket seguro).
- Boton **Demo**: muestra los escenarios sin necesitar el modulo.
- Modo profesor: PIN para cambiar la meta de humedad y la temperatura maxima.
- La conexion usa `config.js` (ver `config.example.js`).
