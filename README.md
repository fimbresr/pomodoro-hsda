# Enfoque · Hospital San Diego de Alcalá

Temporizador **Pomodoro** (PWA) para programar tiempo de enfoque. Funciona en cualquier
dispositivo, se instala en la pantalla de inicio y opera sin conexión.

## Instalar en el teléfono

Abre el enlace publicado en el navegador del dispositivo:

- **Android (Chrome):** menú ⋮ → *Instalar app* / *Agregar a pantalla de inicio*.
- **iPhone (Safari):** botón Compartir → *Agregar a pantalla de inicio*.

Quedará con el ícono de HSDA y se abrirá a pantalla completa.

## Funciones

- Modos Enfoque / Pausa breve / Pausa larga con encadenado automático.
- Anillo de progreso, conteo en el título de la pestaña, sonido y vibración al terminar.
- Lista de tareas por sesión (se guarda en el dispositivo).
- Ajustes de duración, rondas, inicio automático y sonido.

## Desarrollo local

```bash
python3 -m http.server 8080
# abrir http://localhost:8080
```

> Debe servirse por http/https (no funciona abriendo el archivo con `file://`).

## Stack

HTML + CSS + React (UMD) compilado en el navegador. Sin dependencias de build.
Identidad visual del Hospital San Diego de Alcalá.
