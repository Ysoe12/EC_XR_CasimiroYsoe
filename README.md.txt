# EC XR Interaction Challenge

- Apellidos y nombres: Casimiro, Ysoe
- Curso: Laboratorio de Realidad Extendida (XR) para Videojuegos
- Docente:Victor Alejandro Arroyo Castro

## Descripción
Sala de entrenamiento XR desarrollada en Unity 6 con URP. Incluye objetos manipulables con física, una interfaz espacial que se controla con el rayo y teletransporte.

## Funcionalidades implementadas
- Escena `EC_XR_CasimiroYsoe` con piso, iluminación, 4 paredes como límites visuales y 5 objetos 3D.
- Objetos manipulables con Rigidbody y XR Grab Interactable (Movement Type: Velocity Tracking).
- Interacción a distancia: botón en World Space UI que apaga la luz al usar el rayo.
- Reto libre: teletransporte con Teleportation Area sobre el piso.

## Controles
Se usa el XR Device Simulator: mantener Left Shift o Space para controlar cada mano, y el clic del mouse para seleccionar o agarrar. Las teclas se muestran en pantalla al dar Play.

## Capturas , en la carpeta CAPTURAS EN LA RAIZ DEL PROYECTO
Vista general del escenario:
![Escena](Capturas/1.jpg)

Configuración en el Inspector (Rigidbody y XR Grab Interactable):
![Inspector](Capturas/2.jpg)

Interacción funcionando:
![Interacción](Capturas/3.jpg)

## Tecnologías y paquetes utilizados
- Unity 6000.3.10f1 (URP)
- XR Interaction Toolkit 3.3.2
- XR Plugin Management 4.5.4
- OpenXR Plugin 1.16.1
- TextMeshPro
- XR Device Simulator