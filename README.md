# Puzzle·CAM

Puzzle·CAM es una aplicación web que convierte una selfie en un rompecabezas interactivo controlado únicamente con gestos de las manos.

Juega con tus amigos, resuelve el puzzle y crea selfies de una manera diferente. Todo el procesamiento ocurre directamente en tu navegador, por lo que ninguna imagen se envía a servidores externos.

---

## Funciones

- Captura fotografías utilizando únicamente gestos con las manos.
- Detección de manos en tiempo real mediante MediaPipe Hands.
- Convierte automáticamente cada fotografía en un rompecabezas de 3×3.
- Mueve las piezas utilizando gestos.
- Completa tres rondas para generar una tira fotográfica.
- Descarga el resultado en formato PNG.
- Todo el procesamiento se realiza localmente en el navegador.

---

## Cómo jugar

### 1. Permite el acceso a la cámara

Al abrir la aplicación, concede permiso para utilizar tu cámara.

### 2. Captura una fotografía

Haz un gesto de **Pinch** con ambas manos y mantenlo durante aproximadamente **1.5 segundos**.

La aplicación iniciará una cuenta regresiva y capturará automáticamente la fotografía.

### 3. Resuelve el rompecabezas

La imagen capturada se dividirá en nueve piezas.

Para mover una pieza:

- Haz Pinch sobre ella.
- Arrástrala hasta otra posición.
- Suelta el gesto para colocarla.

### 4. Confirma la ronda

Cuando el rompecabezas esté completo, cierra un puño para confirmar la fotografía.

### 5. Repite el proceso

Completa tres fotografías diferentes.

### 6. Descarga tu tira fotográfica

Al finalizar, Puzzle·CAM generará automáticamente una tira con las tres fotografías lista para descargar.

---

## Tecnologías

- HTML5
- CSS3
- JavaScript (Vanilla)
- Canvas API
- WebRTC (getUserMedia)
- MediaPipe Hands

---

## Dependencias

El proyecto utiliza versiones fijas de MediaPipe para mantener la compatibilidad.

```html
<script src="https://cdn.jsdelivr.net/npm/@mediapipe/hands@0.4.1675469240/hands.js"></script>
<script src="https://cdn.jsdelivr.net/npm/@mediapipe/drawing_utils@0.3.1675466124/drawing_utils.js"></script>
```

No requiere instalación mediante npm ni frameworks adicionales.

---

## Instalación

Clona el repositorio.

```bash
git clone https://github.com/0xjuarez/puzzle-cam.git
```

Entra al directorio.

```bash
cd puzzle-cam
```

Inicia un servidor local.

```bash
python3 -m http.server
```

Abre tu navegador en:

```
http://localhost:8000
```

---

## Estructura

```
Puzzle-CAM/
│
├── index.html
```

---

## Gestos disponibles

| Gesto | Acción |
|--------|--------|
| Pinch con ambas manos | Capturar fotografía |
| Pinch con una mano | Mover una pieza |
| Soltar Pinch | Colocar la pieza |
| Puño cerrado | Confirmar la ronda |

---

## Compatibilidad

Puzzle·CAM funciona correctamente en navegadores modernos compatibles con WebRTC y MediaPipe.

Navegadores recomendados:

- Google Chrome
- Microsoft Edge
- Brave
- Opera

---

## Próximas mejoras

- Diferentes niveles de dificultad.
- Rompecabezas de mayor tamaño.
- Más gestos.
- Nuevos filtros para las fotografías.
- Exportación en distintos formatos.
- Compartir directamente en redes sociales.

---

## Apoya el proyecto

Si Puzzle·CAM te resultó útil o simplemente te gustó la idea, puedes apoyar el desarrollo del proyecto.

<p align="center">
  <a href="https://buymeacoffee.com/pm5146003l" target="_blank">
    <img src="https://img.buymeacoffee.com/button-api/?text=Buy%20me%20a%20coffee&emoji=&slug=pm5146003l&button_colour=FFDD00&font_colour=000000&font_family=Arial&outline_colour=000000&coffee_colour=ffffff" alt="Buy Me A Coffee">
  </a>
</p>

O visita:

**https://buymeacoffee.com/pm5146003l**

---

## Licencia

Este proyecto está disponible bajo la licencia MIT.

---

## Autor

**Jesús Juárez**

GitHub: https://github.com/0xjuarez

Portfolio: https://juarezsec.dev

**DevSecurityMX**

https://devsecuritymx.com
